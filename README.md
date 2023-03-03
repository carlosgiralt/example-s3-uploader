# Serverless S3 Upload

This is a serverless application that allows users to upload files directly to an AWS S3 bucket using pre-signed URLs, and then informs an API with the filenames of the uploaded files.

## Requirements
- Python 3.x
- AWS CLI
- Serverless Framework
- pytest (for running unit tests)

## Installation

#### 1. Install the serverless framework:
```bash
npm install -g serverless
```

#### 2. Install the required Python packages:
```bash
poetry install
```

#### 3. Configure the AWS CLI with your AWS credentials:
```bash
aws configure
```

#### 4. Deploy the application
```bash
serverless deploy
```

## Testing
To run the unit tests, use the following command:
```bash
python -m unittest discover -s tests
```

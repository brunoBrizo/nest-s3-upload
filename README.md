# 🚀 NestJS AWS S3 File Upload

This repository contains a NestJS application that demonstrates how to upload a file to an AWS S3 bucket.

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of [Node.js](https://nodejs.org/)
- You have a Windows machine. This guide is tailored for Windows users.
- You have read the [NestJS documentation](https://docs.nestjs.com/).
- You have an AWS Account with an S3 Bucket configured.

## 🛠️ Installation

To install the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/brunoBrizo/nest-s3-upload.git
   ```

2. Navigate into the project directory and install the dependencies:
   ```bash
   cd your-repo-name
   yarn
   ```

3. Create a .env file in the root directory of the project and add your AWS credentials and S3 bucket name:
   ```bash
   AWS_ACCESS_KEY_ID=
   AWS_SECRET_ACCESS_KEY=
   AWS_REGION=
   S3_BUCKET_NAME=
   UPLOAD_RATE_TTL=
   UPLOAD_RATE_LIMIT=
   ```

## 🚀 Running the Application

To run the application, follow these steps:

1. Start the NestJS application:
   ```bash
   yarn dev
   ```


The application will be running at `http://localhost:3000`.

## 📦 Usage

To upload a file, make a POST request to `http://localhost:3000/upload` with the file in the body of the request.

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

## 📝 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

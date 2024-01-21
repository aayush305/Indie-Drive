# Indie Drive

Indie Drive is a cloud-based file management service, designed to offer an intuitive and secure platform for storing and sharing files. Built using Django and deployed on AWS, it provides a reliable and scalable solution for users needing online storage and collaboration.

## Features

- **Cloud-Based Storage:** Files are securely stored in AWS S3.
- **Database Management:** Utilizes AWS RDS for efficient and secure database handling.
- **File Sharing:** Share files with other users with ease.
- **Email Notifications:** Automated email alerts through AWS Lambda functions when files are shared.
- **User-Friendly Interface:** Built using Django for a smooth user experience.
- **Scalable Architecture:** Deployed on AWS EC2, ensuring reliable performance and scalability.

## Getting Started

To start using Indie Drive, follow these steps:
1. **Set up an AWS Account:** If you don't already have an AWS account, create one at [AWS Sign Up](https://aws.amazon.com/). You'll need access to S3, RDS, EC2, and Lambda services. For help setting up these services, refer to AWS's documentation or these guides:
   - [Getting Started with Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/gsg/GetStartedWithS3.html)
   - [Amazon RDS Setup Guide](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_GettingStarted.html)
   - [Launching an EC2 Instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
   - [Creating AWS Lambda Functions](https://docs.aws.amazon.com/lambda/latest/dg/getting-started-create-function.html)
2. **Clone the Repository:**
3. **Install the requirements:**
    ```
    pip install -r requirements.txt
    ```
4. **Run the server:**
    ```
    python manage.py runserver
    ```
## Tech Stack

Indie Drive is built with a combination of powerful technologies and services. Here's a quick overview of our main tech stack:

- **Frontend:**
  - HTML, CSS, JavaScript: For building a user-friendly interface.
  - Django Templates: For dynamic rendering of web pages.

- **Backend:**
  - Django: A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
  - Python: The core programming language used for backend logic.

- **Database:**
  - AWS RDS: For reliable and scalable database storage.

- **Storage:**
  - AWS S3: Used for storing and retrieving any amount of data at any time.

- **Server:**
  - AWS EC2: For hosting the web application.

- **Function as a Service:**
  - AWS Lambda: Used for running code in response to events, such as sending email notifications when files are shared.

- **Email Service:**
  - AWS SES (Simple Email Service): For sending automated email notifications.

This tech stack was chosen for its robustness, scalability, and the seamless integration it offers for a cloud-based file management system like Indie Drive.


---

Indie Drive - Your Personal Cloud Storage and Sharing Solution.


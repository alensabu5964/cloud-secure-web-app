# cloud-secure-web-app
# Cloud Secure Blog Website

## Project Overview

Cloud Secure Blog Website is a secure web application developed and deployed on AWS Cloud following DevSecOps best practices.

The application allows users to register, log in, create blog posts, manage content, upload media files, and perform CRUD operations through a secure role-based access control system.

This project demonstrates cloud infrastructure deployment, cybersecurity implementation, Linux administration, DevOps automation, monitoring, and logging.

---

## Features

### User Features

* User Registration
* User Login
* JWT Authentication
* Secure Password Hashing using bcrypt
* Create Blog Posts
* Edit Blog Posts
* Delete Blog Posts
* View Blog Posts
* Upload Blog Images

### Admin Features

* Manage Users
* Manage Blog Posts
* Role-Based Access Control
* View Uploaded Files

---

## Security Features

* Password Hashing (bcrypt)
* JWT Authentication
* SQL Injection Prevention
* XSS Protection using Helmet
* Secure HTTP Headers
* HTTPS/SSL Encryption
* Role-Based Access Control
* Security Groups and Firewall Rules
* Rate Limiting Protection

---

## AWS Services Used

* Amazon EC2
* Amazon VPC
* Amazon S3
* Amazon CloudWatch
* Security Groups
* Internet Gateway
* Route Tables

---

## Technology Stack

### Frontend

* HTML
* CSS
* Bootstrap
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MySQL

### Security

* JWT
* bcrypt
* Helmet
* Express Rate Limit

### DevOps

* Git
* GitHub
* Docker
* GitHub Actions

---

## Architecture

User Browser
↓
Internet
↓
Nginx Reverse Proxy
↓
Node.js Application
↓
MySQL Database
↓
AWS Cloud Infrastructure

---

## Project Structure

cloud-secure-blog-website

├── config

│   └── db.js

├── middleware

│   └── authMiddleware.js

├── routes

│   ├── auth.js

│   └── posts.js

├── uploads

├── public

│   ├── css

│   └── js

├── views

├── server.js

├── package.json

└── README.md

---

## Installation

### Clone Repository

git clone <repository-url>

cd cloud-secure-blog-website

### Install Dependencies

npm install

### Configure Environment Variables

Create a .env file:

DB_HOST=localhost

DB_USER=root

DB_PASSWORD=password

DB_NAME=blogdb

JWT_SECRET=your_secret_key

PORT=3000

### Start Application

node server.js

or

npm start

---

## AWS Deployment

1. Create VPC
2. Create Public and Private Subnets
3. Configure Internet Gateway
4. Configure Route Tables
5. Create Security Groups
6. Launch EC2 Instance
7. Install Node.js and Nginx
8. Deploy Application
9. Configure HTTPS
10. Configure Monitoring

---

## Monitoring

Application monitoring is performed using Amazon CloudWatch.

Monitored Metrics:

* CPU Usage
* Memory Usage
* Network Traffic
* Application Logs
* Failed Login Attempts

---

## Backup Strategy

* Database Backups stored in Amazon S3
* Uploaded Media Backups stored in Amazon S3
* Automated Backup Scripts using Cron Jobs

---

## DevOps Pipeline

GitHub
↓
GitHub Actions
↓
Build
↓
Test
↓
Deploy
↓
AWS EC2

---

## Future Enhancements

* Multi-Author Blogging
* Comment System
* Email Notifications
* Search Functionality
* Social Media Integration
* Advanced Analytics Dashboard

---

## Author

Alen Sabu

Cloud-Based Secure Blog Website (DevSecOps Capstone Project)

---

## License

This project is developed for educational and academic purposes.

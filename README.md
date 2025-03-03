AWS S3 Static Website Hosting Project
Overview
This project demonstrates how to host a static website using Amazon S3. The website is a simple HTML page with associated assets, fully hosted on S3, showcasing how to leverage AWS for static content delivery.
![s3-architecture](https://github.com/user-attachments/assets/ac866ea6-6ef6-4a66-a6ee-e3a7d9b513f0)
Features

Static Website Hosting: Accessible via a public URL provided by S3.
Custom Error Pages: Configured custom error pages for a better user experience.
Access Management: Implemented AWS S3 Bucket Policies and ACLs to control public access.
Setup and Deployment

Step 1: Create an S3 Bucket
Log in to the AWS Management Console.
Navigate to the S3 service.
Create a new bucket:
Give it a unique name (e.g., my-awesome-website-bucket).
Choose a region closest to your target audience (e.g., Asia Pacific (Mumbai) ap-south-1).
Enable ACLs:
During bucket creation, under "Object Ownership," select ACLs enabled.
This allows fine-grained control over the permissions of individual objects in the bucket.
Creating an S3 bucket

![Screenshot 2025-03-03 170441](https://github.com/user-attachments/assets/c883bcb4-cfc4-46ad-b37f-20e533c2015d)


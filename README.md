**AWS S3 Static Website Hosting Project Overview**
This project demonstrates how to host a static website using Amazon S3. The website is a simple HTML page with associated assets, fully hosted on S3, showcasing how to leverage AWS for static content delivery.
![s3-architecture](https://github.com/user-attachments/assets/ac866ea6-6ef6-4a66-a6ee-e3a7d9b513f0)
**Features**

Static Website Hosting: Accessible via a public URL provided by S3.

Custom Error Pages: Configured custom error pages for a better user experience.

Access Management: Implemented AWS S3 Bucket Policies and ACLs to control public access.

**Setup and Deployment**
Step 1: Create an S3 Bucket
Log in to the AWS Management Console.
Navigate to the S3 service.
**Create a new bucket:** 
Give it a unique name (e.g., my-awesome-website-bucket).
Choose a region closest to your target audience (e.g., Asia Pacific (Mumbai) ap-south-1).
Enable ACLs:
During bucket creation, under "Object Ownership," select ACLs enabled.
This allows fine-grained control over the permissions of individual objects in the bucket.
**Creating an S3 bucket**

![Screenshot 2025-03-03 170441](https://github.com/user-attachments/assets/c883bcb4-cfc4-46ad-b37f-20e533c2015d)

**Step 2: Not to enable Block access**

To host a static website on AWS S3, you must disable "Block Public Access" for the bucket to allow public access to the website files. This ensures that users can access the hosted content via the website URL.

![Screenshot 2025-03-03 170509](https://github.com/user-attachments/assets/d1aa2bd5-3e17-4169-9681-3256b4ddc6f5)


**Step 3: Upload Files**

**Upload your website files:**
Upload index.html and the unzipped folder to the S3 bucket.
Ensure the directory structure is preserved during the upload.

![Screenshot 2025-03-03 170655](https://github.com/user-attachments/assets/94e32698-b205-4b9d-b070-195a35f5bd60)

**Step 4: Configure the Bucket for Static Website Hosting**

After  uploading files and folders you wanted go to properites section and scrool down to static web hosting
Go to the bucket properties in the S3 console.
Enable static website hosting:
In the "Static website hosting" section, choose Enable.
Set index.html as the Index document.
Optionally, set a custom error document like error.html.

![Screenshot 2025-03-03 170104](https://github.com/user-attachments/assets/196fd832-287a-47dd-b1da-f809ead07229)











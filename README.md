# Simple-static-website-hosted-on-AWS S3
A beginner level project. 
Here a simple static website is hosted on Amazon S3.

Services Used:
Amazon S3 (Simple Storage Service)

![Amazon S3](https://github.com/AbdulR431/Simple-static-website-hosted-on-AWSS3/blob/main/Images/Amazon%20s3.png)

Brief about Amazon S3:
Amazon S3 (Simple Storage Service) is a cloud-based object storage service offered by Amazon Web Services (AWS). It provides a scalable and durable way to store and retrieve any amount of data from anywhere on the web.   

Key features of Amazon S3:
Scalability: S3 can handle virtually unlimited amounts of data, making it suitable for large-scale storage needs.   
Durability: Amazon S3 is designed to provide 99.999999999% durability for your data, ensuring it's protected against loss or corruption.
Availability: S3 offers high availability, with 99.99% availability by default, ensuring your data is accessible whenever you need it.   
Security: S3 provides robust security features, including access control lists (ACLs), encryption, and data transfer acceleration.   
Cost-effective: S3 offers various storage classes to help you optimize costs based on your data access patterns and retention requirements.   

Common use cases for Amazon S3:
Data lakes: Storing large datasets for analytics and machine learning.   
Web applications: Storing static content like images, videos, and HTML files.   
Backup and disaster recovery: Storing backups of your on-premises data.   
Content delivery: Distributing content to users globally using Amazon CloudFront.   
IoT data storage: Storing data generated by IoT devices.   
Overall, Amazon S3 is a versatile and reliable storage solution for a wide range of applications.   

# Steps
# Step 1:

Create a S3 bucket.

# Step 2:
 Go to properties of the bucket
 At the bottom we can find the option to enable hosting of static website
 By default it is disabled
 we have to enable it inorder to host our website by entering the html file name.

![Enabling Static website hosting](https://github.com/AbdulR431/Simple-static-website-hosted-on-AWSS3/blob/main/Images/s3%20bucket%20enabling%20static%20website%20hosting.PNG)

# Step 3:
 Now we get an url of the bucket.
 we can find that it is not working.
 Because we have not uploaded the html file and have not given necessary permissions to the bucket.
 Let us give the permissions to the bucket by attaching the policy.

 ![Attached policy](https://github.com/AbdulR431/Simple-static-website-hosted-on-AWSS3/blob/main/Images/S3%20bucket%20policy.PNG)

 Also by default public access is not allowed for the bucket we have to change it.

 ![unblocked the access to the S3 bucket](https://github.com/AbdulR431/Simple-static-website-hosted-on-AWSS3/blob/main/Images/S3%20bucket%20Access.PNG)

 # Step 4:
Now lets upload the necessary files to the bucket as a final step.

Our Website is successfully hosted !!
We can access our website 

![Final Output](https://github.com/AbdulR431/Simple-static-website-hosted-on-AWSS3/blob/main/Images/project%20output.PNG)

It is a very basic project.

# Thank You

# The End .

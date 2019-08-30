# Spring-Boot-API-Upload-Files-AWS-S3
This is a simple Spring Boot restful API for upload and delete files to AWS S3 bucket
# download the zip file and extract it and import as a existing maven project in Eclipse or InteliJ
# Upload (POST) API : http://localhost:8080/v1/storage/uploadFile   
# Delete (Delete) API : http://localhost:8080/v1/storage/deleteFile

# Required Software 
1. Java 8 with JCE unlimited security Jar
2. Maven 

# Step 
1. Create AWS account
2. Create User from IAM and assign policy AWSS3fullaccess programatically ( So this user will get the all S3 bucket access through CLI or progam not console )
3. download the access key and Access ID 
4. Change the access key and access ID in application.yml file
5. Create Bucket from S3 service with default configuration
6. provide the bucket name and endpoint url of this bucket in the application.yml file

# Check My YouTube Channel :  https://www.youtube.com/c/techtalkdebu
# Contact mmy FB page : techtalk debu


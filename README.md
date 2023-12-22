# Deploy Static Website on AWS

In this project, I deployed a static website to AWS using S3, CloudFront, and IAM.

The website can be access at:

+ S3 Object: https://my-static-website-user492329421376.s3.us-east-2.amazonaws.com/index.html
+ Website endpoint: http://my-static-website-user492329421376.s3-website.us-east-2.amazonaws.com/
+ Cloudfront: https://d11od07eiy97m7.cloudfront.net/

## Step 1 - Create an S3 Bucket

!(Create S3 Bucket)[https://github.com/JustinMckee/AWS-static-website-basics/blob/main/readme-img/1-s3-bucket.png]

## Step 2 - Add Files to Bucket

!(Add Files to Bucket)[https://github.com/JustinMckee/AWS-static-website-basics/blob/main/readme-img/2-files.png]

The files included are: 

+ index.html - The Index document for the website.
+ /img - The background image file for the website.
+ /vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
+ /css - CSS files for the website.

## Step 3 - Setup the Bucket for Public, Static Hosting

!(Setup the bucket for static website hosting)[https://github.com/JustinMckee/AWS-static-website-basics/blob/main/readme-img/3-bucket-static-hosting.png]

## Step 4 - Add IAM Bucket Permissions

!(Add IAM Bucket policy/permissions)[https://github.com/JustinMckee/AWS-static-website-basics/blob/main/readme-img/4-IAM-bucket-permissions.png]

## Step 5 - Deploy Cloudfront Distribution

!(Deploy Cloudfront Distribution)[https://github.com/JustinMckee/AWS-static-website-basics/blob/main/readme-img/5-cloudfront.png]
Repo from [article](https://medium.com/@krish.joshi.02/migration-between-google-drive-and-s3-bucket-c3ddd0b7b507) on moving GDrive content to S3.

*Paused implementation as wasn't confident this method met my requirements for security and large file size.*



# S3 Public Bucket Creation
1. Create a public bucket
1. Create an IAM user with Admin and S3 full access
1. Login as this user, create Access Key for Local Code option, store it
1. In the the S3 Console, create an Access point by choosing the bucket and set it to public access.


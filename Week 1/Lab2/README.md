# Task 2: Create Amazon S3 bucket with bucket policies and life cycle management

1. Launch AWS Console
2. Create a S3 bucket with enforced ownership
3. Create a single lifecycle policy
4. Create a single bucket policy
5. Delete all policies
6. Delete S3 bucket



For guide, kindly visit

https://docs.aws.amazon.com/cli/latest/reference/s3api/create-bucket.html

https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html

https://docs.aws.amazon.com/cli/latest/userguide/cli-services-s3-commands.html




**Launch AWS Console
*I opened Aws

**create s3 bucket
*launched S3bucket, created bucket    **crystalsmile

*I choose the Ec2, clicked management tab, and created lifecycle rule  **policy-07324a8cb3b8ff90e.

**create bucket policy: *I clicked the console, clicked the **crystalsmile bucket, choose permission
Edited bucket policy, choose policy generator
on the policy generator, I picked s3 bucket policy.
amazon resource name:   arn:aws:s3:::crystalsmile

{
  "Id": "Policy1653410529467",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1653407699483",
      "Action": [
        "s3:CreateBucket"
      ],
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::crystalsmile",
      "Principal": {
        "AWS": [
          "mariam"
        ]
      }
    }
  ]
}

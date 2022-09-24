# Tutorial 7) A) Practice AWS Cloud Shell, Run Python Program from Cloud Shell & Create S3 Bucket from Cloud Shell.

Task 1) Practice bash commands: sudo, ls, mkdir, touch, mv, nano, rm -rf | Choose Bash Shell | Create Folder name Project. | Move Python file to Folder.
Task 2) Upload & Download File from Cloud Shell.
Task 3) Test & Run Python File (program.py) from Cloud Shell. (Python Program attached or you can run your own python program)
Task 4) Run following command & Create s3 Bucket, Upload multiple files & delete bucket at last 
  in US east Region: 
aws s3api create-bucket --bucket name-of-your-bucket --region us-east-1
aws s3 sync . s3://name-of-your-bucket
aws s3 rb s3://name-of-your-bucket --force
Tip: Paste Unique Bucket name in place of (insert-unique-bucket-name-here) from above command.
Terminate the bucket after Practice. Choose Bash Shell - (Attached shell.txt for reference.)
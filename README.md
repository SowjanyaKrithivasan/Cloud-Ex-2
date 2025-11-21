# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS

## Name: SOWJANYA K
## Register Number:212223090023
 
# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2
instance in AWS.
# Procedure
a) Steps to Create a first S3 Bucket:

## Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
## Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service
dashboard.
## Step 3: Create Bucket
Click the Create bucket button.
## Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name.
• AWS Region: Select the region where you want to store your data.

## Step 5: Object Ownership
Choose between:
▪ ACLs disabled (recommended) – Bucket owner has full control.
▪ ACLs enabled – Control access via access control lists.

## Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need
public access.
## Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
## Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
## Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
## Step 10: Create the Bucket
Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

1. Go to the EC2 Dashboard in AWS Console.
2. Click on “Launch Instance”.
3. Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4. Select an instance type (e.g., t2.micro for Free Tier).


5. Create or choose a key pair for SSH access.
6. Configure network settings (use default VPC/subnet).
7. Configure storage (default root volume is fine).
8. Review the settings and click “Launch Instance”.
9. Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key.
• Windows: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)

1. Go to EC2 Instances.
2. Select your instance → Instance State → Terminate.
# Output

<img width="1018" height="473" alt="image" src="https://github.com/user-attachments/assets/632c5422-2d7a-4f56-9a02-89d89eb0a6ed" />


<img width="1002" height="476" alt="image" src="https://github.com/user-attachments/assets/0b64c8a8-43f3-4931-904b-a484424bc70a" />


<img width="1919" height="858" alt="Screenshot 2025-11-01 114447" src="https://github.com/user-attachments/assets/c22cf567-5d14-4e32-9c8e-ae360ed683d5" />

# Result
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance
has been successfully created and launched in AWS


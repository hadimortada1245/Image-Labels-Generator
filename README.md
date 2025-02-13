Image Labels Generator
Overview
This project utilizes AWS Rekognition to analyze images stored in an Amazon S3 bucket and generate labels with confidence scores. The integration includes IAM for authentication, AWS CLI for interaction, and a Python script for automation.

How It Works
1️⃣ Upload the Image – Store an image in an Amazon S3 bucket.
2️⃣ Image Processing – The image is analyzed using AWS Rekognition to detect labels.
3️⃣ AI-Powered Label Detection – Labels are identified along with their confidence levels.
4️⃣ Secure Access – IAM (Identity and Access Management) is used for authentication and access control.
5️⃣ AWS CLI Integration – The AWS Command Line Interface is used to interact with AWS services.
6️⃣ Python Script Execution – The main Python file:

Extracts the image from S3
Runs the detect_labels operation using AWS Rekognition
7️⃣ Configuration Setup – Ensure that:
The S3 bucket region matches the IAM region
The bucket name and image name are updated correctly in the script
8️⃣ Output Generation – The script provides:
Number of detected labels based on input
Confidence scores for each label
9️⃣ Visual Display – A pop-up screen is generated:
Displays the selected image from S3
Bounding boxes highlight detected labels
Setup & Usage
Configure AWS IAM permissions.
Ensure AWS CLI is installed and configured.
Upload an image to your Amazon S3 bucket.
Update the Python script with the correct bucket name and image name.
Run the script to analyze the image and generate labels.

Technologies Used
AWS S3 – Image storage
AWS Rekognition – Image analysis & label detection
AWS IAM – Authentication & access management
AWS CLI – Interaction with AWS services

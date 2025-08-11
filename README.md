# AWS-projects
# Amazon Rekognition Image Analysis Demo

## 📌 What It Does
This project uses **Amazon Rekognition** to analyze an image stored in **Amazon S3** and detect labels (objects, scenes, and concepts) within it.  
It demonstrates how AWS Rekognition can be used for computer vision tasks like image classification, moderation, and facial recognition.

---

## 🛠 How I Built It
1. Uploaded an image to an **Amazon S3** bucket.
2. Wrote a **Python script** using the **Boto3 AWS SDK** to:
   - Connect to Amazon S3.
   - Call the Rekognition `detect_labels` API.
   - Print out detected labels with confidence scores.
3. Ran the script locally to test the detection.

---

## ⚡ Challenges I Solved
- Learned how to configure AWS credentials (Access Key & Secret Key) securely.
- Understood how Rekognition expects input from S3 rather than a local file.
- Managed IAM permissions so the script could access both S3 and Rekognition.

---

## ☁ AWS Services Used & Why
- **Amazon Rekognition** → For AI-powered image analysis and label detection.
- **Amazon S3** → To store the image and make it accessible to Rekognition.
- **AWS IAM** → To create secure credentials and manage service permissions.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/amazon-rekognition-demo.git
   cd amazon-rekognition-demo

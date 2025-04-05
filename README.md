# ☁️ AWS Cloud Automation with Python

> **Summer Internship Project | Guided by Mr. Vimal Daga**  
> **Domain:** AWS Cloud | Python Automation | Event-Driven Architecture | Cloud DevOps

---

## 📌 Project Description

This Python-based, menu-driven project focuses on automating and managing various AWS Cloud operations through a unified CLI interface. Designed during my summer internship, the project integrates core AWS services such as **EC2**, **S3**, **Lambda**, **SES**, and **Transcribe**, demonstrating powerful automation workflows using Python and `boto3`.

The system allows users to:

- Launch EC2 instances with GUI-based RHEL OS
- Access CloudWatch logs on-demand
- Implement event-driven architecture for audio-to-text conversion via AWS Transcribe
- Upload files to S3 and trigger Lambda functions for automated actions
- Connect to MongoDB from AWS Lambda
- Automate email campaigns using SES by reading email IDs from S3

---

## 🛠️ Technologies & Services Used

| Technology        | Purpose                                             |
|------------------|-----------------------------------------------------|
| **Python**        | Core scripting for automation and menu interface   |
| **Boto3**         | AWS SDK for Python to interact with cloud services |
| **AWS EC2**       | Launch and manage Linux instances in the cloud     |
| **AWS S3**        | Store and retrieve files and email lists           |
| **AWS Lambda**    | Run serverless functions triggered by S3 events    |
| **AWS SES**       | Send automated emails to a list of recipients      |
| **AWS Transcribe**| Convert audio files (e.g., MP3) into text          |
| **MongoDB Atlas** | Store and query data from Lambda                   |

---

## 💡 Features

- **EC2 RHEL Launching**: Spin up a GUI-based Red Hat instance with pre-defined configurations.
- **CloudWatch Log Access**: Retrieve logs from any log group/stream via user input.
- **Audio Transcription**: Upload audio to S3 and get transcriptions using AWS Transcribe.
- **Lambda + MongoDB**: Push sample data into MongoDB from Lambda function securely.
- **File Uploading**: Upload files to S3 for backups or automation triggers.
- **Email Automation**: Trigger Lambda from S3 to send bulk emails via SES.

---

## 🧩 Project Structure

├── main.py # Core menu-based logic and AWS interactions ├── lambdahandler.py # Lambda function code triggered by S3 to send emails ├── main.env # MongoDB connection URI (for local use) ├── README.md # Project documentation

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/aws-cloud-automation.git
   cd aws-cloud-automation
2. Set up your Python environment:
     ```
   pip install boto3 pymongo
   
3. Configure your AWS credentials using:
    ```
    aws configure
4. Run the application:
   ```
   python main.py
5. Deploy lambdahandler.py in AWS Lambda and configure S3 triggers.

📈 Outcome
This project showcases real-world use of AWS for cloud automation and DevOps integration, demonstrating:

Infrastructure provisioning

Event-driven cloud architecture

Serverless computing

Secure data integration and processing

Email marketing automation through cloud services

🔮 Future Enhancements
Integrate a GUI-based interface (e.g., Tkinter or PyQT)

Add IAM Role integration and enhanced security policies

Expand support to AWS Glue, Rekognition, and Comprehend

ML model integration for predictive analytics

Enable multi-cloud compatibility (Azure, GCP)

👨‍💻 Author
Ritik Kumar
Cloud & Security Enthusiast | MCA Final Year
Summer Intern under mentorship of Mr. Vimal Daga
[Connect with me on LinkedIn](https://www.linkedin.com/in/ritikumarsahu/)


⚠️ This project was developed solely for educational and academic purposes. All resources and credentials should be used ethically and responsibly.

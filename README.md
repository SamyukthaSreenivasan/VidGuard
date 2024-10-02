# VidGuard

## Project Overview
VidGuard is a comprehensive solution designed to enhance the trustworthiness of video content by verifying creator credentials, ensuring proper attribution, and detecting tampering. Our goal is to combat misinformation and provide a transparent system for video verification.

## Features
- **Creator Credential Verification**: A blockchain-based system to track and verify the credentials of content creators.
- **Attribution**: Cryptographically signed metadata and watermarks for traceability of video origins and edits.
- **Tampering Detection**: AI-powered models that identify manipulations such as deepfakes and frame edits.

## Technologies Used
- Blockchain
- Machine Learning
- Generative AI
- Deep Learning
- Perceptual Hashing
- Python
- TensorFlow
- OpenCV
- Flask
- AWS
- Docker
- SQL
- REST APIs

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-link.git

###  **Other Files**
- **requirements.txt**
   ```plaintext
   Flask
   TensorFlow
   OpenCV-python
   PyCryptodome
   web3
   numpy
   pandas
   scikit-learn
# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the requirements file and install dependencies
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code
COPY . .

# Expose the application port
EXPOSE 5000

# Command to run the application
CMD ["python", "src/backend/app.py"]

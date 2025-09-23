# OTA Firmware Update Server

This project provides a minimal dashboard for uploading ESP32 firmware and enabling OTA updates.

## Deploy

1. Set up AWS S3, MongoDB Atlas, and grab credentials.
2. Set environment variables on Netlify:  
   - AWS_ACCESS_KEY_ID  
   - AWS_SECRET_ACCESS_KEY  
   - AWS_REGION  
   - S3_BUCKET  
   - MONGO_URI  

3. Push your code to GitHub.

4. Connect your GitHub repo to Netlify and deploy.

Backend and frontend will both work from https://your-site.netlify.app.

## Usage

- Open the dashboard, select your `.bin` file and version, upload.
- ESP32 code should point to:

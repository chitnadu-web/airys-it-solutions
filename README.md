# AIRYS IT Solutions

Website for airysitsolutions.com.

## Stack
- Node.js / Express
- HTML/CSS/JavaScript
- Nodemailer
- Zoho Mail SMTP

## Local setup
1. npm install
2. Create a local .env from .env.example.
3. Set your Zoho SMTP password in SMTP_PASS.
4. npm start
5. Open http://localhost:3000

## Production
Set SMTP_HOST=smtppro.zoho.in, SMTP_PORT=465, SMTP_SECURE=true, SMTP_USER=support@airysitsolutions.com, CONTACT_TO=support@airysitsolutions.com and SMTP_FROM=support@airysitsolutions.com as protected environment variables. Never commit the password or .env file.
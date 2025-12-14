# QuantC

QuantC is a secure, temporary file-sharing web application that allows users to upload files and retrieve them using a unique access code. All files are automatically deleted after 48 hours to ensure privacy and reduce data exposure.

# Live Application

You can access the hosted version here: https://quantcarya.vercel.app


## Features

*  Secure file upload and retrieval
*  Unique access code for each uploaded file
*  Automatic file deletion after 48 hours
*  No user accounts or personal data required
*  Clean and minimal web interface

## Tech Stack

* **Frontend:** React / Next.js
* **Backend:** Serverless APIs (Next.js API routes)
* **Hosting:** Vercel
* **Storage:** Secure temporary file storage

## How It Works

1. Upload a file through the web interface with a password.
2. Receive a unique access code.
3. Use the access code and password to retrieve or download the file.
4. Files are automatically deleted after 48 hours.

## Security

* Files are accessible only via unique access codes and password
* Files are fully encrypted and secure over the server
* No authentication or personal information required
* Automatic expiration prevents long-term data storage
* Designed for short-term, controlled file sharing

## Local Development

```bash
# Clone the repository
git clone https://github.com/s4sahiko/quantcarya.git

# Navigate to the project directory
cd quantc

# Install dependencies
npm install

# Run the development server
npm run dev
```

Open `http://localhost:3000` in your browser to view the app.

## Environment Variables

Create a `.env.local` file and configure any required environment variables:

```env
# Example
STORAGE_KEY=Your_Storage_Key

```

## Future Improvements

* File size and type restrictions
* Download limits
* Time extension for pro users

## Author
 **Aryan & Sahiko**

Built with ❤️ for secure and simple file sharing.

 

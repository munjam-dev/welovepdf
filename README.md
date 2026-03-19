We Love PDF

We Love PDF is a browser-based PDF toolkit designed to perform essential document operations entirely on the client side. It enables users to process PDF files instantly without uploading data to any server, ensuring speed, privacy, and reliability.

Overview

We Love PDF provides a unified interface for common PDF tasks such as merging, splitting, converting, and securing documents. The application is built with a modern UI and runs completely in the browser using JavaScript-based PDF libraries.

All file operations are executed locally, making the platform suitable for privacy-conscious users and offline usage.

Features
Document Management

Merge multiple PDF files into a single document

Split PDF files by page range

Remove selected pages

Extract specific pages

Reorder pages

Conversion Tools

Convert JPG images to PDF

Convert PDF pages to JPG images

Editing Capabilities

Rotate PDF pages

Add text watermarks

Insert page numbers

Security

Protect PDF files with passwords

Unlock password-protected PDFs

Optimization

Compress PDF files

Key Advantages

Client-side processing with no backend dependency

No file uploads or external storage

Fast execution with immediate results

Works offline after initial load

Clean and responsive user interface

Project Structure
we-love-pdf/
│
├── index.html          # Main application file
├── README.md           # Documentation
│
└── assets/             # Optional assets (if extended)
    ├── css/
    ├── js/
    └── images/
Technology Stack
Layer	Technology
Frontend	HTML5, CSS3, JavaScript
PDF Handling	pdf-lib
Rendering	pdf.js
Installation

Clone the repository:

git clone https://github.com/your-username/we-love-pdf.git
cd we-love-pdf
Usage

Open the application directly in a browser:

index.html

For better development experience, use a local server such as Live Server.

Deployment
GitHub Pages

Open repository settings

Navigate to Pages

Select the main branch

Save

The application will be available at:

https://your-username.github.io/we-love-pdf/
Vercel
npm install -g vercel
vercel

Or deploy using the Vercel dashboard by importing the repository.

Functional Modules
Feature	Function
Merge PDF	mergePDF()
Split PDF	splitPDF()
Remove Pages	removePages()
Rotate PDF	rotatePDF()
JPG to PDF	jpgToPDF()
PDF to JPG	pdfToJPG()
Watermark	addWatermark()
Page Numbers	addNumbers()
Extract Pages	extractPages()
Reorder PDF	reorderPDF()
Protect PDF	protectPDF()
Unlock PDF	unlockPDF()
Compress PDF	compressPDF()
Privacy

All processing is performed locally within the browser. Files are never uploaded or stored externally.

Support

Email: support@bisque-lapwing-145506.hostingersite.com

Author

Munjam Anjanna
Hyderabad, India

Roadmap

Drag and drop file support

Batch processing

OCR integration

AI-based document analysis

Cloud sync (optional future feature)

Contributing

Fork the repository

Create a new branch

Submit a pull request

License

This project is licensed under the MIT License.

Statement

We Love PDF is built with a focus on simplicity, speed, and privacy, enabling users to manage documents efficiently without relying on external services.

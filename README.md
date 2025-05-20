# Lab 08: Image-to-ASCII Converter
**Course:** CIS 485 - Web Programming II  
**Student:** Sam Lima   

## 🧠 Objective
This lab demonstrates how to:
- Use `npm` to manage Node.js packages
- Build a basic Express.js web app
- Upload and process image files using middleware
- Convert images into ASCII art using third-party libraries

## 🚀 Features
- Upload an image through a web form
- Convert the image to grayscale ASCII art
- Display the ASCII result directly in the browser
- Clean up uploaded files after processing

## 🛠️ Technologies Used
- **Node.js**
- **Express.js**
- **Multer** for handling file uploads
- **asciify-image** for image-to-ASCII conversion
- **strip-ansi** to clean up colored ASCII output

## 📂 Project Structure
lab-08/
├── app.js # Main Express application
├── public/ # Static files (e.g., CSS)
│ └── style.css
├── uploads/ # Temp storage for uploaded images
├── .gitignore # Ignoring node_modules and uploads
└── package.json # npm metadata

markdown
Copy
Edit

## 🖥️ How to Run Locally
1. Clone or download this repo
2. Run:
   ```bash
   npm install
   node app.js
Open your browser to http://localhost:3000

Upload an image and watch the ASCII magic happen!

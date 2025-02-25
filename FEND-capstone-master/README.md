
# 🌍 TravelOne App

## **📌 Project Overview**
**TravelOne** is a web application designed to help users **plan their trips** efficiently. It provides the latest **weather forecasts, country details, and images** of the destination using multiple APIs.

## **✅ Features**
- 🌤️ **Fetch weather forecast** for the selected destination.
- 🏞️ **Display an image** of the destination using Pixabay API.
- 🌍 **Show country details** (currency, language, etc.).
- 🔧 Built with **HTML, SCSS, JavaScript, Webpack, Node.js, and Express.js**.
- 💡 Uses **APIs** (Weather, GeoNames, Pixabay, RestCountries).
- ⚡ Optimized with **Webpack** for fast performance.

---

## **🚀 Getting Started**
Follow these steps to set up and run the project on your local machine.

### **1️⃣ Prerequisites**
Ensure you have the following installed:
- **Node.js 16.x** (**Recommended**)
- **npm** (comes with Node.js)
- A **modern web browser**

### **2️⃣ Installation**
1. Clone the repository:
   git clone https://github.com/yourusername/TravelOne-App.git
   cd TravelOne-App

   npm install

🌍 Environment Variables
This project requires API keys to fetch data. Create a .env file in the root directory and add:
USERNAME=<your_username>
WEATHER_KEY=<your_weather_api_key>
PIXABAY_KEY=<your_pixabay_api_key>


🛠 Running the Project
Development Mode
To run the project in development mode:


npm run build-dev
Production Mode
To build and run the project in production mode:


npm run build-prod
npm run start
Then, open your browser and visit:

http://localhost:8081
🧪 Running Tests
Run the test cases using:


npm run test
📂 Folder Structure
scss
📂 TravelOne-App
 ┣ 📂 src
 ┃ ┣ 📂 client
 ┃ ┃ ┣ 📂 js (Frontend logic)
 ┃ ┃ ┣ 📂 views (HTML templates)
 ┃ ┃ ┣ 📂 styles (SCSS styles)
 ┃ ┣ 📂 server
 ┃ ┃ ┣ server.js (Backend logic)
 ┣ 📜 package.json (Dependencies)
 ┣ 📜 webpack.dev.js (Development config)
 ┣ 📜 webpack.prod.js (Production config)
 ┣ 📜 .env (Environment variables)
 ┣ 📜 README.md (Project documentation)
🐞 Troubleshooting
Common Errors & Fixes
1️⃣ npm install fails due to node-gyp errors?

Make sure Python 3.10 is installed (not 3.12).
Run:

npm config set python C:\Path\To\Python310\python.exe
2️⃣ Node.js Version Issue?

If using Node.js 22 or 20, downgrade to Node.js 16:

nvm install 16
nvm use 16
3️⃣ Port Already in Use Error?

Kill the running process on port 8081:

npx kill-port 8081
👤 Author
Your Name
📩 Contact: your.email@example.com
🔗 GitHub: yourgithub

📜 License
This project is licensed under the MIT License.

📌 Correct Node.js Version for Your Project
Your project should work with Node.js 16.x.
Use the following command to install and switch to it:


nvm install 16
nvm use 16
Then verify:

node -v

---

### ✅ **Now you can copy everything at once! 🚀**  
Let me know if you need any modifications! 😊

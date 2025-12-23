✈️ AEROVIA – Travel & Exploration Platform

AEROVIA is a comprehensive travel platform designed for adventurers and explorers who want to discover, share, and review extraordinary places around the world. Built using the MERN stack (MongoDB, Express, React, Node.js), AEROVIA delivers a seamless, secure, and interactive experience for both casual travelers and serious wanderers.

🌍 Live Demo:
👉 https://github.com/anuj2905/Wanderlust

🚀 Features

✨ Create & Manage Listings

Add new travel destinations with rich descriptions and images

Manage and track your personal travel listings

🗺️ Explore Listings

Discover unique destinations shared by travelers worldwide

Interactive maps powered by Mapbox

⭐ Review & Rate Experiences

Share reviews of places you’ve visited

Learn from experiences shared by other users

🔐 Secure Authentication

User authentication handled securely using Passport.js

🧭 Interactive Maps

Visualize locations with Mapbox to plan trips effortlessly

🧑‍💻 Tech Stack

Frontend: React, EJS

Backend: Node.js, Express.js

Database: MongoDB (Atlas / Local)

Authentication: Passport.js

Maps: Mapbox

Image Hosting: Cloudinary

📚 Table of Contents

How to Contribute

Local Setup Guide

Environment Variables

Contributors

Contact

🤝 How to Contribute

We welcome contributions to improve AEROVIA 🚀

1️⃣ Fork the Repository

Go to the AEROVIA GitHub repository

Click Fork (top-right corner)

2️⃣ Clone Your Fork
git clone https://github.com/your-username/Wanderlust-2024.git
cd Wanderlust-2024

3️⃣ Create a New Branch
git checkout -b feature/your-feature-name

4️⃣ Make Your Changes

Add features, fix bugs, or improve documentation

5️⃣ Commit Changes
git add .
git commit -m "Add feature: short description"

6️⃣ Push to GitHub
git push origin feature/your-feature-name

🛠️ How to Set Up the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/Wanderlust-2024.git
cd Wanderlust-2024

2️⃣ Set Up Mapbox

Sign up at 👉 https://www.mapbox.com

Generate an Access Token

3️⃣ Set Up Cloudinary

Sign up at 👉 https://cloudinary.com

Copy:

Cloud Name

API Key

API Secret

4️⃣ Create .env File

In the root directory:

MAP_TOKEN=your-mapbox-access-token
ATLAS_DB_TOKEN=mongodb://127.0.0.1:27017/wanderlust
SECRET=your-secret-key
CLOUD_NAME=your-cloudinary-cloud-name
CLOUD_API_KEY=your-cloudinary-api-key
CLOUD_API_SECRET=your-cloudinary-api-secret
PORT=8080

5️⃣ Add .gitignore (Important)

Make sure .gitignore includes:

node_modules/
.env

6️⃣ Install Dependencies
npm install

7️⃣ Start the Server
npx nodemon


OR

node app.js

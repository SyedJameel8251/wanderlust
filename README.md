<h1 align="center">🌍 Wanderlust – Airbnb-Style Property Listing Platform</h1>

<p align="center">
  A Full-Stack Property Listing Web Application Inspired by Airbnb <br>
  Built using Node.js, Express, MongoDB Atlas & Deployed on Render
</p>

<p align="center">
  <a href="https://wanderlust-g19x.onrender.com/" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Demo-Visit%20Now-brightgreen?style=for-the-badge">
  </a>
  <a href="https://github.com/SyedJameel8251/wanderlust" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge">
  </a>
</p>

<hr>

<h2>🚀 Live Deployment</h2>

<p>
🔗 <strong>Live Website:</strong>  
<a href="https://wanderlust-g19x.onrender.com/">
https://wanderlust-g19x.onrender.com/
</a>
</p>

<p>
💻 <strong>GitHub Repository:</strong>  
<a href="https://github.com/SyedJameel8251/wanderlust">
https://github.com/SyedJameel8251/wanderlust
</a>
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
Wanderlust is a full-stack Airbnb-inspired web application that allows users to browse, create, edit, and review property listings.  
The platform includes secure authentication, session handling, RESTful routing, and cloud database integration.
</p>

<p>
This project demonstrates real-world backend architecture, production deployment practices, and database management using MongoDB Atlas.
</p>

<hr>

<h2>✨ Key Features</h2>

<ul>
  <li>🔐 User Authentication (Signup / Login / Logout)</li>
  <li>🏠 Create, Edit & Delete Property Listings</li>
  <li>⭐ Add & Delete Reviews</li>
  <li>🧭 RESTful Routing Architecture</li>
  <li>📂 MVC Project Structure</li>
  <li>💾 Cloud Database using MongoDB Atlas</li>
  <li>🔑 Secure Session Management</li>
  <li>💬 Flash Messages for User Feedback</li>
  <li>🌐 Production Deployment on Render</li>
  <li>📱 Responsive UI using EJS & Bootstrap</li>
</ul>

<hr>

<h2>🛠 Tech Stack</h2>

<h3>Backend</h3>
<ul>
  <li>Node.js</li>
  <li>Express.js</li>
  <li>MongoDB</li>
  <li>Mongoose ODM</li>
  <li>Passport.js (Authentication)</li>
  <li>Express-Session</li>
  <li>Connect-Flash</li>
</ul>

<h3>Frontend</h3>
<ul>
  <li>EJS (Embedded JavaScript Templates)</li>
  <li>HTML5</li>
  <li>CSS3</li>
  <li>Bootstrap</li>
</ul>

<h3>Deployment & Cloud</h3>
<ul>
  <li>MongoDB Atlas (Cloud Database)</li>
  <li>Render (Web Hosting)</li>
  <li>Environment Variables for Security</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
wanderlust/
│
├── models/        → Mongoose Schemas
├── routes/        → Route Controllers
├── views/         → EJS Templates
├── public/        → Static Assets (CSS, JS)
├── utils/         → Error Handling Utilities
├── init/          → Database Seeder
│
├── app.js         → Main Application File
├── middleware.js  → Custom Middleware
├── schema.js      → Joi Validation Schemas
└── package.json   → Dependencies & Scripts
</pre>

<hr>

<h2>⚙️ Installation & Local Setup</h2>

<h3>1️⃣ Clone the Repository</h3>

<pre>
git clone https://github.com/SyedJameel8251/wanderlust.git
cd wanderlust
</pre>

<h3>2️⃣ Install Dependencies</h3>

<pre>
npm install
</pre>

<h3>3️⃣ Create Environment Variables</h3>

Create a <code>.env</code> file in the root directory:

<pre>
ATLASDB_URL=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
</pre>

<h3>4️⃣ Start the Server</h3>

<pre>
npm start
</pre>

Visit:

<pre>
http://localhost:8080
</pre>

<hr>

<h2>🧪 Database Seeding</h2>

To initialize sample listings data:

<pre>
node init/index.js
</pre>

This will populate the MongoDB Atlas database with demo listings.

<hr>

<h2>🎯 Learning Outcomes</h2>

<ul>
  <li>Implemented MVC architecture in a real-world project</li>
  <li>Integrated Passport.js for secure authentication</li>
  <li>Managed sessions and flash messaging</li>
  <li>Connected cloud database (MongoDB Atlas)</li>
  <li>Debugged production deployment issues</li>
  <li>Deployed full-stack application on Render</li>
</ul>

<hr>

<h2>🔒 Security Implementation</h2>

<ul>
  <li>Environment variables for sensitive data</li>
  <li>Password hashing using Passport-local-mongoose</li>
  <li>Session-based authentication</li>
  <li>Express error handling middleware</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<strong>Syed Jameel</strong><br>
B.Tech Computer Science (2025)<br>
Aspiring Software Developer | Backend & Cloud Enthusiast<br>
</p>

<hr>

<h2>📜 License</h2>

<p>
This project is developed for academic and portfolio purposes.
</p>

<hr>

<p align="center">
⭐ If you found this project helpful, consider giving it a star on GitHub!
</p>

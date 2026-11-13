🏡 Wanderlust

🌍 Explore the World, One Stay at a Time!

Wanderlust is a full-stack Airbnb-inspired web application where users can explore property listings, discover places to stay, create and manage their own listings, and share reviews.

Built using Node.js, Express.js, MongoDB, and EJS, this project focuses on implementing real-world full-stack web development concepts.

---

✨ Features

- 🔐 User Authentication: Secure user signup, login, and logout functionality.
- 🏠 Property Listings: Browse and explore different property listings.
- ➕ Create Listings: Users can add their own properties.
- ✏️ Edit & Delete Listings: Manage your own property listings.
- ⭐ Reviews & Ratings: Users can share reviews and rate properties.
- 💬 Flash Messages: Display success and error notifications.
- 🛡️ Form Validation: Server-side validation for listings and reviews.
- ☁️ Cloud Image Handling: Cloud storage integration for listing images.
- 🗄️ MongoDB Atlas: Cloud-hosted database integration.
- 🔄 MVC Architecture: Organized codebase using the Model-View-Controller pattern.

---

🛠️ Tech Stack

🎨 Frontend

- HTML5
- CSS3
- JavaScript
- EJS
- Bootstrap

⚙️ Backend

- Node.js
- Express.js

🗄️ Database

- MongoDB
- Mongoose
- MongoDB Atlas

📦 Tools & Packages

- Passport.js (Authentication)
- Express Session
- Connect Flash
- Joi (Validation)
- Cloudinary (Image Storage)
- Multer (File Uploads)
- And other npm packages.

---

📂 Project Structure

Wanderlust/
│
├── controllers/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
│
├── init/
│   ├── data.js
│   └── index.js
│
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── public/
│   ├── css/
│   └── js/
│
├── routes/
│
├── utils/
│
├── views/
│   ├── includes/
│   ├── layouts/
│   ├── listings/
│   ├── users/
│   └── error.ejs
│
├── .env
├── app.js
├── cloudConfig.js
├── middleware.js
├── schema.js
├── package.json
└── package-lock.json

---

🚀 Getting Started

Follow these steps to run Wanderlust locally.

📋 Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB Atlas account

1️⃣ Clone the Repository

git clone https://github.com/SahilChoudhary1397/Wanderlust
cd Wanderlust

2️⃣ Install Dependencies

npm install

3️⃣ Configure Environment Variables

Create a ".env" file in the root directory and add the following:

ATLASDB_URL=your_mongodb_atlas_connection_string
SECRET=your_session_secret

Add your Cloudinary credentials too if required by your cloud configuration.

⚠️ Important: Never upload your ".env" file, database credentials, or secret keys to GitHub.

4️⃣ Run the Application

node app.js

Open your browser and visit the local address displayed in your terminal.

---

🏗️ Application Architecture

Wanderlust follows the MVC (Model-View-Controller) architecture.

- Model: Manages database schemas and data.
- View: Handles the user interface using EJS templates.
- Controller: Contains application logic.
- Routes: Handle incoming HTTP requests.
- Middleware: Handles authentication, authorization, validation, and error handling.

---

🎯 Project Goals

This project is part of my journey in learning full-stack web development.

Through Wanderlust, I aim to strengthen my understanding of:

- Backend development with Node.js and Express.js.
- Database management using MongoDB.
- Authentication and authorization.
- RESTful routing and MVC architecture.
- Third-party services and cloud integration.
- Building practical, real-world web applications.

---

👨‍💻 Author

Sahil Choudhary

🎓 B.Tech IT Student | Full-Stack Web Development Enthusiast

🔗 GitHub: "Visit My GitHub Profile" (https://github.com/SahilChoudhary1397)

---

⭐ Show Your Support

If you find this project interesting, consider giving it a ⭐ on GitHub!

Thanks for visiting Wanderlust! ❤️

Happy Coding! 🚀

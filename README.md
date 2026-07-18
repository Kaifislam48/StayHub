# 🏡 StayHub – Enterprise-Grade Travel Accommodation Platform

StayHub is a production-ready full-stack accommodation marketplace that enables users to discover, create, and manage travel property listings through a secure and intuitive web experience.

The platform integrates authentication, cloud-based image management, geolocation services, interactive maps, and role-based authorization to deliver a scalable real-world CRUD application. Built using modern JavaScript technologies and the MVC architectural pattern, StayHub demonstrates industry-standard backend engineering, maintainable code organization, and responsive user interface design.

---

# 🚀 Core Features

- 🔐 Secure User Authentication (Register, Login & Logout)
- 🏡 Create, Update & Delete Property Listings
- 🖼️ Cloud-based Image Upload & Management (Cloudinary)
- ⭐ Review & Rating System
- 🛡️ Role-Based Authorization & Route Protection
- 🗺️ Interactive Maps with Geolocation Support
- 💬 Flash Messaging & Centralized Error Handling
- 📱 Fully Responsive User Interface
- 📂 MVC-Based Project Architecture

---

# 🛠️ Technology Stack

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- Passport.js Authentication
- Express Session
- Connect Flash

## Frontend

- EJS (Server-Side Rendering)
- Bootstrap 5
- HTML5
- CSS3
- JavaScript (ES6)

## Integrations & Services

- Cloudinary (Image Storage)
- Multer (File Uploads)
- Leaflet.js
- OpenStreetMap Geocoding
- Express Validator

---

# 📁 Project Architecture

```
StayHub
│
├── controllers/      Business Logic
├── models/           Database Models
├── routes/           Application Routes
├── views/            EJS Templates
├── public/           CSS, JavaScript & Assets
├── utils/            Utility Functions
├── middleware.js     Custom Middleware
├── app.js            Application Entry Point
└── package.json
```

The application follows the **Model–View–Controller (MVC)** architecture, ensuring clean separation of concerns, scalability, and maintainability.

---

# 🔐 Authentication & Authorization

StayHub implements secure authentication and authorization using Passport.js.

### Authentication

- User Registration
- Secure Login
- Session-Based Authentication
- Logout

### Authorization

- Only authenticated users can create listings.
- Only listing owners can edit or delete their listings.
- Reviews are linked to registered users.
- Protected routes are secured through custom middleware.

---

# 🗺️ Maps & Location Services

StayHub integrates **OpenStreetMap** and **Leaflet.js** to provide an interactive location experience.

Features include:

- Automatic Geocoding
- Interactive Map Rendering
- Dynamic Location Markers
- Property Location Visualization

---

# ⚙️ Local Installation

## 1. Clone Repository

```bash
git clone https://github.com/Kaifislam48/StayHub.git

cd StayHub
```

## 2. Install Dependencies

```bash
npm install
```

## 3. Configure Environment Variables

Create a `.env` file inside the project root.

```env
MONGO_URL=your_mongodb_connection_string

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

SESSION_SECRET=your_session_secret
```

## 4. Start the Development Server

```bash
node app.js
```

or

```bash
nodemon app.js
```

## 5. Open in Browser

```
http://localhost:3000
```

---

# 🚀 Future Enhancements

- 📅 Property Booking System
- 💳 Secure Online Payments
- ❤️ Wishlist & Favorites
- 🔍 Advanced Search & Filtering
- 📊 Admin Dashboard
- 📧 Email Notifications
- 🤖 AI-Powered Property Recommendations
- 🐳 Docker & Containerization
- ☁️ Cloud Deployment
- 📈 Analytics Dashboard
- 🔔 Real-Time Notifications

---

# 👨‍💻 Developer

**Kaif Islam**

Software Engineer

- GitHub: https://github.com/Kaifislam48
- LinkedIn: https://www.linkedin.com/in/kaifislam49/

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

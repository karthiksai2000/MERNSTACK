<div align="center">
  <h1>🏥 Prescripto — Modern Hospital Management System</h1>
  <p>
    A comprehensive, full-stack hospital management solution for modern healthcare facilities.
    Streamline patient care, appointments, and administrative workflows with Prescripto.
  </p>
  
  <p>
    <a href="#tech-stack">
      <img src="https://img.shields.io/badge/Node.js-18.x-339933?logo=nodedotjs&logoColor=white" alt="Node.js" />
    </a>
    <a href="#tech-stack">
      <img src="https://img.shields.io/badge/React-18.x-61DAFB?logo=react&logoColor=white" alt="React" />
    </a>
    <a href="#tech-stack">
      <img src="https://img.shields.io/badge/MongoDB-5.0-47A248?logo=mongodb&logoColor=white" alt="MongoDB" />
    </a>
    <a href="#license">
      <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License" />
    </a>
    <a href="https://github.com/yourusername/Prescripto-Hospital_Management_System/stargazers">
      <img src="https://img.shields.io/github/stars/yourusername/Prescripto-Hospital_Management_System?style=social" alt="GitHub stars" />
    </a>
  </p>

  <p>
    <a href="#features">Features</a> •
    <a href="#screenshots">Screenshots</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#documentation">Documentation</a> •
    <a href="#contributing">Contributing</a>
  </p>
</div>

## ✨ Features

<div align="center">
  <table>
    <tr>
      <td width="50%">
        <h3>👥 User Management</h3>
        <ul>
          <li>🔐 Secure JWT Authentication & Authorization</li>
          <li>👨‍⚕️ Role-based Access Control (Admin, Doctor, Patient)</li>
          <li>📱 Responsive Design for all devices</li>
        </ul>
      </td>
      <td width="50%">
        <h3>🏥 Medical Features</h3>
        <ul>
          <li>📅 Appointment Scheduling System</li>
          <li>📋 Electronic Health Records (EHR)</li>
          <li>💊 Digital Prescription Management</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <h3>📊 Admin Dashboard</h3>
        <ul>
          <li>📊 Analytics & Reporting</li>
          <li>👥 Staff & User Management</li>
          <li>⚙️ System Configuration</li>
        </ul>
      </td>
      <td>
        <h3>🔧 Technical Features</h3>
        <ul>
          <li>📁 File/Image Uploads</li>
          <li>📱 Progressive Web App (PWA) Ready</li>
          <li>🔒 Secure API with Rate Limiting</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

## 🖼️ Screenshots

<div align="center">
  <img src="https://via.placeholder.com/400x250/4f46e5/ffffff?text=Dashboard+Preview" alt="Dashboard Preview" width="30%" />
  <img src="https://via.placeholder.com/400x250/10b981/ffffff?text=Appointments" alt="Appointments" width="30%" />
  <img src="https://via.placeholder.com/400x250/f59e0b/ffffff?text=Patient+Records" alt="Patient Records" width="30%" />
</div>

## 🚀 Tech Stack

### Frontend
- **React 18** - Frontend library
- **Vite** - Next Generation Frontend Tooling
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Axios** - HTTP client
- **React Toastify** - Notifications

### Backend
- **Node.js** - JavaScript runtime
- **Express** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - JSON Web Tokens for authentication
- **Multer** - File uploads
- **Razorpay** - Payment integration
- **Stripe** - Payment processing

### Development Tools
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Nodemon** - Development server

## 🛠️ Prerequisites

- Node.js 16+ & npm/yarn
- MongoDB (local or Atlas)
- Git

## 🚀 Quick Start

### Backend Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/Prescripto-Hospital_Management_System.git
cd Prescripto-Hospital_Management_System/backend

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Start the development server
npm run server
```

### Frontend Setup

```bash
# Navigate to frontend directory
cd ../frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

Visit `http://localhost:5173` in your browser.

## 🔧 Environment Variables

### Backend (`.env`)
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=30d
NODE_ENV=development
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
STRIPE_SECRET_KEY=your_stripe_secret
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
```

## 📂 Project Structure

```
Prescripto-Hospital_Management_System/
├── backend/                 # Backend server
│   ├── config/             # Configuration files
│   ├── controllers/        # Route controllers
│   ├── middleware/         # Custom middleware
│   ├── models/             # Database models
│   ├── routes/             # API routes
│   ├── utils/              # Utility functions
│   ├── .env.example        # Environment variables example
│   └── server.js           # Main server file
│
├── frontend/               # Frontend React app
│   ├── public/             # Static files
│   └── src/
│       ├── assets/         # Images, fonts, etc.
│       ├── components/     # Reusable components
│       ├── context/        # React context
│       ├── pages/          # Page components
│       ├── App.jsx         # Main app component
│       └── main.jsx        # Entry point
│
├── .gitignore
└── README.md
```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- [React](https://reactjs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)

## 📧 Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - your.email@example.com

Project Link: [https://github.com/yourusername/Prescripto-Hospital_Management_System](https://github.com/yourusername/Prescripto-Hospital_Management_System)

## ⭐ Show your support

Give a ⭐️ if this project helped you!

## Prerequisites

- Node.js (v16+ recommended)
- npm (or yarn)
- MongoDB (Atlas connection string or local server)

## Installation

Clone the repository and install dependencies for both backend and frontend.

```powershell
# clone and open repo
git clone <repository-url>
cd Prescripto-Hospital_Management_System-main

# backend
cd backend
npm install

# in a new terminal: frontend
cd ..\frontend
npm install
```

If this project includes additional apps (e.g., `admin/`), install those the same way.

## Environment variables

Create a `.env` file in the `backend` directory (and any other service that requires runtime config). Do not copy secrets into source control. Example `.env.example` (don't include real values):

```env
MONGODB_URI=YOUR_MONGODB_CONNECTION_STRING
JWT_SECRET=YOUR_JWT_SECRET
PORT=4000
ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=ChangeMeToAStrongPassword
```

Replace placeholders with your own values. The repository you cloned may already contain a `.env` locally — verify and remove any secrets before pushing.

## Running the app (development)

Start the backend and frontend in separate terminals.

Backend (PowerShell):

```powershell
cd backend
# preferred: a dev script (nodemon)
npm run dev
# or fallback
node server.js
```

Frontend (PowerShell):

```powershell
cd frontend
npm run dev
# or npm start depending on package.json
```

Open the URL printed by the frontend dev server (Vite typically uses http://localhost:5173 or increments the port if the default is in use).

If you encounter a blank page:

- Open the browser devtools console and check for runtime errors.
- Check the Network tab for failed asset requests or 404s.
- Confirm the frontend dev server is running and serving `index.html`.
- Confirm backend API endpoints are reachable (try `GET /api/health` or similar).
- If Tailwind utilities or `@apply` cause build errors, ensure `postcss.config.js` includes `tailwindcss` + `autoprefixer` and that `tailwind.config.js` `content` globs include `frontend/src`.

## Build / Production

To build frontend and run backend in production:

```powershell
# frontend build
cd frontend
npm run build

# backend: set NODE_ENV=production and run your start command
cd ..\backend
# set env vars in your host and run
node server.js
```

Deployment platforms can include Render, Heroku, Vercel (frontend), or container-based deployments.

## API and routes

Look in `backend/routes/` and `backend/controllers/` to inspect available endpoints. Typical routes:

- `POST /api/auth/login` — login and obtain JWT
- `POST /api/auth/register` — create account (if enabled)
- `GET /api/users` — list users (admin)
- `POST /api/appointments` — create appointment
- `GET /api/appointments` — list appointments
- `POST /api/prescriptions` — create prescription

Use tools like Postman or curl to exercise the API while developing.

## Seeding an admin user

If the project automatically seeds an admin account, it may use `ADMIN_EMAIL` and `ADMIN_PASSWORD` environment variables. If no seeder exists, create a small script that uses the backend `User` model to insert an admin record.

## Development tips

- Keep `.env` out of the repo and use `.env.example` for documentation.
- If using Tailwind, ensure `tailwind.config.js` `content` includes all templates so utilities are generated.
- Use `nodemon` for backend hot reload.
- Check browser console for the easiest clues when the UI is blank.

## Contributing

Contributions are welcome. Typical flow:

1. Fork the repository
2. Create a topic branch: `git checkout -b feat/your-feature`
3. Commit changes and open a Pull Request

Please include tests where appropriate and follow existing coding style.

## Security

- Do not commit `.env` or any secrets. Add `.env` to `.gitignore`.
- Rotate any credentials leaked accidentally.
- Use strong `JWT_SECRET` and secure password policies.

## License

Add a license file (`LICENSE`) and state the license here (e.g., MIT).

---

If you want, I can also:

- Create a `.env.example` file and add `.env` to `.gitignore`.
- Add a minimal `postcss.config.js` and `tailwind.config.js` in `frontend` if Tailwind is used but missing.
- Run the dev server and capture errors (I can help fix blank-page issues live).

Tell me which follow-up you'd like.

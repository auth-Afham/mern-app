# MERN App

## Project Structure

```
mern-app/
├── backend/
│   ├── src/
│   │   ├── models/
│   │   │   ├── User.js
│   │   ├── routes/
│   │   │   ├── auth.js
│   │   ├── server.js
│   ├── .env
│   ├── .gitignore
│   ├── package.json
│
├── frontend/
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   ├── robots.txt
│   ├── src/
│   │   ├── components/
│   │   │   ├── Home.js
│   │   │   ├── Login.js
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── App.test.js
│   │   ├── index.css
│   │   ├── index.js
│   │   ├── logo.svg
│   │   ├── reportWebVitals.js
│   │   ├── setupTests.js
│   ├── .gitignore
│   ├── package.json
│   ├── README.md
│   ├── tailwind.config.js
│
├── README.md
```

## Overview
This is a **MERN (MongoDB, Express.js, React, Node.js)** application with a structured backend and frontend.

### Backend
- **Server:** `server.js` (Entry point)
- **Models:** Contains database models (e.g., `User.js`)
- **Routes:** API endpoints (e.g., `auth.js`)
- **Environment Variables:** Stored in `.env`
- **Dependencies:** Managed via `package.json`

### Frontend
- **Components:** Reusable React components (e.g., `Home.js`, `Login.js`)
- **Styling:** TailwindCSS configuration (`tailwind.config.js`)
- **Assets:** Static files in `public/`
- **Dependencies:** Managed via `package.json`

## Getting Started

### Backend Setup
```sh
cd backend
npm install
npm start
```

### Frontend Setup
```sh
cd frontend
npm install
npm start
```

## Contributing
Feel free to fork the repository and submit pull requests.

## License
MIT License


# QR Menu App (MERN Starter Template)

A modern, modular, and extensible QR-code accessible restaurant menu application built with the MERN stack (MongoDB, Express, React, Node.js).

## Features
- Customer-facing digital menu (mobile-first, responsive)
- Admin CRUD for menu items (add, edit, delete, list)
- JWT-based authentication for admin
- Modular code structure for easy extension
- Ready for theme and multi-language support
- Starter template: only core features, no extra bloat

## Project Structure
```
menu-app/
├── client/   # React frontend (Vite, Tailwind CSS)
├── server/   # Node.js backend (Express, MongoDB)
├── .env.example
├── .gitignore
├── LICENSE
└── README.md
```

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/qr-menu-app-mern-stack.git
cd qr-menu-app-mern-stack/menu-app
```

### 2. Install dependencies
```bash
cd client && npm install
cd ../server && npm install
```

### 3. Environment Variables
- Copy `.env.example` to `.env` in both `client` and `server` folders and fill in the required values.

### 4. Run the app
- In two terminals:
```bash
cd client && npm run dev
cd ../server && npm run dev
```

## License
MIT

---


## Contributing
See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on how to contribute.

## Screenshot
You can add a screenshot of the app here (e.g., `client/public/screenshot.png`).

---

> This project is a clean starter template. For feature requests, open an issue or fork the repo!

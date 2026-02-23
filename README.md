# Car Parking Alert System

## 🛑 Project Objective & Motivation
Modern urban environments face significant challenges with vehicle parking, including unauthorized parking, inefficient space usage, and lack of timely notifications for both drivers and administrators. These issues can lead to congestion, frustration, and even security concerns.

**Why is this needed?**

- Unauthorized or improper parking causes inconvenience and can block emergency access.
- Manual monitoring is inefficient and error-prone.
- Drivers often miss important alerts about their vehicles.

**What does this project do?**

The Car Parking Alert System provides a comprehensive, automated solution for monitoring parking areas, detecting violations, and notifying users in real time. It integrates:
- A desktop application for administrators (Electron)
- High-performance backend logic (C++ with CMake)
- A modern, user-friendly web interface (Vite + React/TypeScript)
- Dockerized deployment for easy setup and scaling

**Problem & Solution**

- **Problem:** Inefficient parking management, lack of real-time alerts, and manual record-keeping.
- **Solution:** Automated detection, instant notifications (SMS, app, or display), and a unified dashboard for monitoring and reporting.

---

## 🚗 Overview

This project provides a complete car parking alert system built with:
- **Electron**: Cross-platform desktop application framework
- **C++**: Core system components (CMake build system)
- **Frontend**: Modern web-based UI (Vite + React/TypeScript)
- **Docker**: Containerized deployment and development

## ✨ Features

- Desktop app for parking management and alerts
- Cross-platform (Windows, macOS, Linux)
- Docker containerization
- Integrated C++ backend with CMake
- Modern web frontend

## 📦 Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [CMake](https://cmake.org/) (for C++ components)
- [Visual Studio](https://visualstudio.microsoft.com/) or compatible C++ compiler (Windows)
- [Docker](https://www.docker.com/) (optional)

## 🔧 Installation

1. **Clone the repository:**
	```bash
	git clone https://github.com/yourusername/car-parking-alert-system.git
	cd car-parking-alert-system
	```

2. **Install Node.js dependencies:**
	```bash
	npm install
	```

3. **Set up environment variables (if needed):**
	```bash
	cp car-chime-system-main/.env.example car-chime-system-main/.env
	# Edit .env as required
	```

---

## 🏗️ Build Instructions

### C++ Components

**Windows:**
```bash
./build_release.bat
```

**CMake (all platforms):**
```bash
cmake --preset=default
cmake --build build --config Release
```

### Electron App

```bash
npm run build
```

### Frontend (if using standalone frontend/):

```bash
cd frontend
npm install
npm run build
```

---

## 🚀 Run Instructions

### Development Mode
```bash
npm start
```

### Production Mode
```bash
npm run start:prod
```

See [For_run_the_code](For_run_the_code) for additional details.

---

## 🐳 Docker Usage

### Compose (Production)
```bash
docker-compose -f compose.yaml up
```

### Compose (Debug)
```bash
docker-compose -f compose.debug.yaml up
```

### Build Docker Image
```bash
docker build -t car-parking-alert-system .
```

---

## 📁 Project Structure

```
├── src/                    # C++ source code
│   ├── api/                # HTTP server implementation
│   ├── database/           # Database manager
│   ├── services/           # Backend services
│   ├── ui/                 # UI logic
│   └── main.cpp            # Entry point
├── include/                # C++ header files
│   ├── api/                # HTTP server headers
│   ├── database/           # DB manager headers
│   ├── dsa/                # Data structures
│   ├── models/             # Data models
│   ├── services/           # Service headers
│   └── ui/                 # UI headers
├── frontend/               # Web frontend (Vite + React)
│   ├── src/                # Frontend source
│   ├── public/             # Static assets
│   └── vite.config.ts      # Vite config
├── car-chime-system-main/  # Main module (Node.js/Electron)
├── dist-electron/          # Electron build output
├── build/                  # CMake build output
├── scripts/                # Utility scripts
├── sql/                    # Database schema
├── docs/                   # Documentation
├── logo/                   # Logo assets
├── video/                  # Video resources
├── main.js                 # Electron main process
├── preload.js              # Electron preload script
├── CMakeLists.txt          # CMake config
├── Dockerfile              # Docker config
├── compose.yaml            # Docker Compose config
├── package.json            # Node.js dependencies
├── README.md               # Project documentation
└── LICENSE.txt             # License
```

---

## 📖 Documentation

- [Setup Guide](SETUP_GUIDE.md) - Detailed setup instructions
- [TODO](TODO.md) - Planned features and improvements

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the terms specified in [LICENSE.txt](LICENSE.txt).

---

⭐ If you find this project useful, please consider giving it a star!
Car Parking Alert System
🛑 Project Objective & Motivation
Modern urban environments face significant challenges with vehicle parking, including unauthorized parking, inefficient space usage, and lack of timely notifications for both drivers and administrators. These issues can lead to congestion, frustration, and even security concerns.

Why is this needed?

Unauthorized or improper parking causes inconvenience and can block emergency access.
Manual monitoring is inefficient and error-prone.
Drivers often miss important alerts about their vehicles.
What does this project do?

The Car Parking Alert System provides a comprehensive, automated solution for monitoring parking areas, detecting violations, and notifying users in real time. It integrates:

A desktop application for administrators (Electron)
High-performance backend logic (C++ with CMake)
A modern, user-friendly web interface (Vite + React/TypeScript)
Dockerized deployment for easy setup and scaling
Problem & Solution

Problem: Inefficient parking management, lack of real-time alerts, and manual record-keeping.
Solution: Automated detection, instant notifications (SMS, app, or display), and a unified dashboard for monitoring and reporting.
🚗 Overview
This project provides a complete car parking alert system built with:

Electron: Cross-platform desktop application framework
C++: Core system components (CMake build system)
Frontend: Modern web-based UI (Vite + React/TypeScript)
Docker: Containerized deployment and development
✨ Features
Desktop app for parking management and alerts
Cross-platform (Windows, macOS, Linux)
Docker containerization
Integrated C++ backend with CMake
Modern web frontend
📦 Prerequisites
Node.js (v16+ recommended)
npm or yarn
CMake (for C++ components)
Visual Studio or compatible C++ compiler (Windows)
Docker (optional)
🔧 Installation
Clone the repository:


git clone https://github.com/yourusername/car-parking-alert-system.gitcd car-parking-alert-system
Install Node.js dependencies:


npm install
Set up environment variables (if needed):


cp car-chime-system-main/.env.example car-chime-system-main/.env# Edit .env as required
🏗️ Build Instructions
C++ Components
Windows:


./build_release.bat
CMake (all platforms):


cmake --preset=defaultcmake --build build --config Release
Electron App

npm run build
Frontend (if using standalone frontend/):

cd frontendnpm installnpm run build
🚀 Run Instructions
Development Mode

npm start
Production Mode

npm run start:prod
See For_run_the_code for additional details.

🐳 Docker Usage
Compose (Production)

docker-compose -f compose.yaml up
Compose (Debug)

docker-compose -f compose.debug.yaml up
Build Docker Image

docker build -t car-parking-alert-system .
📁 Project Structure

├── src/                    # C++ source code│   ├── api/                # HTTP server implementation│   ├── database/           # Database manager│   ├── services/           # Backend services│   ├── ui/                 # UI logic│   └── main.cpp            # Entry point├── include/                # C++ header files│   ├── api/                # HTTP server headers│   ├── database/           # DB manager headers│   ├── dsa/                # Data structures│   ├── models/             # Data models│   ├── services/           # Service headers│   └── ui/                 # UI headers├── frontend/               # Web frontend (Vite + React)│   ├── src/                # Frontend source│   ├── public/             # Static assets│   └── vite.config.ts      # Vite config├── car-chime-system-main/  # Main module (Node.js/Electron)├── dist-electron/          # Electron build output├── build/                  # CMake build output├── scripts/                # Utility scripts├── sql/                    # Database schema├── docs/                   # Documentation├── logo/                   # Logo assets├── video/                  # Video resources├── main.js                 # Electron main process├── preload.js              # Electron preload script├── CMakeLists.txt          # CMake config├── Dockerfile              # Docker config├── compose.yaml            # Docker Compose config├── package.json            # Node.js dependencies├── README.md               # Project documentation└── LICENSE.txt             # License
📖 Documentation
Setup Guide - Detailed setup instructions
TODO - Planned features and improvements
🤝 Contributing
Fork the repository
Create a feature branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -m 'Add YourFeature')
Push to your branch (git push origin feature/YourFeature)
Open a Pull Request
📄 License
This project is licensed under the terms specified in LICENSE.txt.

⭐ If you find this project useful, please consider giving it a star!

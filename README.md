<div align="center">

  # 🚀 SubPilot

  **A modern, full-stack web application built with TypeScript, React, Vite, and Firebase.**

  [![Live Demo](https://img.shields.io/badge/Demo-Live%20App-brightgreen?style=for-the-badge&logo=render)](https://subpilot-6izb.onrender.com)
  [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
  [![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)

  ---

  ### 🔗 [View Live Application](https://subpilot-6izb.onrender.com)

</div>

---

## 📌 About The Project

**SubPilot** is a production-grade full-stack web application engineered with type safety at its core. By leveraging **TypeScript** across both frontend and backend environments, it ensures high maintainability, robust code execution, and a seamless developer experience.

The application combines the lightning-fast build performance of **Vite** and **Esbuild** with the real-time cloud infrastructure provided by **Firebase**.

---

## 🛠️ Tech Stack & Architecture

### **Frontend**
* **Language:** TypeScript
* **Framework / Library:** React
* **Build Tool:** Vite (Optimized production bundling & instant HMR)

### **Backend**
* **Runtime:** Node.js
* **Framework:** Express.js
* **Bundler:** Esbuild (Ultra-fast server bundling)

### **Database & Authentication**
* **Authentication:** Firebase Auth
* **Database / Cloud:** Firestore / Firebase Services

### **Deployment & Hosting**
* **Platform:** Render (Automated CI/CD from Git `main` branch)

---

## ✨ Key Features

- ⚡ **End-to-End Type Safety:** Strict TypeScript interfaces across UI components and API controllers.
- 🔐 **Firebase Authentication:** Secure user identity management and session handling.
- 🔥 **Firestore Integration:** Real-time data synchronization with flexible cloud storage.
- 🚀 **Optimized Production Build:** Fast bundle generation using `vite build` for client side and `esbuild` for Node backend execution.
- ☁️ **Cloud Deployed:** Continuous deployment configured on Render platform.

---

## 📂 Project Directory Structure

```text
SubPilot/
├── src/
│   ├── assets/                # Static assets (images, icons)
│   ├── components/            # Reusable UI components
│   ├── lib/                   # Firebase initialization & helper utility modules
│   │   └── firebase.ts        # Firebase app configuration & SDK setup
│   ├── App.tsx                # Main Application Component
│   └── main.tsx               # Client entry point
├── server.ts                  # Express backend entry point
├── firebase-applet-config.json# Firebase configuration file
├── vite.config.ts             # Vite build & plugin configuration
├── package.json               # Scripts & dependencies
└── README.md                  # Project documentation

⚙️ Local Development Setup
Follow these steps to run the project locally on your machine:

Prerequisites
Make sure you have Node.js (v18 or higher) and npm installed.

1. Clone the Repository
Bash
git clone [https://github.com/addy-pandey2025/SubPilot.git](https://github.com/addy-pandey2025/SubPilot.git)
cd SubPilot

2. Install Dependencies
Bash
npm install
3. Environment Setup
Create a .env file in the root directory (if using environment variables) and populate it with your Firebase configuration values.

4. Start Development Server
Runs the Vite development server with Hot Module Replacement (HMR):

Bash
npm run dev
📦 Production Build & Execution
To bundle both the React client and TypeScript backend server for production deployment:

Bash
# Build client assets and compile backend server code
npm run build

# Start production server
npm start
👤 Author
Developed with ❤️ by Addy Pandey

GitHub: @addy-pandey2025

Project Repo: SubPilot

# 3D Customizer Web App

A full-stack 3D customization application that allows users to personalize virtual items using real-time rendering and AI-generated content. Built using React.js, Three.js, Node.js, and the OpenAI API.

---

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Contributing](#contributing)
8. [License](#license)
9. [Author](#author)

---

## 🤖 Introduction

This repository hosts a complete full-stack solution for designing 3D virtual items. The frontend provides a responsive, interactive UI for customizing models, while the backend handles AI-driven content generation via OpenAI. Users can adjust colors, upload images, or generate textures/logos using AI prompts.

---

## ⚙️ Tech Stack

* **Frontend:** React.js, Vite, Three.js, React Three Fiber, React Drei
* **Styling:** Tailwind CSS
* **State Management & Animations:** Valtio, Framer Motion
* **Backend:** Node.js, Express.js
* **AI Integration:** OpenAI API

---

## 🔋 Features

* Interactive 3D model customization in the browser
* Color selection and live updates
* Upload your own logos or textures
* AI-generated assets from custom prompts
* Download final design as an image
* Fully responsive and animated UI

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/MeghanshGovil/project_threejs_ai.git
cd project_threejs_ai
```

### 2. Install dependencies

#### Client

```bash
cd client
npm install
```

#### Server

```bash
cd ../server
npm install
```

### 3. Configure environment variables

Create a `.env` file inside the `server` directory:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the applications

#### Start the server

```bash
cd server
npm start
```

#### Start the client

```bash
cd ../client
npm run dev
```

Visit `http://localhost:5173` in your browser.

---

## 🎯 Usage

1. Choose a color to apply to the model.
2. Upload your own logo or texture image.
3. Enter a prompt to generate a logo or texture using AI.
4. Download the final design.

---

## ⚙️ Configuration

* **Frontend:** Modify assets in `client/public/models`
* **Backend:** All AI interaction settings are handled through `server/index.js`
* **API Key:** Set `OPENAI_API_KEY` in the server's `.env` file

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch
3. Commit your changes
4. Push and open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

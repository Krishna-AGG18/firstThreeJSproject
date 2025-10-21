# 🧠 AI-Powered 3D T-Shirt Customizer

An interactive web application built with **React** and **Three.js**, enabling users to customize **3D t-shirt models in real-time**.
Users can **change colors**, **upload logos or textures**, **generate AI-powered designs using DALL·E**, and **download their creations** — all from the browser.

This project was built by following the [JavaScript Mastery](https://www.youtube.com/watch?v=ZqEa8fTxypQ) tutorial **“Build and Deploy an AI-Powered 3D Website Using React | 2024 Three JS Course Tutorial for Beginners”**, with personalized modifications and enhancements.

![Project Demo](https://via.placeholder.com/800x400?text=3D+T-Shirt+Customizer+Demo)

---

## 🧩 Overview

This project demonstrates **3D graphics integration in React** using **React Three Fiber** and **Three.js**.
It offers a hands-on experience with **3D rendering**, **AI integration**, **state management**, and **smooth animations** — perfect for learners exploring interactive web development.

---

## 🚀 Features

* 🎨 **3D Model Customization** – Load, rotate, and modify a GLTF t-shirt model in real time.
* 🌈 **Color Picker** – Choose or input any custom color to update the model’s appearance instantly.
* 🖼️ **File Upload** – Upload logos or patterns to apply as decals.
* 🤖 **AI Image Generation** – Generate unique designs using **OpenAI’s DALL·E** based on text prompts.
* 🧩 **Toggle Controls** – Enable/disable logo and full texture independently.
* 📸 **Download Functionality** – Capture and download the customized 3D t-shirt image.
* ⚡ **Smooth Animations** – Framer Motion adds fluid transitions and engaging motion effects.
* 📱 **Fully Responsive** – Built with Tailwind CSS for an optimized experience on all devices.

---

## 🛠️ Tech Stack

**Frontend**

* React (Vite)
* Three.js
* @react-three/fiber
* @react-three/drei
* Tailwind CSS
* Framer Motion

**AI Integration**

* OpenAI DALL·E API (via @google/generative-ai)

**State Management**

* Voltio (lightweight proxy-based state manager)

**Utilities**

* Maath (math helpers)
* react-colorful (color picker UI)

**Deployment**

* Hostinger / Vercel / Netlify

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-3d-tshirt-customizer.git
cd ai-3d-tshirt-customizer
```

### 2. Install dependencies

```bash
npm install
```

### 3. (Optional) Setup Backend for AI

If you want to use AI-generated designs:

* Create a `.env` file in the root directory.
* Add your OpenAI API key:

  ```
  OPENAI_API_KEY=your_openai_api_key
  ```

### 4. Download Assets

Download the 3D model and texture files from the tutorial’s Google Drive (linked in the video description).
Place them in:

```
public/
src/assets/
```

### 5. Run the project

```bash
npm run dev
```

Then open: **[http://localhost:5173](http://localhost:5173)**

---

## 🧠 Usage Guide

1. **Homepage** – Overview of the app with an option to start customizing.
2. **Customizer Interface** –

   * Select colors or upload your own logo.
   * Use AI prompt to generate a design.
   * Toggle logo/full texture.
3. **Download** – Click the camera icon to export your customized shirt as an image.
4. **Navigation** – Use the "Go Back" button to return to the homepage.

---

## 🌍 Deployment

To build and deploy the app:

### Build for production

```bash
npm run build
```

### Deploy Options

* **Hostinger** (recommended in tutorial): Upload the `dist/` folder via File Manager.
* **Vercel / Netlify**: Connect your repo and use build command:

  ```
  npm run build
  ```

---

## 🧰 Common Issues

**Problem:** `failed to load resource` for drei or fiber
**Fix:**

```bash
npm update @react-three/drei @react-three/fiber
```

Refer to this fix: [JavaScript Mastery Pull Request #45](https://github.com/adrianhajdin/project_threejs_ai/pull/45)

---

## 💡 Learning Outcomes

Through this project, I learned:

* How to integrate **Three.js** with **React** using **React Three Fiber**.
* How to manage app-wide state using **Voltio**.
* The basics of **AI-powered image generation** and handling **OpenAI APIs**.
* Implementing **3D rendering, animations, and performance optimization** in React.

---


Would you like me to make it **more personalized** (for example, mentioning your learning journey like *“Built as part of my React + Three.js learning phase to explore 3D web development and AI integration”*)?
I can tailor the intro and ending sections that way for your GitHub.

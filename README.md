# 🧠 AI-Powered 3D T-Shirt Customizer

An interactive web application built with **React** and **Three.js**, enabling users to customize **3D t-shirt models in real time**.
Users can **change colors**, **upload logos or textures**, **generate AI-powered designs**, and **download their creations** — all from the browser.

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
* 🤖 **AI Image Generation** – Generate unique designs using text prompts.
* 🧩 **Toggle Controls** – Enable or disable logo and full texture independently.
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

* OpenAI DALL·E API (or any AI image API)

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
* Add your API key:

  ```
  OPENAI_API_KEY=your_api_key
  ```

### 4. Download Assets

Place your 3D model and texture files in:

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
   * Use an AI prompt to generate a design.
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

* **Hostinger** – Upload the `dist/` folder via File Manager.
* **Vercel / Netlify** – Connect your repo and use the build command:

  ```bash
  npm run build
  ```

---

## 🧰 Common Issues

**Problem:** `failed to load resource` for drei or fiber
**Fix:**

```bash
npm update @react-three/drei @react-three/fiber
```

---

## 💡 Learning Outcomes

Through this project, I learned:

* How to integrate **Three.js** with **React** using **React Three Fiber**.
* How to manage app-wide state using **Voltio**.
* The basics of **AI-powered image generation** and handling APIs.
* Implementing **3D rendering, animations, and performance optimization** in React.

---

## 📜 License

This project is open-source under the **MIT License** — feel free to use, modify, and share.

---

Would you like me to **personalize it further** (for example, mentioning that you built it while learning React and Three.js or experimenting with AI features)?

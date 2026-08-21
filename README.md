# 🌐 3D Portfolio

An interactive, futuristic **3D personal portfolio website** designed to showcase my journey from a Computer Science Engineering student to a **DevOps Engineer / Platform SRE**.

The website is built as an immersive, scroll-driven experience where users can explore my career journey, projects, technical skills, DevOps ecosystem, achievements, and personal interests through interactive 3D environments and animations.

> **From Code to Cloud.**

---

## 📌 Overview

The goal of this project is to create a portfolio that goes beyond a traditional website.

Instead of presenting information through standard static sections and cards, the portfolio uses:

* 3D environments
* Scroll-driven storytelling
* Interactive animations
* Camera movement
* Parallax effects
* Particle effects
* Dynamic lighting
* Technology visualizations

The complete experience is designed around a single story:

```text
Computer Science Student
        ↓
Developer
        ↓
Backend Engineer
        ↓
DevOps Engineer
        ↓
Platform SRE
```

---

## ✨ Features

### 🎭 Interactive 3D Experience

* Interactive 3D avatar
* Cinematic hero scene
* Scroll-based camera movement
* Natural cursor interaction
* Dynamic lighting
* Particle effects
* Depth and parallax effects
* Smooth scene transitions

### 📜 Scroll-Driven Storytelling

The website uses scrolling as the primary interaction mechanism.

As the user scrolls, the environment and camera progressively transition through different stages of the portfolio.

```text
Hero
  ↓
Journey
  ↓
Engineering Evolution
  ↓
Projects
  ↓
DevOps / Platform SRE
  ↓
Skills
  ↓
Personal Side
  ↓
Achievements
  ↓
Contact
```

### ☁️ DevOps Infrastructure Visualization

A dedicated 3D environment represents the DevOps and Platform SRE ecosystem.

Technologies are visualized as connected infrastructure components rather than a simple list of skills.

```text
Code
  ↓
Git
  ↓
CI/CD
  ↓
Docker
  ↓
Kubernetes
  ↓
Cloud
  ↓
Monitoring
  ↓
Production
```

### 📱 Responsive Design

The portfolio supports:

* Desktop
* Laptop
* Tablet
* Mobile

The 3D experience is optimized and simplified on smaller devices where necessary while maintaining the overall storytelling experience.

---

# 🧭 Portfolio Sections

## 1. Hero

The portfolio begins with a cinematic 3D environment containing:

* 3D avatar
* Name
* Current role
* "From Code to Cloud."

The avatar reacts naturally to user interaction and gradually moves away as the user progresses through the experience.

---

## 2. My Journey

An interactive timeline representing the transition from university to professional engineering.

```text
2021
Started B.Tech
    ↓
2021 – 2025
Computer Science Engineering
    ↓
2025
Graduated
    ↓
May 5, 2025
Joined Nisum
    ↓
2025 – Present
DevOps / Platform SRE Journey
```

---

## 3. Engineering Evolution

The portfolio visually represents the evolution of my engineering career:

```text
Student
   ↓
Developer
   ↓
Backend Engineer
   ↓
Cloud / DevOps
   ↓
Platform SRE
```

Each stage is represented through a different visual environment.

---

## 4. B.Tech Projects

### Generative AI Model

A Generative AI project created using Google Colab for text-to-image generation through model training and fine-tuning.

### Advanced Notepad

A Python Tkinter-based desktop application supporting:

* File creation
* File opening
* File saving
* Cut / Copy / Paste
* Font customization
* Text and background colors
* Multiple tabs
* Error handling
* Cross-platform support

### Blood Donor & Recipient Management System

A Spring Boot web application providing:

* Donor registration
* Recipient requests
* Blood inventory tracking
* Compatible donor search
* Authentication
* Role-based access
* Dashboard
* REST APIs

---

# ☁️ DevOps / Platform SRE

The DevOps section is one of the major visual environments of the portfolio.

It represents modern infrastructure and deployment workflows through connected 3D nodes and animated pipelines.

### Technologies Represented

* Git
* GitLab
* Docker
* Kubernetes
* Terraform
* Jenkins
* Google Cloud / GCP
* Argo CD
* Helm
* CI/CD
* Redis
* Akamai
* Dynatrace
* Consul
* Vault
* Linux
* Monitoring
* Logging
* Cloud Infrastructure

---

# 🛠️ Tech Stack

## Frontend

* React
* JavaScript
* HTML
* CSS

## 3D & WebGL

* Three.js
* React Three Fiber
* WebGL
* 3D Models
* Particle Systems
* Dynamic Lighting

## Animation

* GSAP
* ScrollTrigger
* Smooth Scrolling
* Parallax
* Camera Animations

## Development Tools

* Git
* GitLab
* npm
* VS Code

---

# 📂 Project Structure

```text
3d_portfolio/
│
├── public/
│   ├── models/
│   ├── textures/
│   └── assets/
│
├── src/
│   ├── components/
│   ├── scenes/
│   ├── sections/
│   ├── animations/
│   ├── styles/
│   └── App.jsx
│
├── package.json
├── vite.config.js
└── README.md
```

> The exact structure may vary depending on the implementation.

---

# 🚀 Getting Started

## Prerequisites

Make sure the following are installed:

* Node.js
* npm
* Git

Check the installed versions:

```bash
node --version
npm --version
git --version
```

---

## Clone the Repository

```bash
git clone <YOUR_GITLAB_REPOSITORY_URL>
```

Navigate to the project:

```bash
cd 3d_portfolio
```

---

## Install Dependencies

```bash
npm install
```

---

## Run the Development Server

```bash
npm run dev
```

The development server will provide a local URL that can be opened in a browser.

---

## Build for Production

```bash
npm run build
```

---

## Preview Production Build

```bash
npm run preview
```

---

# 🔐 Environment Variables

If environment variables are required, create a `.env` file in the project root.

Example:

```env
VITE_LINKEDIN_URL=
VITE_GITHUB_URL=
VITE_EMAIL=
```

Do not commit sensitive information such as:

* API keys
* Access tokens
* Passwords
* Cloud credentials
* Private keys

---

# ⚡ Performance

Performance is an important part of this project because of the use of 3D and WebGL.

The application is designed to:

* Optimize 3D assets
* Avoid unnecessary rendering
* Lazy-load heavy assets where appropriate
* Reduce expensive visual effects when necessary
* Maintain smooth scrolling
* Optimize the mobile experience
* Respect reduced-motion preferences

---

# 📱 Responsive Experience

### Desktop

The desktop experience provides the complete cinematic 3D experience with:

* Full 3D environments
* Camera movement
* Interactive elements
* WebGL effects
* Scroll-driven animations

### Mobile

The mobile experience reduces computationally expensive effects while preserving:

* Core content
* Career storytelling
* Navigation
* Animations
* Visual identity

---

# 🎨 Design Philosophy

The project follows a:

* Futuristic
* Minimal
* Professional
* Cinematic
* Dark
* Technology-focused

design approach.

The objective is to avoid a conventional portfolio template and instead create an interactive experience that feels like traveling through an engineering career.

---

# 🔮 Future Improvements

Potential future enhancements include:

* More advanced 3D environments
* Interactive Kubernetes architecture visualization
* Cloud infrastructure simulations
* Live GitHub project integration
* Live GitLab activity
* Advanced WebGL effects
* Additional performance optimizations
* Improved mobile 3D experience
* Automated CI/CD deployment
* Additional interactive DevOps visualizations

---

# 👨‍💻 Author

**Biswajit Mishra**

DevOps Engineer | Platform SRE

Nisum

> **From Code to Cloud.**

---

## 📄 License

This is a personal portfolio project created by **Biswajit Mishra**.

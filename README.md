# 👋 Hi, I'm Siddhant Gureja

**Full Stack Web Developer | MERN | Next.js | Three.js | C4GT 2025 Contributor**

---

## 🚀 About Me

- 🔭 Working on advanced **MERN stack** apps with real-world use cases  
- 🏛️ Contributor @ **C4GT 2025** – ADC Mahendragarh land demarcation system  
- 💼 Built **Incubator CRM** for Thapar Innovate to manage startup programs  
- 🌱 Learning **Next.js**, **Three.js**, **GSAP**, and deepening backend mastery  
- 🤝 Open to collaborations on impactful frontend/backend systems

---

## 🧠 Featured Projects

### 🔹 **C4GT 2025 – ADC Mahendragarh**
- Digitizing land demarcation disputes for Haryana govt.
- Tracks plot-wise activities for revenue officers
- Displays current/historic demarcation progress to reduce conflict

### 🔹 **Incubator CRM – Thapar Innovate**
- Platform to manage startups, cohorts, funding & mentorship
- Tracks team sizes, stage of growth, and program outcomes
- Context API used to handle 110+ APIs and reduce performance issues

### 🔹 **DevTinder**
- Tinder-like platform for developers to swipe, match & collaborate
- Tech: React, Firebase OTP, Node.js, MongoDB

### 🔹 **CodeFusion**
- Live coding + chat rooms with Judge0 API and Monaco Editor
- Tech: React, Express, JWT, Socket.IO

### 🔹 **ResumeForge**
- Sleek resume builder with PDF export and live preview
- Tech: React, Zustand, Tailwind, HTML2PDF

### 🔹 **TwitPilot**
- Twitter clone with login, feed, tweets, follow/unfollow
- Tech: MERN, Redux

### 🔹 **Priv-guard**
- Chrome extension to detect data leaks & block trackers
- Tech: Manifest V3, Chrome API

---

## ⚙️ Skills & Tools

### 💻 Languages & Frameworks
- JavaScript, React, Next.js, Node.js, Express

### 🗄️ Databases
- MongoDB, PostgreSQL

### 🎨 Design & Animation
- Figma, GSAP, Three.js

---

## ✨ Three.js Code Snippet

```js
import * as THREE from 'three';

const scene = new THREE.Scene();
const camera = new THREE.PerspectiveCamera(75, window.innerWidth/window.innerHeight, 0.1, 1000);
const renderer = new THREE.WebGLRenderer();

renderer.setSize(window.innerWidth, window.innerHeight);
document.body.appendChild(renderer.domElement);

const geometry = new THREE.BoxGeometry();
const material = new THREE.MeshStandardMaterial({ color: 0x00ff00 });
const cube = new THREE.Mesh(geometry, material);
scene.add(cube);

const light = new THREE.PointLight(0xffffff);
light.position.set(5, 5, 5);
scene.add(light);

camera.position.z = 5;

function animate() {
  requestAnimationFrame(animate);
  cube.rotation.x += 0.01;
  cube.rotation.y += 0.01;
  renderer.render(scene, camera);
}

animate();
```

📊 GitHub Stats



📚 LeetCode Highlights


🏆 Achievements
🥇 1st Place @ Hackmol 5.0, NIT Jalandhar

🥉 3rd Place @ CodeSprint, ACM TIET

🧠 Top 2% in LeetCode Weekly Contests

🎓 Merit I Scholar @ TIET (100% Fee Waiver ×2)

🔥 Open Source Contributor @ Hacktoberfest 2024



🌐 Connect With Me
LinkedIn

X / Twitter

Instagram

✍️ Quote
"The best way to predict the future is to invent it." – Alan Kay

🎯 Let’s Collaborate
Have an idea? Want to collaborate? Let's build something epic.
DM me on LinkedIn → linkedin.com/in/sidgureja

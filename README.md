<!-- Premium Developer Portfolio README for Sahitya Ghosh -->
<div align="center">

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212747657-7a8d59da-69c8-4110-8ea8-f8102fd0b413.gif" width="45%" alt="coding-animation" style="border-radius: 12px; margin: 5px; max-width: 320px;" />
  <img src="https://user-images.githubusercontent.com/74038190/219923809-b86dc415-a0c2-4a38-bc88-ad6cf06395a8.gif" width="45%" alt="developer-animation" style="border-radius: 12px; margin: 5px; max-width: 320px;" />
</p>

# Hi 👋, I'm Sahitya Ghosh
### **Full-Stack Engineer · GenAI Builder · Open Source Contributor**
*Crafting high-leverage intelligent systems at the intersection of LLMs, scalable backends, and modern frontend architecture.*

<br/>

<!-- Real-time typing animation summarizing key competencies -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=6366f1&center=true&vCenter=true&width=600&lines=React+%7C+Node.js+%7C+Next.js;AI%2FML+Practitioner+%7C+Python+Learner;Open-Source+Contributor+%7C+Tech+Writer;Turning+ideas+into+scalable+solutions;DSA+problem+solver+on+LeetCode_Platform" alt="Typing SVG" />

<br/>

<!-- Custom dynamic profile counters -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sahitya350&label=Profile+Views&color=8A2BE2&style=for-the-badge&labelColor=000000" alt="Profile Views" /> 
  <img src="https://img.shields.io/github/stars/sahitya350?color=FFD700&label=Stars&logo=github&style=for-the-badge&labelColor=000000" alt="GitHub Stars" />
  <img src="https://img.shields.io/github/followers/sahitya350?color=00FF7F&label=Followers&logo=github&style=for-the-badge&labelColor=000000" alt="GitHub Followers" />
</p>

</div>

---

## ⚡ DevPulse.AI — My Live Portfolio Analyzer

This workspace includes **DevPulse.AI** — a premium, client-side, real-time GitHub Profile Analyzer, Visualizer, and AI Career Auditor built with pure CSS & vanilla JS. It queries official REST APIs directly to perform interactive audits and compile statistical reports.

> [!TIP]
> 🔍 **Want to audit my profile in real-time?** Explore my live [DevPulse.AI Profile Dashboard](https://sahitya350.github.io/Githubreadme/) (or deploy it in one click!) to see live repository metrics, language allocations, and algorithmic career scores!

<details>
<summary><b>🛠️ Live GitHub REST API Query Example</b></summary>

Here is a functional, modern asynchronous implementation of how this dashboard queries live developer profiles from the GitHub REST API:

```javascript
// Dynamic Profile Fetching Controller
const fetchGitHubStats = async (username) => {
    try {
        const response = await fetch(`https://api.github.com/users/${username}`, {
            method: 'GET',
            headers: {
                'Content-Type': 'application/json',
                'Accept': 'application/vnd.github.v3+json'
            }
        });
        
        if (!response.ok) throw new Error(`User not found: ${response.status}`);
        
        const data = await response.json();
        console.log(`Successfully synced @${username}:`, {
            name: data.name,
            repos: data.public_repos,
            followers: data.followers
        });
        return data;
    } catch (error) {
        console.error("GitHub API Connection Error:", error);
    }
};

// Execute live sync
fetchGitHubStats('SAHITYA350');
```

</details>

---

## 👨‍💻 Executive Summary

I am a B.Tech CSE student at **NIT Bhubaneswar** focused on **GenAI application development** and **full-stack engineering**. I ship production-grade AI tools — from intelligent interview prep platforms to generative exam systems — using modern LLM APIs, MERN stack, and scalable cloud infrastructure.

*   **Actively Exploring**: RAG pipelines · LLM fine-tuning · Agentic workflows · Real-time AI systems
*   **Goal 2025**: Google Summer of Code (GSoC) · Open source AI developer tooling.

---

## 🚀 Professional Network & Connect

<div align="center">

| Platform | Address / Handle | Link Button |
| :--- | :--- | :--- |
| 💼 **LinkedIn** | `sahitya-ghosh-9ba098292` | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sahitya-ghosh-9ba098292) |
| 🐦 **Twitter / X** | `@sahityagbcx` | [![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/sahityagbcx) |
| 📝 **Dev.to Blog** | `sahitya_ghosh_350` | [![Dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=flat-square&logo=dev.to&logoColor=white)](https://dev.to/sahitya_ghosh_350) |
| 🏆 **LeetCode** | `balasur` | [![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=flat-square&logo=LeetCode&logoColor=black)](https://www.leetcode.com/balasur) |
| 🔶 **GeeksforGeeks** | `sahityagmkep` | [![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-298D46?style=flat-square&logo=geeksforgeeks&logoColor=white)](https://auth.geeksforgeeks.org/user/sahityagmkep) |
| 👥 **Facebook** | `devinwithsahitya` | [![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://fb.com/devinwithsahitya) |
| 📸 **Instagram** | `sahityaghosh_350` | [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/sahityaghosh_350) |

</div>

---

## 🤖 Featured Masterpieces

<div align="center">

| Project | Description | Core Stack | Live Demo / Repo |
| :--- | :--- | :--- | :--- |
| **🤖 SG Interview Prep AI** | AI-driven interview evaluation platform. Generates personalized role questions and grades answers in real-time. | `GenAI` `LLM APIs` `Next.js` `Node.js` `MongoDB` | [**Live Platform**](https://sginterviewprepai.onrender.com) |
| **📝 ExamCraft AI** | Intelligent exam generation system. Takes subject matter as input and auto-crafts calibrated sheets with explanations. | `GenAI` `Prompt Eng` `React` `Express.js` `MongoDB` | [**Live Platform**](https://examcraftai.onrender.com) |
| **✂️ Trimrrs** | Full-stack URL shortening service with custom alias support, clicks analytics, and secure JWT-based user authentication. | `React` `Node.js` `Express.js` `MongoDB` `JWT` | [**Live Platform**](https://trimrrs.onrender.com) |
| **✨ Magma UI Clone** | High-performance interactive replica showcasing complex WebGL shader pipelines and smooth GSAP timelines. | `Three.js` `GSAP` `WebGL` `React` | [**Source Code**](https://github.com/SAHITYA350/magma-clone) |

</div>

---

## 🛠️ Tech Stack Palette

<div align="left">

### 🎨 Frontend Mastery
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)

### ⚙️ Backend & Databases
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### 🧠 AI/ML & Data Science
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

</div>

---

## 📈 Real-Time GitHub Analytics

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=SAHITYA350&show_icons=true&theme=radical&count_private=true&include_all_commits=true" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=SAHITYA350&theme=radical" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SAHITYA350&theme=react-dark&hide_border=true&area=true" width="100%" />
</div>

<br/>

<p align="center"> 
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=sahitya350&theme=onedark&no-frame=true&margin-w=15&row=1&column=7" alt="GitHub Trophies" />
  </a> 
</p>

---

## 🏆 LeetCode Stats

<div align="center">
  <img src="https://leetcard.jacoblin.cool/balasur?theme=dark&font=source_code_pro&ext=activity" alt="LeetCode Stats" width="80%" />
</div>

---

## ✍️ Technical Writing

*   [Optimizing React Performance with useMemo and useCallback](https://dev.to/sahitya)
*   [Building Accessible Web Components: A Complete Guide](https://medium.com/@sahitya)
*   [From Zero to Hero: WebGL Animations in React](https://hashnode.com/@sahitya)

---

## 💡 Philosophy

> "In the era of AI, code is no longer just written — it's co-created. The future belongs to CSE minds who think beyond syntax and build with intelligence."

---

<div align="center">

<a href="https://twitter.com/sahityagbcx" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Follow%20@SahityaGbcx-1DA1F2?style=for-the-badge&logo=twitter&logoColor=black&labelColor=000000" alt="Follow @sahityagbcx on Twitter" />
</a>

<br/><br/>

*"The best engineers don't just write code — they build leverage. AI is the highest leverage tool of our generation."*

</div>

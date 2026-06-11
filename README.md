<!-- Banner -->
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&color=00BFFF&center=true&vCenter=true&width=500&lines=M+V+Karthikeya" alt="M V Karthikeya" />
</h1>

<p align="center">
  <strong>🚀 AI/ML Engineer & Computer Vision Researcher</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mv-karthikeya-b26a2131b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Mvkarthikeya07&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile views"/>
</p>

---

## 👨‍💻 About Me

I am a Computer Science & Engineering student specializing in Artificial Intelligence and Machine Learning, focused on designing real-time perception systems, intelligent automation, and data pipelines. I aim to ground theoretical machine learning principles into practical, reliable code implementations.

* 🏓 **National-Level Table Tennis Player:** Represented the state in national championships. High-performance sports built my core engineering mindset: rigorous discipline, rapid iterative adjustments, and performing under intense pressure.
* 🔬 **Research-Oriented Developer:** Actively developing and benchmarking systems with the goal of publishing in peer-reviewed (Scopus/Springer indexed) journals.
* 🎯 **DAAD Germany Candidate:** Structuring my current research and system design portfolio toward a Master's in Computer Science at German public universities for the 2026/2027 intake.

---

## 📐 Core Focus Areas
* **Computer Vision Optimization:** Handling live camera streams, custom frame preprocessing pipelines, array transformations via NumPy, and implementing models like YOLOv8/v11 for edge tasks.
* **Backend Infrastructure:** Building lightweight, functional REST APIs using Python and Flask, managing concurrency without blocking network loops, and ensuring reliable data input boundaries.
* **Predictive Modeling:** Mapping tabular datasets into time-series frameworks, scaling regional forecasting ensembles, and evaluating accuracy thresholds without relying on compute-heavy deep learning configurations.

---

## 🧰 Technical Ecosystem

### 💻 Deep Learning & Computer Vision
<code><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/></code>
<code><img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/></code>
<code><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/></code>
<code><img src="https://img.shields.io/badge/YOLOv8-006400?style=for-the-badge&logo=ultralytics&logoColor=white" alt="YOLOv8"/></code>

### 📊 Data Pipelines & Mathematics
<code><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/></code>
<code><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/></code>
<code><img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/></code>
<code><img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/></code>

### 🌐 Tooling & Environments
<code><img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/></code>
<code><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/></code>
<code><img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"/></code>

---

## 🏗️ Technical Projects & System Case Studies

### 🏎️ 1. Modular Hybrid Perception Framework for Autonomous Driving
* **The Challenge:** Pure deep learning lane identification setups consume massive computing power on edge devices, while standalone classical computer vision parameters fail when encountering rapid outdoor lighting variations.
* **The Architecture:** Developed a hybrid pipeline pairing classical CV with deep learning. Lane boundary mapping uses a sequential OpenCV block (CLAHE $\to$ ROI $\to$ Bird's Eye View $\to$ Sliding Window $\to$ Polynomial Curve Fitting) yielding **28 FPS on GPU**. It runs alongside a GPU-accelerated **YOLOv8s** architecture targeted specifically at road-relevant classes to minimize computing overhead.
* **Performance:** Object Detection $mAP@0.5 = 0.91$ | Lane Detection $mIoU = 0.86$.

---

### 🔒 2. Real-Time Secure Indoor Object Detection Framework
* **The Challenge:** Most standard model implementations only run as local script outputs. They lack network access configurations, stream security boundaries, or structural optimizations for real-world deployments.
* **The Architecture:** Implemented a secure Flask-backed streaming app using **YOLOv8m (25.9M parameters)** to reduce geometric shape misclassifications common in lighter models. The backend utilizes application-layer whitelisting to filter out irrelevant categories, handles explicit $BGR \to RGB$ array channel alignment before inference to maintain accuracy, and serves the feed via thread-isolated streaming boundaries.
* **Security:** Secured all endpoint and video configurations behind session-gated authentication routes signed with cryptographic validation parameters.

---

### 🎯 3. AI-Driven Adaptive Interview Simulation Platform
* **The Challenge:** Building a dynamic automated evaluation screening tool that shifts its technical complexity based on user responses, while running background verification to check for non-compliance.
* **The Architecture:** Developed an evaluation environment that maps text responses to gauge technical completeness, altering interview routing rules dynamically. In parallel, a concurrent background OpenCV script monitors live video feeds, tracking head position coordinates and verifying environmental compliance markers to flag secondary hardware components.

---

### 🤖 4. J.A.R.V.I.S: Autonomous AI Desktop Assistant
* **The Challenge:** Moving away from hardcoded keyword arrays that crash when phrasing changes, and managing multiple local automation tasks without triggering thread deadlocks.
* **The Architecture:** Programmed an object-oriented Python application using the **Claude LLM API** to interpret natural language intentions. The system extracts goals from spoken phrases, plans step-by-step tasks, and sends commands to local system layers (controlling apps, filesystem pathways, and browser automation setups).
* **Latency:** Built with non-blocking multi-threading to handle audio operations cleanly, processing the end-to-end flow in **~1 second** using an instant offline text-to-speech module.

---

### 🌧️ 5. HydraCast: Predictive Multi-Step Rainfall Forecasting System
* **The Challenge:** Time-series regional weather predictions often default to heavy Recurrent Neural Networks (LSTMs), which carry complex hardware dependencies and train poorly on lighter, sparse data matrices.
* **The Architecture:** Engineered a lightweight forecasting engine using a `RandomForestRegressor` ensemble ($50\ trees,\ max\_depth=8$). The data pipeline transforms irregular data structures using an automated `.melt()` vector conversion, tracks rolling 10-day history windows, and runs a **recursive predict-and-slide vector loop** to calculate 7-day forward predictions.
* **Latency:** Generates localized forecasts in under **100ms** running purely on lightweight CPU environments with zero neural compute overhead.

---

## 📈 Performance & Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mvkarthikeya07&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="190"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mvkarthikeya07&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="190"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mvkarthikeya07&theme=tokyonight&hide_border=true" height="180"/>
</p>

---

## 📬 Open Collaboration

I am looking to connect for engineering internships, research groups, and open-source contributions focusing on practical Computer Vision and optimized ML setups.

* 🌐 **LinkedIn:** [M V Karthikeya](https://www.linkedin.com/in/mv-karthikeya-b26a2131b)
* 🐙 **Repositories:** Feel free to review, fork, or clone any of the codebase configurations.

```markdown
⚡ "Clean code logic and resource efficiency are the real differentiators in production AI development."

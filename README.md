<!-- Banner -->
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&color=00BFFF&center=true&vCenter=true&width=500&lines=M+V+Karthikeya" alt="M V Karthikeya" />
</h1>

<h3 align="center">
🚀 Computer Vision Engineer • AI Developer • Research-Oriented Builder
</h3>

<p align="center">
  Building intelligent systems using Computer Vision, Machine Learning, Predictive Analytics, and AI-driven Automation.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mv-karthikeya-b26a2131b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&maxAge=2592000"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Mvkarthikeya07&label=Profile%20Views&color=0e75b6&style=flat-square"/>
</p>

---

# 👨‍💻 About Me

Computer Science and Engineering student specializing in Artificial Intelligence and Machine Learning, with a core focus on Computer Vision, Intelligent Systems, and Applied ML. I bridge the gap between theoretical models and clean, resource-efficient system implementations.

- 🏓 **National-Level Athlete:** Represented Andhra Pradesh in national-level table tennis competitions. Competitive sports instilled the high-level discipline, resilience, and rapid adaptability that govern my approach to software engineering and research.
- 🔬 **System Developer:** Experienced in designing and deploying practical AI applications across Computer Vision, Forecasting, NLP, and Desktop Automation.
- 🎯 **Research Focus:** Building reproducible AI systems while preparing for advanced graduate study in Computer Vision and Intelligent Systems.

---

# 🔬 Research Interests

- **Computer Vision & Scene Understanding:** Low-latency object tracking, spatial geometry, and video analysis loops.
- **Edge AI Optimization:** Streamlining deep networks to run efficiently on resource-constrained hardware.
- **Intelligent Automation:** Event-driven architectures and context-aware autonomous software agents.
- **Applied Deep Learning in Healthcare:** High-accuracy predictive modeling using medical imaging datasets.

---

# 🧰 Technical Expertise

- **Programming:** `Python` • `C++` • `SQL`
- **AI & Deep Learning:** `PyTorch` • `OpenCV` • `Scikit-Learn` • `YOLOv8`
- **Backend & Deployment:** `Flask` • `REST APIs` • `SQLite`
- **Tools & Environments:** `Git` • `GitHub` • `VS Code` • `Linux`

---

# 🏗️ Technical Projects & Case Studies

## 🏎️ 1. Autonomous Driving Perception Framework
> Real-time hybrid road perception pipeline combining classical computer vision techniques with deep learning.

* **The Challenge:** Pure deep learning networks generate heavy computational overhead on edge nodes, while standalone classical CV algorithms break easily under rapid environmental lighting changes.
* **The Architecture:** Engineered a hybrid processing pipeline. Lane boundary localization uses a sequential OpenCV pipeline (CLAHE $\to$ Region of Interest filtering $\to$ Bird's Eye View transformation $\to$ Sliding Window profiling $\to$ Polynomial Curve Fitting). This runs concurrently alongside a GPU-accelerated **YOLOv8s** architecture targeted specifically at road-relevant COCO classes to save processing cycles.
* **Performance:** Implements a multi-threaded execution queue with an integrated visualization dashboard for real-time inference logging and class-specific threshold adjustments.

---

## 🔒 2. Real-Time Indoor Object Detection Platform
> Secured web-based computer vision platform for authenticated live stream video monitoring.

* **The Challenge:** Most standard model implementations operate purely as local script windows, lacking network access boundaries, stream security layers, or target filtering.
* **The Architecture:** Developed a secure web ecosystem around a **YOLOv8m network (25.9M parameters)** to reduce geometric shape misclassifications common in lighter models. The application uses server-side whitelisting to filter out irrelevant categories down to 40 core indoor classes, handles explicit $BGR \to RGB$ array channel alignment to preserve validation accuracy, and broadcasts frames over a multi-threaded real-time video streaming architecture.
* **Security:** Gated all streaming routes behind signed, session-based authentication blocks (`SECRET_KEY`) to eliminate unauthorized endpoint access.

---

## 🤖 3. J.A.R.V.I.S: Autonomous AI Desktop Assistant
> Multi-threaded system automation assistant driven by conversational natural language intent.

* **The Challenge:** Bypassing hardcoded, brittle keyword matching strings that fail when user phrasing varies, and managing deep OS-level automation safely without triggering execution locks.
* **The Architecture:** Programmed an object-oriented Python automation loop integrating the **Claude LLM API** as its core reasoning planner. The engine interprets natural spoken intent, maps multi-step instructions into clear execution tasks, and dispatches them safely to low-level system controllers (handling application launches, file systems, and web automation).
* **Latency:** Built on an event-driven, non-blocking multi-threaded framework. Processes end-to-end loops in **~1 second** using an instant, completely offline text-to-speech module.

---

## 🎯 4. AI-Driven Adaptive Interview Simulation Platform
> Adaptive interview simulation system with dynamic question routing and real-time proctoring using computer vision.

* **The Challenge:** Creating a technical screening tool that dynamically measures engineering depth instead of presenting flat, static question lists, while ensuring compliance verification in the background.
* **The Architecture:** Implemented an NLP evaluation system that scores user text responses for semantic completeness and dynamically shifts the complexity of subsequent interview questions. Operating on a separate background thread is a concurrent OpenCV pipeline that processes the camera feed to monitor facial gaze direction matrices and flag unauthorized secondary hardware presence.

---

## 🌧️ 5. HydraCast: Predictive Rainfall Forecasting Analytics System
> Lightweight regional forecasting analytics platform optimizing time-series predictions for CPU-bound execution.

* **The Challenge:** Regional meteorological time-series operations typically default to complex deep learning models (LSTMs), introducing high training instability, hardware dependencies, and deployment friction.
* **The Architecture:** Designed an efficient analytics framework driven by a `RandomForestRegressor` ensemble ($50\ trees,\ max\_depth=8$). The data pipeline ingestion layer uses an optimized vector `.melt()` strategy to parse non-standard tabular data, structures properties across a rolling 10-day history matrix, and generates clean 7-day rainfall forecasts using recursive prediction.
* **Latency:** Generates localized forecasts in under **100ms** utilizing parallelized CPU processing threads (`n_jobs=-1`) with zero neural compute dependencies.

---

# 📊 GitHub Performance & Analytics

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Mvkarthikeya07&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mvkarthikeya07&layout=compact&theme=tokyonight&hide_border=true&langs_count=6"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mvkarthikeya07&theme=tokyonight&hide_border=true" height="180"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Mvkarthikeya07&theme=tokyonight&no-frame=true&row=1&column=7"/>
</p>

---

# 🏆 Profile Highlights

* 🏓 **National Table Tennis Player:** Represented Andhra Pradesh; driven by routine, hard discipline, and systematic practice.
* 🚀 **Systems-Minded Developer:** Passionate about deploying production-ready AI beyond notebook environments.
* 📚 **Research & Benchmarking Focus:** Emphasizing clear code quality, clean documentation, and mathematical optimization.

---

# 🤝 Open to Collaboration

I am open to connecting with engineers, researchers, and labs for initiatives involving:
- Computer Vision Research & Pipeline Optimization
- Open-Source Machine Learning Infrastructure
- Intelligent Desktop Automation Systems
- Applied Machine Learning & Predictive Analytics

---

# 📫 Connect With Me

- **LinkedIn:** [M V Karthikeya](https://www.linkedin.com/in/mv-karthikeya-b26a2131b)
- **GitHub:** [Mvkarthikeya07](https://github.com/Mvkarthikeya07)
- **Email:** [mv.karthikeya.dev@gmail.com](mailto:mv.karthikeya.dev@gmail.com)

---

> *“The true value of AI lies not in training models, but in engineering systems that reliably solve real-world problems.”*

<p align="center">
  <img alt="Profile Image" width="240" height="240" style="border-radius:50%;" src="https://raw.githubusercontent.com/MohamedELHalmoushy/MohamedELHalmoushy/main/Mohamed%20EL-Halmoushy.png">
</p>

<h1 align="center">👑 Mohamed El-Halmoushy 👑</h1>
<h3 align="center">AI Engineer | DL Engineer  | Computer Engineer | NLP Engineer</h3>


<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=24&center=true&vCenter=true&width=600&lines=AI+Engineer;Machine+Learning+Developer;DSP+%26+Embedded+Systems+Engineer;Computer+Engineering;IoT+Developer;Always+Learning+New+Technologies">
</p>

---

## 🚀 About Me  
- 🎓 Computer Engineering Student at **Helwan National University**  
- 🤖 Passionate about **AI, ML, DSP, IoT, and Embedded Systems**  
- 💡 Experienced in Deep Learning, NLP, Computer Vision, and real-time applications  
- 🧠 Worked on multiple projects using **Python, MATLAB, Java, C, and Embedded C**  
- 🌱 Currently learning **Cloud Computing, Deployment, and Advanced AI Engineering**  
- 🚀 I love building projects that combine **software + hardware + intelligence**

---
<p align="center">
  <img alt="2nd Place" width="500" height="600" style="border-radius:50%;" src="https://raw.githubusercontent.com/MohamedELHalmoushy/MohamedELHalmoushy/main/Hackathon.jpg">
</p>
---
## 🧠 Technical Skills  

<p align="center">
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="120" />
</p>

---

### 🔹 <img src="https://img.icons8.com/color/48/artificial-intelligence.png" width="24"/> AI & Machine Learning  

<div align="center">

| Skill | Tools / Technologies |
|-------|-----------------------|
| **Programming & ML** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Sklearn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) |
| **Deep Learning** | CNNs, RNNs, Seq2Seq, Embeddings |
| **NLP** | Emotion Recognition, Sentiment Analysis, Text Classification |
| **Face Recognition** | MTCNN, FaceNet, SSD |
| **Object Detection** | SSD MobileNet, YOLOv8 |

</div>

---

### 🔹 <img src="https://img.icons8.com/external-flat-satawat-anukul/64/external-dsp-chip-flat-satawat-anukul.png" width="24"/> DSP (Digital Signal Processing)

<div align="center">

| Area | Tools |
|------|--------|
| **Core DSP** | Filters, FFT, Signal Enhancement |
| **Applications** | DSP for Object Detection, Real-Time Processing |
| **Software** | ![MATLAB](https://img.shields.io/badge/MATLAB-FF7800?logo=MathWorks&logoColor=white) ![Simulink](https://img.shields.io/badge/Simulink-007ACC?logo=simulink&logoColor=white) |
| **Research** | Audio Watermarking |

</div>

---

### 🔹 <img src="https://img.icons8.com/color/48/microchip.png" width="24"/> Embedded Systems & IoT

<div align="center">

| Category | Tools & Hardware |
|----------|------------------|
| **Microcontrollers** | ATmega32, Arduino, ESP8266 |
| **Hardware Interfaces** | Sensors, Motors, LCD, UART, ADC |
| **Drivers & Modules** | L293 Motor Driver |
| **IoT** | Real-time Monitoring, WiFi Control |

</div>

---

### 🔹 <img src="https://img.icons8.com/color/48/laptop-coding.png" width="24"/> Software Engineering

<div align="center">

| Field | Technologies |
|-------|--------------|
| **Backend** | Flask, FastAPI |
| **Desktop Apps** | Java Swing |
| **Databases** | MySQL, JSON |
| **Dev Tools** | Git, GitHub, Linux |
| **APIs** | REST API Architecture |

</div>

---
<style>
/* ==== Slider Container ==== */
.slider {
  display: flex;
  overflow-x: auto;
  scroll-behavior: smooth;
  gap: 20px;
  padding-bottom: 20px;
}

/* Hide scrollbar */
.slider::-webkit-scrollbar { display: none; }
.slider { -ms-overflow-style: none; scrollbar-width: none; }

/* ==== Project Card ==== */
.project-card {
  min-width: 320px;
  max-width: 350px;
  border-radius: 20px;
  padding: 20px;
  background: linear-gradient(135deg, #1e1e2e, #2c2c3d);
  box-shadow: 0 0 25px rgba(0,255,255,0.2);
  border: 2px solid transparent;
  position: relative;
  overflow: hidden;
  transform: translateY(50px);
  opacity: 0;
  transition: transform 0.5s ease, box-shadow 0.5s ease;
  perspective: 1000px;
  flex-shrink: 0;
}

/* Slide-in Animation */
.project-card.animate {
  transform: translateY(0);
  opacity: 1;
}

/* ==== Glow Animated Border ==== */
.project-card::before {
  content: "";
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
  background: linear-gradient(45deg, #00fff7, #ff00f7, #ffff00, #00fff7);
  animation: gradientMove 4s linear infinite;
  z-index: 0;
  opacity: 0.25;
}

@keyframes gradientMove {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

/* Hover Effects */
.project-card:hover {
  transform: rotateY(5deg) rotateX(3deg) scale(1.08);
  box-shadow: 0 0 35px rgba(0,255,255,0.55);
}

/* ==== Card Content ==== */
.project-card > * {
  position: relative;
  z-index: 1;
}

.project-title {
  font-size: 1.4rem;
  font-weight: bold;
  margin-bottom: 10px;
  display: flex;
  align-items: center;
  gap: 10px;
  color: #00fff7;
}

.project-title img {
  width: 28px;
  height: 28px;
  animation: bounce 1.5s infinite;
}

/* GIF Animation */
.project-gif {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 10px;
  transition: transform 0.3s ease;
}

.project-card:hover .project-gif {
  transform: scale(1.08);
}

/* Bounce Animation for icons */
@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-5px); }
}

/* Dark/Light Mode */
@media (prefers-color-scheme: light) {
  .project-card {
    background: linear-gradient(135deg, #f0f7ff, #d0e3ff);
    box-shadow: 0 0 20px rgba(0,0,0,0.1);
  }
  .project-title { color: #0078d4; }
}
</style>

<div class="slider">

<!-- ==== PROJECT 1 ==== -->
<div class="project-card">
  <div class="project-title">
    <img src="https://img.icons8.com/color/48/robot-2.png"/> AI Chatbot with Emotional Understanding
  </div>
  <img class="project-gif" src="https://media.giphy.com/media/EQ9uZf7L3nfYk/giphy.gif">
  <ul>
    <li>Detects <b>happiness, sadness, anger, fear</b></li>
    <li>Built using <b>NLP + Seq2Seq + Deep Learning</b></li>
    <li>API-ready & tested via Postman</li>
  </ul>
</div>

<!-- ==== PROJECT 2 ==== -->
<div class="project-card">
  <div class="project-title">
    <img src="https://img.icons8.com/color/48/eye.png"/> Real-time Face Recognition System
  </div>
  <img class="project-gif" src="https://media.giphy.com/media/l3fzGBzPUkGWDfPBu/giphy.gif">
  <ul>
    <li>Uses <b>MTCNN + FaceNet embeddings</b></li>
    <li>Real-time: videos, images, webcam</li>
    <li>Developed on Google Colab using Kaggle dataset</li>
  </ul>
</div>

<!-- ==== PROJECT 3 ==== -->
<div class="project-card">
  <div class="project-title">
    <img src="https://img.icons8.com/color/48/music.png"/> Audio Watermarking System (MATLAB)
  </div>
  <img class="project-gif" src="https://media.giphy.com/media/yYSSBtDgbbRzq/giphy.gif">
  <ul>
    <li>Hides secret text inside audio</li>
    <li>Uses DSP techniques (FFT + Filters)</li>
    <li>Accurate data recovery</li>
  </ul>
</div>

<!-- ==== PROJECT 4 ==== -->
<div class="project-card">
  <div class="project-title">
    <img src="https://img.icons8.com/color/48/trash.png"/> Smart Trash Bin using ATmega32
  </div>
  <img class="project-gif" src="https://media.giphy.com/media/2ikwIgNrmPZICNmRyX/giphy.gif">
  <ul>
    <li>Waste categorization with sensors</li>
    <li>Motor control using L293</li>
    <li>LCD interface + Proteus design</li>
  </ul>
</div>

<!-- ==== PROJECT 5 ==== -->
<div class="project-card">
  <div class="project-title">
    <img src="https://img.icons8.com/color/48/email.png"/> Spam Email Classifier
  </div>
  <img class="project-gif" src="https://media.giphy.com/media/xTiIzJSKB4l7xTouE8/giphy.gif">
  <ul>
    <li>Text preprocessing</li>
    <li>Models: SVM, Logistic Regression, Naive Bayes</li>
    <li>Accuracy: <b>97%</b></li>
  </ul>
</div>

</div>

<script>
/* ==== Animate Cards on Load ==== */
document.addEventListener("DOMContentLoaded", () => {
  const cards = document.querySelectorAll(".project-card");
  cards.forEach((card, idx) => {
    setTimeout(() => { card.classList.add("animate"); }, idx * 200);
  });
});
</script>

## 🏅 Achievements  
- Ranked **1st** in Intelligent Systems Engineering  
- Ranked **2nd** in CyberArena Hackathon AI Battle  
- Completed **AI/ML Internship** at Tripple One Solutions  
- Completed **AI Training** at Telecom Egypt  
- Certificate in **Critical Infrastructure Protection**  
- Built multiple high-impact academic and professional projects  

---

## 📊 GitHub Stats

<p align="center">
  <!-- GitHub Overall Stats Card -->
  <img height="160" src="https://github-readme-stats-sigma-five.vercel.app/api?username=MohamedELHalmoushy&show_icons=true&theme=tokyonight" />
  <!-- Top Languages Card -->
  <img height="160" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=MohamedELHalmoushy&layout=compact&theme=tokyonight" />
</p>

<p align="center">
  <!-- Stars -->
  <a href="https://github.com/MohamedELHalmoushy?tab=stars" target="_blank">
    <img src="https://img.shields.io/github/stars/MohamedELHalmoushy?style=flat-square&logo=github&label=Stars&color=yellow" alt="Stars"/>
  </a>
  &nbsp;&nbsp;
  <!-- Followers -->
  <a href="https://github.com/MohamedELHalmoushy?tab=followers" target="_blank">
    <img src="https://img.shields.io/github/followers/MohamedELHalmoushy?style=flat-square&logo=github&label=Followers&color=blue" alt="Followers"/>
  </a>
  &nbsp;&nbsp;
  <!-- Profile Views -->
  <a href="https://komarev.com/ghpvc/?username=MohamedELHalmoushy" target="_blank">
    <img src="https://komarev.com/ghpvc/?username=MohamedELHalmoushy&color=blue&style=flat-square" alt="Profile Views"/>
  </a>
</p>

---

## 🔥 GitHub Streak  
<p align="center">
  <img src="https://streaks-readme.vercel.app/api?user=MohamedELHalmoushy&theme=tokyonight" />
</p>



---

## 🖥️ Languages  
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## 🧩 Frameworks & Tools  
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-FF7800?style=for-the-badge&logo=MathWorks&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white)

---

## 🛠️ Tools & Technologies  
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP8266-000000?style=for-the-badge&logo=espressif&logoColor=white" />
</p>

---

## 🏆 Developer Badges  
![AI Engineer](https://img.shields.io/badge/AI%20Engineer-8A2BE2?style=for-the-badge&logo=artificialintelligence&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Embedded Systems](https://img.shields.io/badge/Embedded%20Systems-00599C?style=for-the-badge&logo=arduino&logoColor=white)
![IoT Developer](https://img.shields.io/badge/IoT%20Developer-00A8E8?style=for-the-badge&logo=espressif&logoColor=white)

---


## 📫 Connect With Me  
<p align="center">
  🌐 <a href="https://github.com/MohamedELHalmoushy">GitHub</a> •  
  💼 <a href="https://www.linkedin.com/in/mohamed-el-halmoushy/">LinkedIn</a> •  
  📧 <a href="mailto:mohamedaymanelhalmoushy@gmail.com">Email Me</a>
</p>

---

## 💎 Contribution Activity (Advanced & Animated)

### 🐍 Contribution Snake (Animated)
<p align="center">
  <img src="https://raw.githubusercontent.com/MohamedELHalmoushy/MohamedELHalmoushy/output/github-contribution-grid-snake-dark.svg">
</p>


### 🔥 Profile Contribution Summary
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=MohamedELHalmoushy&theme=tokyonight" />
</p>

### ⏰ Productive Time (When you code the most)
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=MohamedELHalmoushy&theme=tokyonight" />
</p>

### 🌡️ Contribution Heatmap (Pro)
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MohamedELHalmoushy&theme=tokyonight&hide_border=true&area=true" />
</p>

---

### ⚡ Fun Fact  
I build intelligent systems that combine **AI + DSP + Embedded Systems** to solve real-world problems.

# Portfolio Project Showcase: AI-Proctor

## Project Metadata
- **Project Title:** AI-Proctor: Next-Gen AI-Powered Online Examination & Intelligent Proctoring System
- **Developer:** Subham Sanket
- **Tech Stack:** Python, Flask, OpenCV, TensorFlow, DeepFace, YOLOv3, MySQL, Web Audio API, Docker, Stripe API

---

## 🚀 Short Portfolio Pitch (1-2 Sentences)
> **AI-Proctor** is an end-to-end, high-integrity online examination platform featuring a multi-dimensional AI proctoring pipeline (biometric face verification, 3D head pose estimation, gaze tracking, YOLOv3 phone/person detection, and decibel audio telemetry) alongside automated NLP test generation and a multi-language coding IDE.

---

## 📌 Full Portfolio Description (For Portfolio Website / Case Study)

### 🌟 Project Overview
With the shift toward digital learning and remote assessments, maintaining academic integrity without invasive human surveillance is a key challenge. **AI-Proctor** solves this by providing a unified, web-based examination platform that seamlessly combines assessment creation, automated NLP question generation, multi-format exam delivery (MCQ, Subjective, and Coding), and a real-time computer vision proctoring engine.

---

### 💡 Key Architectural Highlights & Engineering Innovations

1. **Multi-Dimensional AI Proctoring Engine**
   - **Biometric Identity Check:** Built continuous face-matching check-in workflows using **DeepFace (VGG-Face)** to prevent impersonation.
   - **Head Pose & Gaze Analysis:** Computed 3D head orientation vectors (pitch, yaw, roll) using 68-point facial landmarks and `cv2.solvePnP` to flag off-screen head movements.
   - **YOLOv3 Object & Person Detection:** Trained object detection pipelines to scan real-time camera streams for unauthorized items (e.g., mobile phones) and monitor room occupant counts.
   - **Real-Time Decibel Telemetry:** Leveraged client-side Web Audio API (`AudioContext`) to continuously record environmental decibel levels, alerting instructors to noise spikes and verbal collaboration.

2. **Full-Featured Exam Suite & In-Browser IDE**
   - Engineered support for Objective (MCQ), Subjective (Essay), and Practical (Coding) tests.
   - Integrated an interactive in-browser compiler environment supporting execution for **15+ programming languages**.

3. **Intelligent NLP Test Authoring**
   - Designed an automated test generation engine using **NLTK POS Tagging** and **WordNet** semantic networks to auto-extract key concepts from raw educational texts and generate valid MCQs with dynamic distractors.

4. **Instructor Telemetry Console & Payment Gateway**
   - Designed a comprehensive live proctoring dashboard that streams real-time candidate metrics and violation flags.
   - Integrated **Stripe Payment Intent APIs** to enable secure credit purchasing for exam hosting.

---

## 🛠️ Technical Skills Demonstrated
- **AI & Computer Vision:** OpenCV, TensorFlow, DeepFace, YOLOv3, Facial Landmark Tracking, Head Pose Estimation (`solvePnP`).
- **Natural Language Processing:** NLTK, WordNet Distractor Generation, Text Processing.
- **Full-Stack Development:** Python, Flask, Jinja2, HTML5 (WebCam & Audio APIs), JavaScript (ES6+), Bootstrap 5, MySQL.
- **DevOps & Architecture:** Docker, Docker Compose, RESTful APIs, Web Security (Window Blur / Visibility Monitoring).

---

## 📋 Copy-Paste HTML Card Snippet for `portfolio.html`

```html
<div class="portfolio-card glass-card p-4 rounded-4 shadow-lg mb-4">
  <div class="d-flex justify-content-between align-items-center mb-2">
    <span class="badge bg-primary text-uppercase px-3 py-2">Full-Stack AI Project</span>
    <small class="text-muted">Python • Flask • OpenCV • TensorFlow</small>
  </div>
  <h3 class="fw-bold mb-2">AI-Proctor — Intelligent Online Examination & Proctoring System</h3>
  <p class="text-secondary">
    An end-to-end web platform featuring multi-modal AI proctoring (DeepFace biometrics, 3D head pose estimation, gaze tracking, YOLOv3 phone detection, and audio decibel monitoring), an automated NLP test generator, and an embedded compiler for 15+ coding languages.
  </p>
  <div class="d-flex gap-2 flex-wrap mb-3">
    <span class="badge bg-dark-subtle text-dark">Python</span>
    <span class="badge bg-dark-subtle text-dark">Flask</span>
    <span class="badge bg-dark-subtle text-dark">OpenCV</span>
    <span class="badge bg-dark-subtle text-dark">TensorFlow</span>
    <span class="badge bg-dark-subtle text-dark">YOLOv3</span>
    <span class="badge bg-dark-subtle text-dark">DeepFace</span>
    <span class="badge bg-dark-subtle text-dark">MySQL</span>
    <span class="badge bg-dark-subtle text-dark">Docker</span>
  </div>
  <div class="d-flex gap-3">
    <a href="https://github.com/subhamsanket/AI-Proctor" target="_blank" class="btn btn-outline-primary btn-sm rounded-pill px-4">
      <i class="fab fa-github me-1"></i> View Code
    </a>
  </div>
</div>
```

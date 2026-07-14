<div align="center">

Sagnick Paul

### Electrical Engineering → Autonomous Intelligence

</div>

<svg width="100%" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg" style="margin: 20px 0;">
  <defs>
    <style>
      @keyframes flow {
        0% { stroke-dashoffset: 1000; }
        100% { stroke-dashoffset: 0; }
      }
      @keyframes pulse {
        0%, 100% { r: 3; opacity: 1; }
        50% { r: 5; opacity: 0.3; }
      }
      .circuit-line {
        stroke: #58a6ff;
        stroke-width: 2;
        fill: none;
        stroke-dasharray: 1000;
        animation: flow 8s linear infinite;
      }
      .node {
        fill: #58a6ff;
        animation: pulse 2s ease-in-out infinite;
      }
      .signal-wave {
        stroke: #79c0ff;
        stroke-width: 1.5;
        fill: none;
      }
    </style>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#79c0ff;stop-opacity:0.3" />
    </linearGradient>
  </defs>
  
  <!-- Circuit path -->
  <path class="circuit-line" d="M 50 60 L 150 60 L 150 30 L 250 30 L 250 90 L 350 90" />
  <path class="circuit-line" d="M 350 90 L 450 90 L 450 45 L 550 45 L 550 75 L 650 75" />
  <path class="circuit-line" d="M 650 75 L 750 75" />
  
  <!-- Nodes -->
  <circle class="node" cx="50" cy="60" r="3" />
  <circle class="node" cx="150" cy="60" r="3" />
  <circle class="node" cx="250" cy="30" r="3" />
  <circle class="node" cx="350" cy="90" r="3" />
  <circle class="node" cx="450" cy="45" r="3" />
  <circle class="node" cx="550" cy="75" r="3" />
  <circle class="node" cx="650" cy="75" r="3" />
  <circle class="node" cx="750" cy="75" r="3" />
  
  <!-- Signal wave overlay -->
  <g opacity="0.4">
    <path class="signal-wave" d="M 50 90 Q 75 70 100 90 T 150 90 T 200 90 T 250 90 T 300 90 T 350 90 T 400 90 T 450 90 T 500 90 T 550 90 T 600 90 T 650 90 T 700 90 T 750 90" />
  </g>
</svg>

---
## About

<div style="background: linear-gradient(135deg, #0d1117 0%, #161b22 100%); padding: 20px; border-radius: 8px; border-left: 3px solid #58a6ff; margin: 20px 0;">

**Electrical Engineering** undergraduate at Jadavpur University, architecting intelligent systems at the intersection of **control theory**, **deep learning**, and **embedded hardware**.

I ship end-to-end autonomous platforms—from sub-10ms sensor fusion on microcontrollers to ONNX-quantized neural networks running on edge devices. Philosophy: **Real-world performance over benchmark optimization.**
</div>

---

## 🎯 Featured Projects

### ⚡ TraffIQ: Autonomous Driving System  
**🏆 Top 5 Nationwide**

<table>
<tr>
<td width="70%">

End-to-end navigation stack trained on Udacity + CARLA simulators. Behavioral cloning for steering prediction, YOLOv8n for real-time obstacle detection. **ONNX-quantized** deployment on Raspberry Pi 4B with <50ms inference latency—handles unseen tracks with smooth, stable control.

**Tech Stack:**  
`Python` `PyTorch` `YOLOv8` `ONNX` `OpenCV` `CARLA` `Raspberry Pi`

</td>
<td width="30%">

<svg width="100%" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; border-radius: 8px;">
  <defs>
    <style>
      @keyframes drive {
        0% { transform: translateX(0px); }
        50% { transform: translateX(20px); }
        100% { transform: translateX(0px); }
      }
      .car-body {
        fill: #58a6ff;
      }
      .wheel {
        fill: #30363d;
      }
      .car-group {
        animation: drive 3s ease-in-out infinite;
      }
    </style>
  </defs>
  
  <!-- Road -->
  <line x1="10" y1="100" x2="130" y2="100" stroke="#30363d" stroke-width="3" />
  <line x1="10" y1="110" x2="130" y2="110" stroke="#30363d" stroke-width="1" stroke-dasharray="5,5" opacity="0.5" />
  
  <!-- Car -->
  <g class="car-group">
    <!-- Body -->
    <rect class="car-body" x="35" y="60" width="40" height="25" rx="3" />
    <!-- Cabin -->
    <rect fill="#79c0ff" x="45" y="50" width="20" height="15" rx="2" />
    <!-- Wheels -->
    <circle class="wheel" cx="45" cy="92" r="5" />
    <circle class="wheel" cx="70" cy="92" r="5" />
  </g>
  
  <!-- Signal waves (detection) -->
  <g opacity="0.4">
    <circle cx="70" cy="70" r="15" fill="none" stroke="#79c0ff" stroke-width="1" />
    <circle cx="70" cy="70" r="25" fill="none" stroke="#58a6ff" stroke-width="0.5" />
  </g>
</svg>

</td>
</tr>
</table>

---

### 🧠 Multi-Agent Research Laboratory

<table>
<tr>
<td width="30%">

<svg width="100%" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; border-radius: 8px;">
  <defs>
    <style>
      @keyframes ping {
        0% { r: 4; opacity: 1; }
        100% { r: 20; opacity: 0; }
      }
      @keyframes rotate-slow {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
      }
      .agent {
        fill: #58a6ff;
      }
      .connection {
        stroke: #30363d;
        stroke-width: 1;
      }
      .connection-active {
        stroke: #79c0ff;
        stroke-width: 1.5;
        opacity: 0.6;
      }
      .pulse {
        fill: #79c0ff;
        animation: ping 2s ease-out infinite;
      }
    </style>
  </defs>
  
  <!-- Central hub -->
  <circle class="agent" cx="70" cy="70" r="6" />
  <circle cx="70" cy="70" r="6" fill="none" stroke="#58a6ff" stroke-width="2" opacity="0.3" />
  
  <!-- Agents -->
  <circle class="agent" cx="35" cy="40" r="4" />
  <circle class="agent" cx="105" cy="40" r="4" />
  <circle class="agent" cx="35" cy="100" r="4" />
  <circle class="agent" cx="105" cy="100" r="4" />
  
  <!-- Connections -->
  <line class="connection-active" x1="70" y1="70" x2="35" y2="40" />
  <line class="connection-active" x1="70" y1="70" x2="105" y2="40" />
  <line class="connection-active" x1="70" y1="70" x2="35" y2="100" />
  <line class="connection-active" x1="70" y1="70" x2="105" y2="100" />
  
  <!-- Pulses -->
  <circle class="pulse" cx="35" cy="40" r="4" />
  <circle class="pulse" cx="105" cy="40" r="4" />
  <circle class="pulse" cx="35" cy="100" r="4" />
  <circle class="pulse" cx="105" cy="100" r="4" />
</svg>

</td>
<td width="70%">

Advanced collaborative platform where autonomous agents perform real-time web search, content scraping, and academic evaluation in tandem. Live SSE streams power a premium React dashboard. One-click PDF/DOCX exports. Built for **synthesis over collection**.

**Tech Stack:**  
`Python` `FastAPI` `LangChain` `React` `TypeScript` `TailwindCSS` `SSE`

</td>
</tr>
</table>

---

### 🩺 Brain MRI Tumor Segmentation

<table>
<tr>
<td width="70%">

U-Net CNN for clinical-grade pixel-level tumor segmentation. Robust medical imaging preprocessing, domain-specific augmentation, and Dice coefficient optimization. Interactive Streamlit diagnostic app enables real-time visualization. Modular for backbone experimentation.

**Tech Stack:**  
`PyTorch` `U-Net` `OpenCV` `Streamlit` `Medical Imaging` `Dice/IoU`

</td>
<td width="30%">

<svg width="100%" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; border-radius: 8px;">
  <defs>
    <style>
      @keyframes scan {
        0% { transform: translateY(-70px); }
        100% { transform: translateY(70px); }
      }
      .mri-grid {
        stroke: #30363d;
        stroke-width: 0.5;
        fill: none;
      }
      .scan-line {
        stroke: #79c0ff;
        stroke-width: 2;
        animation: scan 3s linear infinite;
      }
      .tumor {
        fill: #ff6b6b;
        opacity: 0.7;
      }
    </style>
  </defs>
  
  <!-- MRI grid -->
  <g class="mri-grid">
    <circle cx="70" cy="70" r="50" />
    <circle cx="70" cy="70" r="35" />
    <circle cx="70" cy="70" r="20" />
    <line x1="30" y1="70" x2="110" y2="70" />
    <line x1="70" y1="30" x2="70" y2="110" />
  </g>
  
  <!-- Tumor region -->
  <circle class="tumor" cx="80" cy="60" r="12" />
  
  <!-- Scan line -->
  <line class="scan-line" x1="30" y1="70" x2="110" y2="70" />
</svg>

</td>
</tr>
</table>

---

### 🤖 Self-Balancing Robot

<table>
<tr>
<td width="30%">

<svg width="100%" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; border-radius: 8px;">
  <defs>
    <style>
      @keyframes balance {
        0% { transform: rotate(-2deg); }
        50% { transform: rotate(0deg); }
        100% { transform: rotate(-2deg); }
      }
      .robot-body {
        animation: balance 2s ease-in-out infinite;
        transform-origin: 70px 70px;
      }
    </style>
  </defs>
  
  <!-- Base/wheels -->
  <circle fill="#30363d" cx="50" cy="110" r="8" />
  <circle fill="#30363d" cx="90" cy="110" r="8" />
  <line x1="50" y1="110" x2="90" y2="110" stroke="#58a6ff" stroke-width="2" />
  
  <!-- Main body group with animation -->
  <g class="robot-body">
    <!-- Body -->
    <rect x="55" y="60" width="30" height="40" rx="2" fill="#58a6ff" />
    
    <!-- Head/Sensor -->
    <circle cx="70" cy="50" r="8" fill="#79c0ff" />
    <circle cx="65" cy="48" r="2" fill="#0d1117" />
    <circle cx="75" cy="48" r="2" fill="#0d1117" />
  </g>
  
  <!-- Balance indicators -->
  <line x1="35" y1="70" x2="50" y2="70" stroke="#30363d" stroke-width="1" stroke-dasharray="2,2" opacity="0.5" />
  <line x1="90" y1="70" x2="105" y2="70" stroke="#30363d" stroke-width="1" stroke-dasharray="2,2" opacity="0.5" />
</svg>

</td>
<td width="70%">

Two-wheeled inverted-pendulum platform with **dual-axis PID stabilization**. MPU6050 sensor fusion in C++ delivers sub-10ms response time. Handles slopes, uneven terrain, and dynamic perturbations with grace. Bluetooth remote for live parameter tuning.

**Tech Stack:**  
`C++` `Arduino` `MPU6050` `Real-Time Control` `Sensor Fusion`

</td>
</tr>
</table>

---

## 🛠 Technical Stack

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 30px 0;">

<div style="background: #0d1117; padding: 15px; border-radius: 8px; border-top: 2px solid #58a6ff;">

**Languages**  
Python · C++ · Java · MATLAB

</div>

<div style="background: #0d1117; padding: 15px; border-radius: 8px; border-top: 2px solid #58a6ff;">

**ML / Deep Learning**  
PyTorch · TensorFlow · Scikit-Learn · OpenCV

</div>

<div style="background: #0d1117; padding: 15px; border-radius: 8px; border-top: 2px solid #79c0ff;">

**Data & Visualization**  
NumPy · Pandas · Matplotlib · Seaborn · Plotly

</div>

<div style="background: #0d1117; padding: 15px; border-radius: 8px; border-top: 2px solid #79c0ff;">

**Embedded & Hardware**  
Arduino · ESP32 · Raspberry Pi · MPU6050 · Real-Time Systems

</div>

<div style="background: #0d1117; padding: 15px; border-radius: 8px; border-top: 2px solid #ff79c0;">

**Production & Deployment**  
ONNX · TorchScript · FastAPI · Docker · Streamlit

</div>

<div style="background: #0d1117; padding: 15px; border-radius: 8px; border-top: 2px solid #ff79c0;">

**Frontend**  
React · TypeScript · TailwindCSS · Modern Web Stack

</div>

</div>

---

## 📚 Currently Exploring

<svg width="100%" height="80" viewBox="0 0 800 80" xmlns="http://www.w3.org/2000/svg" style="margin: 20px 0;">
  <defs>
    <style>
      @keyframes float {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-5px); }
      }
      .explore-box {
        animation: float 3s ease-in-out infinite;
      }
    </style>
  </defs>
  
  <g class="explore-box" style="animation-delay: 0s;">
    <rect x="20" y="10" width="140" height="60" rx="4" fill="#0d1117" stroke="#58a6ff" stroke-width="1.5" />
    <text x="90" y="45" text-anchor="middle" fill="#58a6ff" font-size="12" font-weight="bold">CNNs · RNNs</text>
  </g>
  
  <g class="explore-box" style="animation-delay: 0.3s;">
    <rect x="190" y="10" width="140" height="60" rx="4" fill="#0d1117" stroke="#79c0ff" stroke-width="1.5" />
    <text x="260" y="45" text-anchor="middle" fill="#79c0ff" font-size="12" font-weight="bold">Transformers</text>
  </g>
  
  <g class="explore-box" style="animation-delay: 0.6s;">
    <rect x="360" y="10" width="140" height="60" rx="4" fill="#0d1117" stroke="#ff79c0" stroke-width="1.5" />
    <text x="430" y="45" text-anchor="middle" fill="#ff79c0" font-size="12" font-weight="bold">Model Deploy</text>
  </g>
  
  <g class="explore-box" style="animation-delay: 0.9s;">
    <rect x="530" y="10" width="140" height="60" rx="4" fill="#0d1117" stroke="#58a6ff" stroke-width="1.5" />
    <text x="600" y="45" text-anchor="middle" fill="#58a6ff" font-size="12" font-weight="bold">Optimal Control</text>
  </g>
  
  <g class="explore-box" style="animation-delay: 1.2s;">
    <rect x="700" y="10" width="80" height="60" rx="4" fill="#0d1117" stroke="#79c0ff" stroke-width="1.5" />
    <text x="740" y="45" text-anchor="middle" fill="#79c0ff" font-size="12" font-weight="bold">Robotics</text>
  </g>
</svg>

---

## Let's Connect

<div align="center">

🎯 **Actively seeking:** Internships in AI/ML, Robotics, and Autonomous Systems  

If you're building at the frontier—let's talk.

**[LinkedIn](https://www.linkedin.com/in/sagnick-paul-9aa30a352/)** · **[Email](mailto:sp.professional2005@gmail.com)** · **[GitHub](https://github.com/Sagnick-Paul)**

</div>

---

<div align="center">

*"The best control system makes complexity invisible."*

</div>

# Sagnick Paul

**ML Engineer | Control Systems | Autonomous Systems**  
*Building intelligent systems that perceive, decide, and act.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sagnick-paul-9aa30a352/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sp.professional2005@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Sagnick-Paul)

---

## Overview

Electrical Engineering graduate from **Jadavpur University** with a focus on deep learning, control systems, and embedded hardware. I specialize in end-to-end intelligent systems — from sensor fusion on microcontrollers to production-grade ML pipelines. Experience spans **computer vision, anomaly detection, real-time control**, and deployment on constrained hardware.

**Open to:** ML Engineer, AI/ML internships, Robotics, Autonomous Systems roles.

---

## 🎯 Core Competencies

| Category | Skills |
|----------|--------|
| **Deep Learning** | PyTorch, TensorFlow, CNN architectures, RNNs, Autoencoders, Transfer Learning |
| **Computer Vision** | Image segmentation, object detection, feature extraction (PCA, SIFT), anomaly detection |
| **Control Systems** | PID control, real-time stabilization, sensor fusion, embedded systems |
| **ML Infrastructure** | Data preprocessing, augmentation, hyperparameter tuning, evaluation metrics (Dice, IoU, mAP) |
| **Languages** | Python, C, Java |
| **Tools & Frameworks** | PyTorch, TensorFlow, OpenCV, Scikit-Learn, NumPy, Pandas, Git, Docker (learning) |
| **Hardware** | Arduino, ESP32, MPU6050, L298N motor drivers, real-time systems |

---

## 💼 Featured Projects

### 🚀 [Jet Image Classification & Anomaly Detection](https://github.com/Sagnick-Paul/jet-image-classification)
*Deep learning applied to high-energy physics*

**Problem:** Classify jet images from collision data and detect anomalies in particle physics simulations.

**Solution:**
- Built a **custom CNN classifier** with architecture optimization for jet image recognition
- Implemented **CNN Autoencoder** for unsupervised anomaly detection using reconstruction-error thresholding
- Conducted comparative study: **CNN feature extraction (92.4% accuracy)** vs **PCA-based approach (78.1% accuracy)**
- Ablation studies on batch normalization and dropout impact on generalization

**Technical Highlights:**
- Achieved **5.2x speedup** in inference through model quantization (PyTorch → ONNX)
- Implemented custom data pipeline with augmentation (rotation, noise injection)
- Evaluated on test set with precision, recall, F1-score; confusion matrix analysis
- Full reproducibility: seed management, hyperparameter logging

**Stack:** `PyTorch` `CNN` `Autoencoders` `Scikit-Learn` `Matplotlib`  
**Repo:** [See code with full documentation](https://github.com/Sagnick-Paul/jet-image-classification)

---

### 🧠 [Brain MRI Tumor Segmentation](https://github.com/Sagnick-Paul/brain-mri-segmentation)
*Computer vision for medical imaging*

**Problem:** Localize and segment brain tumors in MRI scans with clinical-grade accuracy.

**Solution:**
- End-to-end **semantic segmentation pipeline**: preprocessing → augmentation → model inference → post-processing
- Implemented **U-Net architecture** with residual connections for dense predictions
- Robust handling of class imbalance using **weighted Dice loss**
- Rigorous evaluation: **Dice Coefficient (0.87)**, **IoU (0.81)**, and per-class performance metrics

**Technical Highlights:**
- **Domain-specific preprocessing:** skull stripping, intensity normalization (z-score), histogram equalization
- **Data augmentation strategy:** random rotations, elastic deformations, intensity shifts (clinically aware)
- Modular architecture: easy backbone swapping (ResNet50, EfficientNet-B4)
- Inference optimization: sliding window strategy for memory-constrained environments
- Validation on held-out test set with statistical significance testing (Wilcoxon signed-rank)

**Stack:** `PyTorch` `U-Net` `Medical Imaging` `OpenCV` `NumPy`  
**Repo:** [See code with full documentation](https://github.com/Sagnick-Paul/brain-mri-segmentation)

---

### 🎵 [Music Listening Behavior: Cohort Analysis & Retention Modeling](https://github.com/Sagnick-Paul/music-cohort-analysis)
*Data-driven behavioral intelligence*

**Problem:** Segment users by listening patterns to identify retention cohorts and predict churn.

**Solution:**
- Applied **K-means clustering** on behavioral features (song skips, repeat rate, session duration)
- Built **temporal retention model**: tracked cohort survival rates over 12-week periods
- Generated actionable insights: identified high-churn demographics with **78% prediction accuracy**
- Produced visualizations: cohort retention curves, feature importance plots, demographic breakdowns

**Technical Highlights:**
- Feature engineering: interaction metrics, temporal aggregations, rolling averages
- Elbow method + silhouette analysis for optimal cluster selection (k=5)
- Time-series analysis of listening trends with moving averages
- Business impact: recommendations for targeted retention campaigns

**Stack:** `Python` `Scikit-Learn` `Pandas` `Matplotlib` `Seaborn`  
**Repo:** [See code with full documentation](https://github.com/Sagnick-Paul/music-cohort-analysis)

---

### 🤖 [Self-Balancing Robot: Real-Time Control on Embedded Hardware](https://github.com/Sagnick-Paul/self-balancing-robot)
*Production-grade embedded control system*

**Problem:** Stabilize an inverted pendulum robot in real-time on constrained hardware using sensor fusion.

**Solution:**
- **Full hardware-software stack:** Arduino Mega, MPU6050 (6-DOF IMU), L298N H-bridge, custom chassis
- Implemented **complementary filter** for sensor fusion: gyroscope + accelerometer (drift compensation)
- Tuned **cascade PID controller** with separate loops for angle and angular velocity
- Achieved stable operation on slopes (up to 15°) and uneven terrain with <50ms response time

**Technical Highlights:**
- **Sensor fusion algorithm:** complementary filter with alpha=0.98 for angle estimation
- **PID tuning:** manual Ziegler-Nichols method, then empirical refinement on hardware
- **Real-time constraints:** interrupt-driven sensor reading (100 Hz), control loop at 50 Hz
- **Bluetooth module integration:** live parameter adjustment (Kp, Ki, Kd) via Android app
- **Robustness testing:** verified stable operation on slopes, carpet, wood, concrete surfaces
- **Power analysis:** measured draw, optimized for battery runtime (~45 min continuous)

**Performance Metrics:**
- **Angle stability:** ±2° within 200ms of perturbation
- **Response time:** <50ms from sensor read to motor command
- **Operating range:** slopes up to 15°, ambient temperature 5–40°C
- **Battery life:** 45 minutes continuous operation on 2S LiPo

**Stack:** `C/Arduino` `MPU6050` `PID Control` `Sensor Fusion` `Real-Time Systems`  
**Repo:** [See code with full documentation](https://github.com/Sagnick-Paul/self-balancing-robot)

---

## 📊 Key Achievements

- ✅ **Comparative ML Study:** Published analysis comparing CNN vs PCA feature extraction; 5.2x accuracy improvement
- ✅ **Model Optimization:** Achieved 5.2x inference speedup through quantization and pruning
- ✅ **Real-Time Systems:** Implemented stable control on embedded hardware with <50ms latency
- ✅ **Medical Imaging:** Built segmentation pipeline with clinical-grade metrics (Dice 0.87, IoU 0.81)
- ✅ **Data Science:** Developed retention prediction model with 78% accuracy on real behavioral data
- ✅ **Full-Stack Development:** Hardware selection → firmware → real-time control → live parameter tuning

---

## 🛠️ Technical Deep Dives

### Model Architecture & Design Choices
- **Why U-Net for segmentation?** Dense prediction capability + skip connections preserve spatial detail. Evaluated against FCN (lower Dice) and SegNet (similar performance, 2.1x parameters).
- **CNN vs PCA for jet classification?** CNNs learn hierarchical features (edges → textures → objects); PCA assumes linear separability. Trade-off: CNN requires more data but generalizes better.
- **Complementary filter over Kalman?** Complementary filter: low computational cost, sufficient for inverted pendulum stabilization. Kalman would add 15ms latency; not needed for our control frequency.

### Handling Real-World Constraints
- **Class imbalance in medical imaging:** Weighted Dice loss (weight tumor class 3.5x) vs standard cross-entropy. Measured impact: recall improved from 0.72 → 0.89.
- **Limited training data (MRI scans):** Aggressive augmentation (elastic deformations, rotation, intensity shift). Data augmentation alone improved generalization by ~6% on test set.
- **Memory constraints on embedded systems:** Sliding window inference for large images. Batch normalization disabled at inference time. Model quantization (FP32 → INT8) with <1% accuracy loss.

### Production Readiness
- **Reproducibility:** Fixed seeds, hyperparameter logging, train/val/test split documentation
- **Evaluation rigor:** Not just accuracy — precision, recall, F1, confusion matrices, per-class metrics
- **Statistical significance:** Confidence intervals, cross-validation, held-out test sets
- **Code quality:** Modular design, clear variable names, inline documentation

---

## 📈 GitHub Stats

```
Languages: Python (45%) | C (25%) | Java (15%) | Other (15%)
Contributions: Consistent activity, focused on personal ML projects
Repos: Well-documented, clean commit history, ablation studies included
```

---

## 🎓 Education

**Bachelor of Engineering (B.E.) in Electrical Engineering**  
*Jadavpur University, Kolkata, India*

**Relevant Coursework:**
- Control Systems & Signal Processing
- Digital Electronics & Microprocessors
- Machine Learning & Deep Learning (self-taught, advanced)
- Linear Algebra, Probability & Statistics

---

## 🚀 Currently Exploring

| Domain | Focus |
|--------|-------|
| 🧠 **Advanced Deep Learning** | Transformers, Attention mechanisms, Vision Transformers (ViTs) |
| 🎯 **Model Deployment** | ONNX optimization, TorchScript, inference servers (TensorRT, TVM) |
| ⚙️ **Advanced Control** | Model Predictive Control (MPC), adaptive systems, learning-based control |
| 🤖 **Robotics Pipeline** | SLAM (ORB-SLAM), motion planning, end-to-end learning for navigation |
| 📦 **MLOps** | Feature stores, experiment tracking (MLflow), CI/CD for ML systems |

---

## 💡 Philosophy

> *"The best intelligent system is one that handles complexity gracefully — whether that's in perception, decision-making, or control. Elegance comes from understanding trade-offs and making principled choices."*

I believe in:
- **Rigor over flashiness:** Quantified results, statistical testing, ablation studies
- **Systems thinking:** Understanding failure modes, constraints, and real-world requirements
- **Learning from first principles:** Why does this work? What breaks? How would I redesign it?
- **Clean, reproducible code:** Documentation, modular design, no magic numbers

---

## 🤝 Let's Connect

I'm actively looking for opportunities to work on challenging problems in **ML systems, robotics, and autonomous systems**. If you're building something interesting — I'd love to discuss.

📧 **Email:** [sp.professional2005@gmail.com](mailto:sp.professional2005@gmail.com)  
🔗 **LinkedIn:** [sagnick-paul-9aa30a352](https://www.linkedin.com/in/sagnick-paul-9aa30a352/)  
💻 **GitHub:** [@Sagnick-Paul](https://github.com/Sagnick-Paul)

---

<div align="center">

*Last updated: May 2026 | Open to opportunities*

</div>

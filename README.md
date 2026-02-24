<div align="center">

# 🔥 Fire Detection using YOLO

```
███████╗██╗██████╗ ███████╗    ██╗
██╔════╝██║██╔══██╗██╔════╝    ██║
█████╗  ██║██████╔╝█████╗      ██║
██╔══╝  ██║██╔══██╗██╔══╝      ╚═╝
██║     ██║██║  ██║███████╗    ██╗
╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝    ╚═╝
  Detect it. Before it destroys it.
```

![YOLO](https://img.shields.io/badge/YOLO-Ultralytics-FF4500?style=for-the-badge&logo=pytorch)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Vision-red?style=for-the-badge&logo=opencv)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge&logo=pytorch)
![Status](https://img.shields.io/badge/Status-🔥%20Blazing-orange?style=for-the-badge)

> *"By the time smoke detectors beep — this model has already seen the fire. 👁️🔥"*

</div>

---

## ⚠️ The Problem

Every **3.4 minutes**, a fire breaks out somewhere in the world.  
Every **88 seconds**, a fire department responds to a structural fire.  
Traditional smoke/heat sensors? **Slow. Limited. Unreliable in open spaces.**

**What if your cameras could see fire the moment it sparks?**

That's exactly what this project does. 🎯

---

## 🧠 What is This?

An intelligent **computer vision–based fire detection system** powered by **YOLO (You Only Look Once)** — one of the fastest object detection architectures in the world.

Instead of waiting for smoke to reach a sensor, this system **looks at the scene visually**, processes it through a deep learning model, and flags fire **in real time** — making it ideal for surveillance, industrial safety, and smart city infrastructure.

---

## ✨ Key Highlights

| Feature | Details |
|--------|---------|
| ⚡ **Speed** | Real-time detection with YOLO's single-pass inference |
| 🧠 **Intelligence** | Deep learning trained on custom fire/non-fire scenarios |
| 📉 **Low False Positives** | Multiple training iterations to fine-tune accuracy |
| 🌍 **Versatile** | Works on images — extensible to video & live streams |
| 🔬 **Experimental** | Multiple notebook versions documenting R&D process |

---

## 🛠️ Tech Stack

```python
tech_stack = {
    "Language"   : "Python 3.x",
    "Framework"  : "YOLO via Ultralytics",
    "ML Backend" : "PyTorch",
    "Vision"     : "OpenCV",
    "Numerics"   : "NumPy",
    "Environment": "venv + Jupyter Notebook",
    "Editor"     : "VS Code"
}
```

---

## 📁 Project Structure

```
🗂️ Fire_Detection_using_YOLO/
│
├── 🔬 Version_1_TrainingNotebook.ipynb   ← The origin story
├── 📓 TrainingNotebook.ipynb             ← Iteration 2
├── 📓 TrainingNotebook2.ipynb            ← Refined & improved
├── 📦 requirements.txt                   ← All you need to get started
├── 🚫 .gitignore                         ← Keeping things clean
└── 📄 README.md                          ← You're here!
```

> ⚠️ **Heads up:** Dataset files and trained model weights (`.pt`) are excluded from this repo due to size limits.  
> 📬 *Want the dataset or weights? Drop a message — happy to share via Drive/Kaggle!*

---

## 📊 Dataset

- 🖼️ Custom fire image dataset curated for this project
- ✅ Includes **fire** and **non-fire** scenes for balanced training
- 🔀 Split into training and evaluation sets
- 📌 Available on request via **Google Drive / Kaggle**

---

## 🧪 Model Training Journey

> Three notebooks. Three iterations. One goal — **zero fires missed.**

```
Version 1  ──►  Baseline model, initial results
     ↓
TrainingNotebook  ──►  Hyperparameter tuning, better mAP
     ↓
TrainingNotebook2  ──►  Optimized model, reduced false positives 🏆
```

Each notebook covers:
- 🧼 Data preprocessing & augmentation
- ⚙️ Model config & hyperparameter experiments
- 📈 Training loss curves & evaluation metrics
- 🔍 Performance analysis & visual results

---

## ▶️ Get It Running

### 1️⃣ Clone the repo
```bash
git clone https://github.com/KhushiKalwani24/Fire_Detection_using_YOLO.git
cd Fire_Detection_using_YOLO
```

### 2️⃣ Set up your environment
```bash
python -m venv venv
source venv/bin/activate        # 🐧 Linux / macOS
# OR
venv\Scripts\activate           # 🪟 Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Launch the notebook
```bash
jupyter notebook TrainingNotebook2.ipynb
```

🔥 *Sit back and watch the model learn to see fire.*

---

## 🎯 Real-World Applications

```
🏭  Industrial Plants       →  Instant fire alerts before explosions
🏢  Smart Buildings         →  Camera-based fire suppression triggers  
🌲  Forest Monitoring       →  Satellite/drone feed analysis
🚦  Traffic Surveillance    →  Vehicle fire detection on highways
🏠  Home Security           →  Smarter than any smoke alarm
```

---

## 🌟 What's Coming Next?

- [ ] 🎥 Real-time **video stream** detection
- [ ] 📡 Integration with **CCTV pipelines**
- [ ] 📲 **SMS / Email alert system** on fire detection
- [ ] 🌐 Web dashboard using **Flask / FastAPI**
- [ ] 🤖 Edge deployment on **Jetson Nano / Raspberry Pi**
- [ ] ☁️ Cloud deployment for remote monitoring

---

## 📈 Performance Snapshot

> *Results improve across notebook versions — track the journey in the notebooks!*

| Metric | Description |
|--------|-------------|
| 🎯 mAP | Mean Average Precision across fire class |
| 📉 Loss | Box + Object + Class loss tracked per epoch |
| ⚡ Speed | Inference time per image (ms) |
| 🚫 FP Rate | False positive reduction across versions |

---

## 👩‍💻 Author

<div align="center">

### Khushi Kalwani

*On a mission to make the world a little safer — one model at a time.* 🌍

[![GitHub](https://img.shields.io/badge/GitHub-@KhushiKalwani24-black?style=for-the-badge&logo=github)](https://github.com/KhushiKalwani24)

</div>

---

## ⭐ Like This Project?

If this sparked something in you *(pun intended 🔥)*, leave a **star** ⭐ on the repo!  
It keeps the motivation burning. 🕯️

---

<div align="center">

```
🔥 "The best fire alarm is the one that never goes off — because it stopped it first." 🔥
```

*Built with Python, PyTorch, and a burning passion for AI safety.*

</div>

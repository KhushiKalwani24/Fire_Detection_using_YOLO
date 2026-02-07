# 🔥 Fire Detection using YOLO

An intelligent **computer vision–based fire detection system** built using the **YOLO (You Only Look Once)** object detection framework.  
This project focuses on detecting fire in images with high accuracy and real-time performance, making it suitable for **early fire warning systems** and **surveillance applications**.

---

## 🚀 Project Overview

Fire accidents cause massive damage when not detected early. Traditional fire detection systems rely on sensors that may fail in open or large environments.  
This project leverages **deep learning and computer vision** to visually detect fire using images, enabling faster and more reliable detection.

**Key highlights:**
- 🔍 Real-time fire detection using YOLO
- 🧠 Deep learning–based approach
- ⚡ Fast and scalable object detection
- 📊 Trained and evaluated on a custom fire dataset

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Framework:** YOLO (Ultralytics)  
- **Libraries:** PyTorch, OpenCV, NumPy  
- **Tools:** Jupyter Notebook, VS Code  
- **Environment:** Virtual Environment (venv)

---

## 📁 Project Structure

Fire_Detection_using_YOLO/
│
├── TrainingNotebook.ipynb
├── TrainingNotebook2.ipynb
├── Version_1_TrainingNotebook.ipynb
├── requirements.txt
├── .gitignore
└── README.md

yaml
Copy code

> ⚠️ **Note:**  
> Dataset files and trained model weights (`.pt`) are intentionally excluded from the repository due to size constraints and GitHub best practices.

---

## 📊 Dataset

- Custom fire image dataset
- Includes images with fire and non-fire scenarios
- Dataset used only for training and evaluation

📌 *Dataset can be provided upon request or via external storage (Google Drive / Kaggle).*

---

## 🧪 Model Training

The YOLO model was trained using multiple experimental notebooks to:
- Tune hyperparameters
- Improve detection accuracy
- Reduce false positives

Training notebooks document:
- Data preprocessing
- Model training
- Evaluation metrics
- Performance analysis

---

## ▶️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KhushiKalwani24/Fire_Detection_using_YOLO.git
cd Fire_Detection_using_YOLO
2️⃣ Create virtual environment
bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Run notebooks
Open Jupyter Notebook and execute the training or inference notebooks.

🎯 Applications
🔥 Early fire detection systems

🏭 Industrial safety monitoring

🏢 Smart buildings & surveillance

🌲 Forest fire monitoring

🌟 Future Enhancements
Real-time video stream detection

Integration with CCTV systems

Alert system (email/SMS)

Deployment using Flask / FastAPI

Edge deployment using Jetson or Raspberry Pi

👩‍💻 Author
Khushi Kalwani

GitHub: @KhushiKalwani24

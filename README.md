# Anomaly Detection on NSL-KDD Dataset using Diffusion Model

- Built a diffusion model for anomaly detection on NSL-KDD dataset (a well known benchmark for network intrusion detection) . 
- The noising and denoising process of diffusion is entirely custom and no third party diffusion library is used.

---

##  Project Highlights
- Built a custom deep diffusion model from scratch for detecting anomalies in network traffic data.
- Developed a complete preprocessing pipeline including encoding, scaling, and binary labeling.
- Optimized denoising diffusion probabilistic modeling (DDPM) for discrete, high-dimensional cybersecurity data representations.
- Applied advanced anomaly detection techniques to the NSL-KDD dataset, simulating real-world network security scenarios.
- Conducted multi-metric evaluation including ROC-AUC, precision-recall tradeoff, and interpretability-driven visualization of anomaly scores.

---

##  Dataset

🔗 Official Dataset Page: **https://www.kaggle.com/datasets/hassan06/nslkdd**  
   After download, place the dataset files into the `data/` directory.

---

##  Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/deep-diffusion-anomaly-detection-nslkdd.git
cd deep-diffusion-anomaly-detection-nslkdd
```

### 2. Install required packages
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
Launch Jupyter and open:
```bash
jupyter notebook NSL_VER2_2_mark2.ipynb
```

---

##  Model Evaluation

- **Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC
- **Outputs:** Confusion matrix, anomaly score plots, visualizations, diffusion model

---

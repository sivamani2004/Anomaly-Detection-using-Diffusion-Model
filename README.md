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


##  Model Evaluation

- **Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC
- **Outputs:** Confusion matrix, anomaly score plots, visualizations, diffusion model

## Results 

- Compared the diffusion model against other benchmark models like autoencoder, PCA, and Isolation Forest.
- Achieved F1-score of 0.887, outperforming PCA and Isolation Forest while performing comparably to an Autoencoder despite being an unsupervised model.

---

# paper-implementation
Reimplementation of research paper and comparison with official implementation
# MobileNet Implementation from Scratch

## 📌 Paper
MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications  
Howard et al.

## 📖 Objective
To implement MobileNet from scratch and compare its performance with a standard CNN baseline.

---

## ⚙️ Implementation Details
- Dataset: CIFAR-10
- Input size: 224 × 224
- Framework: PyTorch (Google Colab)
- Models implemented:
  - Baseline CNN (standard convolution)
  - MobileNet (depthwise separable convolution)

---

## 📊 Results

| Model | Accuracy | Parameters |
|------|---------|------------|
| Baseline CNN | 56.46% | 25.7 Million |
| MobileNet | 77.24% | 3.2 Million |

---

## 🔍 Observations
- MobileNet significantly outperforms the baseline CNN.
- Achieves higher accuracy with ~8× fewer parameters.
- Demonstrates efficiency of depthwise separable convolutions.

---

## 🚀 Conclusion
MobileNet provides an excellent trade-off between accuracy and computational efficiency.  
This experiment validates the claims made in the original paper.

---
---

## 📂 Repository Structure

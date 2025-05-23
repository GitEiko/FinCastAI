# 🔮 FinCastAI – Time-Series Forecasting in Finance Using Transformer Models

![GitHub Repo stars](https://img.shields.io/github/stars/GitEiko/FinCastAI?style=social)
![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-🔥-red)
![License](https://img.shields.io/github/license/GitEiko/FinCastAI)

## 💡 Overview

**FinCastAI** is a cutting-edge project that applies **Transformer-based AI models** to financial time-series forecasting. By leveraging self-attention mechanisms, this model aims to outperform traditional methods (ARIMA, LSTM) in **accuracy, scalability, and adaptability** — particularly in volatile markets.

This work was developed as my final year project for the **BSc in Computer Science (Engineering Pathway)** at Queen Mary University of London, supervised by Dr. Raul Mondragon.

## 🚀 Highlights

- 📈 **Accurate mid-range predictions** (24–50 days) with low error rates
- ⚡ **Outperforms** traditional models (ARIMA, LSTM) in both accuracy and efficiency
- 🧠 Built using **PyTorch Forecasting** for modern deep learning workflows
- 💾 Real financial data fetched from `yFinance`
- 📊 Model evaluation with MAE, RMSE, and MAPE metrics

## 📊 Results Snapshot

| Prediction Horizon | MAE   | RMSE  | MAPE     | Verdict       |
|--------------------|-------|-------|----------|---------------|
| 6 Days             | 1.13  | 1.14  | 0.00590  | ✅ Excellent   |
| 12 Days            | 1.07  | 1.19  | 0.00552  | ✅ Excellent   |
| 40 Days            | 1.09  | 1.41  | 0.00574  | ✅ Very Good   |
| 80 Days            | 15.1  | 17.7  | 0.0860   | ❌ Not Reliable|

✅ **Best performance window:** 6–40 days  
🧪 Benchmarked against real-world financial market shifts

## 🧠 Why Transformers?

Traditional models struggle with:
- Linear assumptions (ARIMA)
- Vanishing gradients (LSTM)
- Resource intensiveness

**Transformer models** bring:
- 🔄 Long-range dependency tracking
- 🔎 Self-attention for fine-grained insight
- 🚀 Faster training with parallelism

## 📦 Tech Stack

- Python 3.9+
- PyTorch Forecasting
- yFinance
- NumPy, Pandas, Matplotlib, Seaborn

## 🔧 How to Run

🎉 No Python installation or dependency setup required — everything is bundled in a standalone executable!

### ✅ Steps:

1. **Download the executable** from the [Releases](https://github.com/GitEiko/FinCastAI/releases) section.
2. **Run it:**
   - **Windows:** Double-click `FinCastAI.exe`
   - **Linux/macOS:**
     ```bash
     chmod +x FinCastAI
     ./FinCastAI
     ```

3. Follow the on-screen instructions to run predictions or explore results.

### ⚙️ Notes:
- All dependencies are included — no need to install anything else.
- Built and tested for **Windows 10/11**.
- Want a version for **macOS or Linux**? Open an issue or message me!

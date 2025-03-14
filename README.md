# TraderBot

**TraderBot** is an AI-driven trading bot that analyzes the **sentiment of live news events** to make trading decisions in real-time. This project leverages **natural language processing (NLP) and algorithmic trading** to execute trades based on financial news sentiment analysis.

## 🚀 Getting Started

### 1️⃣ Setup Virtual Environment
```bash
conda create -n trader python=3.10
conda activate trader
```

### 2️⃣ Install Dependencies
```bash
pip install lumibot timedelta alpaca-trade-api==3.1.1
pip install torch torchvision torchaudio transformers
```

### 3️⃣ Configure API Keys
- Update `API_KEY` and `API_SECRET` with your **Alpaca Trading API credentials**.

### 4️⃣ Run the Trading Bot
```bash
python tradingbot.py
```

---
## ⚠️ Troubleshooting SSL Errors
If you encounter SSL errors while connecting to Alpaca:
1. Download the required intermediate SSL certificates:
   - [Let's Encrypt R3](https://letsencrypt.org/certs/lets-encrypt-r3.pem)
   - [ISRG Root X1 Cross Signed](https://letsencrypt.org/certs/isrg-root-x1-cross-signed.pem)
2. Rename the files to `.cer`.
3. Install the certificates by double-clicking and following the setup wizard.

---
## 🔗 Other References
- [Lumibot](https://github.com/Lumiwealth/lumibot): A trading bot library that simplifies algorithmic trading lifecycle management.

---
## 👤 Author & License
👨🏾‍💻 Author: **Ngonidzashe Maposa**  
📅 Version: **1.x**  
📜 License: **MIT License**  

This project was modified from a forked repository to enhance **sentiment-based trading strategies** and **optimize trade execution using NLP techniques**. 🚀

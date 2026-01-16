# 🤖 AI Prompt Injection Detector

A lightweight Python tool that detects potentially malicious **prompt injections** in AI input text.  
It checks if the user’s prompt tries to bypass restrictions or reveal confidential information.  
If found, it flags the prompt as **“Suspicious”** or **“Safe”**.

---

## ✨ Features
- Detects risky and manipulative prompt patterns.
- Helps safeguard AI systems from jailbreak or override attempts.
- Simple and easy-to-customize code.

---

## 🛠️ Installation

```bash
pip install nltk

---
🚀 How It Works

The tool uses regex to scan for phrases that might indicate prompt injection.

If such patterns are found, it flags the input as suspicious.

Otherwise, it marks it safe.

📚 Future Improvements

Integrate with OpenAI API for real-time scanning.

Add a larger dataset of known risky patterns.

Support for multilingual prompt analysis.

🧠 Author

Created with ❤️ by Prardhana


🪪 License

This project is licensed under the MIT License.


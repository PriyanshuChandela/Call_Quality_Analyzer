# 📞 Call Quality Analyzer

This project analyzes call transcripts and provides insights on:
- **Talk-time ratio** between speakers
- **Number of questions asked**
- **Longest monologue duration**
- **Overall sentiment analysis**
- **Actionable insights** for better communication

## 🚀 Features
- Uses **Transformers (DistilBERT)** for sentiment analysis.
- Built with **Python & Google Colab**.
- Simple to use and extend.

## 🛠️ How to Run
1. Open the project in **Google Colab**.
2. Upload your conversation transcript or run the provided notebook.
3. Get instant insights on call quality.

## 📂 Project Structure
- `Call_Quality_Analyzer.ipynb` → Main notebook with code.
- `README.md` → Project documentation (you’re reading it).

## 💡 Example Output
```json
{
  "Talk-time ratio": {"Speaker A": 51.54, "Speaker B": 48.46},
  "Questions asked": 8,
  "Longest monologue (sec)": 10.0,
  "Overall Sentiment": {"label": "POSITIVE", "score": 0.99},
  "Actionable Insight": "Good balance, but focus on building rapport."
}

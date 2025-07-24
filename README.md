# 📰 Bias Buster: Identifying Obfuscating Language in News Headlines

This project uses AI to detect and rewrite biased news headlines by analyzing language patterns such as passive voice, vague agency, and euphemisms. It allows users to input either a headline or a URL to a news article. The tool then outputs bias tags, an estimated bias score, and a rewritten, objective version of the headline using OpenRouter’s GPT-3.5 model.

---

## 🧠 Project Goals
- Detect bias in news headlines and article titles using rule-based heuristics.
- Estimate a bias score from 0–100 based on detected bias types.
- Rewrite biased headlines using GPT-based AI.
- Help promote accountability and transparency in media language.

  ---

## 📁 Files
`Project2_AIFHG_BiasBuster.ipynb`: Main Google Colab notebook with input prompts, detection logic, API integration, and results.

📌 Input Options
- **Headline**: Paste any news headline for analysis and rewriting.
- **URL**: Paste a news article link. The script extracts the title for bias analysis.

  ---

## 🛠 Tools & Technologies
- Google Colab (Python)
- OpenRouter GPT API (for AI rewrites)
- Regular Expressions + Heuristics (for bias detection)
- `newspaper3k` (for article title extraction)
- `requests` (for API communication)

---

## 🚀 How to Use
Open the notebook in Google Colab:

📂 [Open in Colab](https://colab.research.google.com/drive/1IXnMGqb5XxOeG8HOPSQtuPOwhAraRcdu?usp=sharing)

1. Paste your OpenRouter API key when prompted.
2. Choose either Headline or URL mode.
3. Paste your input.
4. View bias tags, score, and rewritten headline.

---

## 💡 Output
- 🔖 Detected Bias Tags: e.g., “Vague agency / Passive voice”
- 📊 Bias Score: A number from 0 (neutral) to 100 (extremely biased)
- 📝 Rewritten Headline: AI-generated neutral alternative

  ---

## 📜 License
This project is open-source and available for educational, research, and humanitarian use. Feel free to fork, adapt, or build upon it with attribution.

---

Created by Ayah Jaber | @ayahjaber7

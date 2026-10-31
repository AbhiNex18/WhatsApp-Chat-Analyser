# 📊 WhatsApp Chat Analyzer

A Python-based WhatsApp Chat Analyzer that transforms exported WhatsApp conversations into meaningful insights and interactive visualizations. Analyze chat activity, user engagement, messaging patterns, and communication trends through an easy-to-use Streamlit dashboard.

## 🚀 Project Overview

WhatsApp Chat Analyzer is a data analytics project built using Python and Streamlit. It processes exported WhatsApp chat files and provides useful insights into conversations through data preprocessing, statistical analysis, and interactive visualizations.

Whether you want to analyze personal conversations or understand group activity, this tool makes chat analysis simple and interactive.

## ✨ Features

- **Chat Statistics:** Analyze total messages, words, media shared, and links.
- **User Analysis:** Identify the most active participants in group conversations.
- **Timeline Analysis:** Understand messaging trends over days, months, and years.
- **Activity Analysis:** Explore the most active days and months.
- **Word Analysis:** Discover frequently used words in conversations.
- **Emoji Analysis:** Analyze emoji usage and frequency.
- **Interactive Visualizations:** Explore insights through charts and graphs.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Interactive web application |
| Pandas | Data manipulation and analysis |
| Matplotlib / Seaborn | Data visualization |
| Plotly | Interactive charts |

## 📂 Project Structure

```text
WhatsApp-Chat-Analyser/
│
├── .streamlit/
│
├── app.py              # Main Streamlit application
├── backend.py          # Data analysis and visualization
├── preprocessor.py     # Chat data preprocessing
├── stop_hinglish.txt   # Hinglish stop words
├── requirements.txt    # Project dependencies
├── .gitignore
│
└── README.md
```

## ⚙️ Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/AbhiNex18/WhatsApp-Chat-Analyser.git
```

**2. Navigate to the project directory**

```bash
cd WhatsApp-Chat-Analyser
```

**3. Create a virtual environment (Optional)**

```bash
python -m venv venv
```

Activate it:

```bash
# Windows
venv\Scripts\activate
```

**4. Install dependencies**

```bash
pip install -r requirements.txt
```

**5. Run the application**

```bash
streamlit run app.py
```

The application will open in your browser.

## 📱 How to Use

1. Open WhatsApp.
2. Select the conversation or group you want to analyze.
3. Export the chat without media in `.txt` format.
4. Open the WhatsApp Chat Analyzer application.
5. Upload the exported chat file.
6. Select a user or analyze the complete group.
7. Explore the generated statistics and visualizations.

## 🎯 Learning Outcomes

Through this project, I explored:

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Text processing and analysis.
- Data visualization.
- Building interactive applications using Streamlit.
- Extracting meaningful insights from unstructured text data.

## 👨‍💻 Author

**Abhinav Rai**

- GitHub: [@AbhiNex18](https://github.com/AbhiNex18)

---

⭐ If you find this project interesting, consider giving it a star!

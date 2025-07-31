# 📊 WhatsApp Chat Analysis Dashboard

A **Streamlit-based web app** to analyze and visualize your **WhatsApp chat data** with real-time insights into message trends, user activity, emoji usage, and more. Built using **Python, Pandas, NLP, and Matplotlib**, with support for **Hinglish stopword filtering** and multilingual parsing.

---

## 🚀 Features

- 📁 Upload raw `.txt` chat files directly from WhatsApp export
- 🧹 Preprocess chats to remove system messages, media info, and group events
- 📊 Visualize:
  - Total messages, word counts, media shares, and links
  - Most active users and timelines
  - Word clouds with stopword filtering
  - Emoji usage and frequency plots
- 🧠 Hinglish + English stopword removal using `stop_hinglish.txt`
- 📈 Built with `Streamlit` for fast UI and analysis
- ☁️ Fully deployable on Heroku using `Procfile` and `setup.sh`

---

## 🧰 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, Regex
- **Deployment**: Heroku

---

## 📂 Project Structure


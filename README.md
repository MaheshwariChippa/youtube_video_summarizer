# 🎥 YouTube Video Summarizer Using AI 🤖

This project is a web application that allows users to enter a YouTube video URL and get a concise, AI-generated summary of the video content using Google Gemini AI. It automates transcript extraction and summarization, saving time and improving content accessibility.

---

## 📌 Features

- 🎯 Fetches transcripts from YouTube videos
- 🤖 Summarizes video content using Google Gemini AI (Gemini Pro)
- 💻 User-friendly web interface built with Streamlit
- 🔐 Secure API key management using `.env` and `python-dotenv`
- 📸 Displays video thumbnail for user confirmation

---

## 🛠️ Technologies Used

- **Python** – Core programming language
- **Streamlit** – For building the web app interface
- **YouTube Transcript API** – To fetch video subtitles
- **Google Gemini AI API** – For NLP-based summarization
- **Python-dotenv** – To load environment variables securely

---

## 🚀 How It Works (Workflow)

1. User enters a YouTube video URL in the Streamlit interface.
2. The app extracts the video ID and retrieves the transcript using the YouTube Transcript API.
3. The transcript is passed to Google Gemini AI with a predefined summarization prompt.
4. The AI returns a concise summary, which is displayed on the web app.

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add your Google API key:

```env
GOOGLE_API_KEY=your_google_api_key_here

# 🎥 YouTube Clone (React.js + YouTube Data API v3)

YouTube Clone LINK:YouTube Clone:https://youtubeclonejey.netlify.app/login

A modern YouTube clone built with **React.js** that uses the official [YouTube Data API v3](https://developers.google.com/youtube/v3) to fetch and display videos, search content, view video details, and more.

---

## 🚀 Features

- 🔍 Search for videos using YouTube API
- 🎬 Display trending or related videos
- 🧠 View video details (title, channel, views, date)
- 📺 Watch embedded YouTube videos
- 🌙 Dark/light mode toggle (optional)
- 📱 Responsive UI with clean design

---

## 🛠️ Tech Stack

- **React.js**
- **React Router DOM**
- **Axios**
- **Material UI / Tailwind CSS / CSS Modules** (choose your styling approach)
- **YouTube Data API v3**

---

## 🔑 API Key Setup

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project (or use an existing one).
3. Enable the **YouTube Data API v3**.
4. Go to **APIs & Services > Credentials**, create an API key.
5. In your project, create a `.env` file in the root and add:

```env
REACT_APP_YOUTUBE_API_KEY=your_api_key_here

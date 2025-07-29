# 🎬 Prompt2Video

**Prompt2Video** is a free, serverless web app that converts text prompts into short videos using text-to-speech (TTS) and a static background. It's built with **Next.js 13 App Router**, **Tailwind CSS**, and **Vercel Functions**.

---

## 🚀 Features

- ✅ Converts text prompts into videos using speech synthesis
- ✅ Free and serverless (runs on Vercel)
- ✅ Built with modern technologies
- ✅ Uses placeholder image as video background
- ✅ Firebase-ready (for user features and storage, optional)

---

## 🧠 How It Works

1. User enters a prompt.
2. The backend API (`/api/generate-video`) uses a **TTS API** to generate audio.
3. The audio is combined with a static image (placeholder.jpg) to simulate a video.
4. A mock video URL is returned for testing. (You can plug in FFmpeg and Firebase for real video generation later.)

---

## 📁 Project Structure


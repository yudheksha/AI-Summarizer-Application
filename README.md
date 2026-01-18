# AI Text Summarizer Application (Next.js)

A simple web app that summarizes pasted text using **Google Gemini**, with **Google Sign-In** and a **saved summary history**.

## What this project does
- Paste/type text and generate a concise summary
- Google login for authentication
- Saves summaries to Firebase so you can revisit them later
- History page with copy + delete actions
- Responsive UI (desktop + mobile friendly)

## Tech stack
- Next.js (App Router) + TypeScript
- Google Generative AI (Gemini)
- Firebase Authentication (Google provider)
- Firestore (stores summaries)
- Tailwind CSS

## Run locally
1. Install dependencies:
   ```bash
   cd aitext-sum-master
   npm install

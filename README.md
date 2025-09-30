# AI Meeting Assistant

## Overview
The **AI Meeting Assistant** is a full-featured tool designed to transform online meetings into actionable insights.  
It can process Google Meet sessions to automatically generate:

- **Full transcripts** (who said what, with timestamps)  
- **Concise meeting summaries and short notes**  
- **Action items and decisions**  
- **Screenshots** when screen content changes significantly  
- **Key insights** (keywords, topics, sentiment analysis)

This project combines **speech recognition, NLP, and computer vision** to create a professional meeting documentation and analysis assistant.

---

## Features

1. **Transcription**  
   - Real-time or post-meeting audio-to-text conversion using OpenAI Whisper.  
   - Speaker diarization for multi-participant meetings.

2. **Summarization & Notes**  
   - AI-generated short notes and action items.  
   - Categorized summaries for better organization.

3. **Screen Change Detection & Screenshots**  
   - Automatic detection of slide/document changes during screen share.  
   - Screenshots linked to relevant transcript timestamps.

4. **Insights Extraction**  
   - Keyword extraction, topic modeling, and sentiment analysis.  
   - Highlights recurring discussion points.

5. **Export & Integration**  
   - Export to PDF, DOCX, or integration with productivity tools like Notion and Google Docs.

---

## Tech Stack

- **Backend**: Python, FastAPI  
- **Frontend**: React.js + Tailwind CSS  
- **AI/NLP**: OpenAI Whisper, Hugging Face Transformers, spaCy, KeyBERT  
- **Computer Vision**: OpenCV, ffmpeg  
- **Database**: PostgreSQL / MongoDB  
- **Storage**: AWS S3 / Firebase  
- **Development Environment**: GitHub Codespaces (browser-based VS Code)

---

## Project Structure


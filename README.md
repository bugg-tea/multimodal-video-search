# 🎥 Multimodal Video Search Engine

A multimodal AI system that enables searching inside videos using **text, image, or audio queries**. User can upload the video and also can upload there query(either text, audio, image) our engine will help the user to search the query inside the uploaded video.
Example :- uploaded a video having mountains somewhere or teacher explaining ohm's law, user can ask - "mountains" or "teacher explaining ohms" , our search engine will search that part in the video and return the timestamp containing that portion.
NOTE :- app.py is actually a google collab notebook downloaded in .py form

---

## 🚀 Features

- Video chunking with temporal overlap
- Audio transcription using Whisper
- Visual captioning using BLIP
- Sentence embeddings using Sentence Transformers
- FAISS-based similarity search
- Gradio-based interactive UI
- Supports Text / Image / Audio queries

---

## 🧠 How It Works
(install requirements.txt)
1. User places video(s) inside `sample_videos/`
2. System processes video into chunks
3. Extracts:
   - Audio transcripts
   - Visual captions from frames
4. Builds multimodal embeddings
5. Searches query against audio + visual index
6. Returns:
   - Matching chunk
   - Timestamp
   - Caption / Transcript
   - Similarity score

---

## 🛠️ Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/multimodal-video-search.git
cd multimodal-video-search

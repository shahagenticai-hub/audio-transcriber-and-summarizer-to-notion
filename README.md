# Audio Transcriber and Summarizer to Notion

An automated workflow built with **n8n** that converts any audio file into a written transcript, summarizes it using AI and saves everything neatly to a **Notion** database in one go.

## How It Works
1. Audio file is received via **Webhook**
2. **Groq Whisper Large V3** model transcribes the audio into text
3. **OpenRouter AI** summarizes the full transcript into key points
4. The summary is automatically saved as a new page in **Notion** database

## Tools Used
- n8n
- Webhook
- Groq Whisper Large V3
- OpenRouter
- Notion

## Real Life Use Cases
- 🎙️ Podcasters saving episode summaries to Notion automatically
- 📋 Business meetings — record audio and get summary saved instantly
- 🎓 Students transcribing and summarizing recorded lectures
- ⚖️ Lawyers and doctors transcribing client and patient audio notes
- 📞 Sales teams summarizing recorded client calls for follow-up

## Workflow Preview
![Audio Transcriber and Summarizer to Notion](screenshot.png)

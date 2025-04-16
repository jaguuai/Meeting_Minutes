# 📝 Meeting Minutes Generator

**Meeting Minutes Generator** is a project designed to automatically transcribe meeting audio recordings into text and generate AI-powered meeting summaries and action items. The goal is to save time, simplify record-keeping, and increase meeting efficiency.

## 🔍 Project Purpose

This project aims to automate the process of writing meeting minutes. The system processes audio files and converts them into text, then extracts:

- Meeting summary  
- Participant list  
- Date and location information  
- Topics discussed  
- Decisions made and task assignments  

and other key details.

## ⚙️ Workflow

1. **Audio → Text:**  
   The meeting audio is transcribed into text using speech-to-text technology.

2. **Text → Summarization & Analysis:**  
   The transcribed content is analyzed using large language models (LLMs) to generate both a general summary and detailed key points.

3. **Minutes Generation:**  
   Summaries, action items, and participants are organized in markdown format to create the final meeting minutes.

## 🧠 Technologies and Models Used

The project utilizes both open-source and commercial LLMs:

- `LLaMA`  
- `BART`  
- `GPT-Neo`  
- (Optional) `OpenAI GPT-4`  

These models are responsible for summarization and content generation.

## 👥 Target Users

- Corporations and businesses  
- Government agencies and municipalities  
- Universities and student organizations  
- Freelancers  
- Anyone organizing or attending online meetings  

## 🌟 Features

- Fully automated meeting minutes generation  
- Support for multiple language models  
- Output in markdown format  
- Custom summaries for each user  
- Modular architecture (each step can run independently)

## 🔮 Future Improvements

- Turkish and multilingual support  
- Web-based user interface  
- Integration with task management tools (Trello, Jira, etc.)  
- Direct connection with platforms like Zoom and Google Meet  




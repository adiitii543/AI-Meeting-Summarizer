🤖 AI Meeting Summarizer

An AI-powered meeting assistant that converts meeting transcripts, documents, and audio recordings into clear and structured meeting reports.

The project uses **Llama 3.2 through Ollama** for intelligent summarization and **OpenAI Whisper** for audio transcription.

## ✨ Features

- 📝 Summarize pasted meeting transcripts
- 📄 Extract text from PDF and TXT files
- 🎙️ Transcribe meeting recordings using Whisper
- 🤖 Generate AI-powered meeting reports
- 📌 Identify key discussion points
- ✅ Extract decisions and action items
- 📅 Identify deadlines
- ⚠️ Highlight unresolved issues
- 🖥️ Simple and professional Gradio interface
- 🔒 Uses Ollama locally for LLM processing

## 🛠️ Tech Stack

- **Python**
- **Ollama**
- **Llama 3.2**
- **OpenAI Whisper**
- **Gradio**
- **PyPDF**

## 🏗️ System Workflow

```text
                ┌──────────────────┐
                │  Meeting Input   │
                └────────┬─────────┘
                         │
          ┌──────────────┼──────────────┐
          ↓              ↓              ↓
     Transcript       PDF/TXT         Audio
          │              │              │
          │        Text Extraction     Whisper
          │              │              │
          └──────────────┴──────────────┘
                         ↓
                  Meeting Transcript
                         ↓
                  Ollama + Llama 3.2
                         ↓
                Structured AI Report
                         ↓
     ┌──────────┬──────────┬──────────┐
     ↓          ↓          ↓          ↓
   Summary   Decisions  Actions   Deadlines
                         │
                         ↓
                Unresolved Issues

```

## 📊 Generated Report

The application generates the following sections:

### Meeting Summary

A concise overview of the meeting.

### Key Discussion Points

The major topics discussed during the meeting.

### Decisions Made

Important decisions explicitly mentioned in the meeting.

### Action Items

Tasks along with the responsible person and deadline when available.

### Deadlines

Dates and deadlines mentioned during the meeting.

### Unresolved Issues

Questions, problems, or decisions that remain unresolved.

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Meeting-Summarizer.git
cd AI-Meeting-Summarizer

```

### 2. Install dependencies

```bash
pip install -r requirements.txt

```

### 3. Install Ollama

Install Ollama from its official website and download the required model:

```bash
ollama pull llama3.2

```

### 4. Run the project

Open the notebook:

```text
AI_Meeting_Summarizer.ipynb

```

The project can also be executed using Google Colab.

## 📁 Project Structure

```text
AI-Meeting-Summarizer/
│
├── AI_Meeting_Summarizer.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── screenshots/
    └── app_demo.png

```

## 🎯 Use Cases

This project can be useful for:

- Student project meetings
- Team discussions
- Online meetings
- Academic discussions
- Business meetings
- Project management

## 🔮 Future Improvements

- Automatic speaker identification
- Support for more audio formats
- Multiple language transcription
- Downloadable meeting reports
- Meeting history and search
- Automatic email generation
- Calendar integration
- Cloud deployment


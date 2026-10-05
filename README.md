# 🎙️ Automatic Text Summarization with Voice Output (Text-to-Speech)

A lightweight Text-and-Speech Natural Language Processing (NLP) pipeline built with Python. This project automatically extracts the core meaning from long paragraphs of text using frequency-based NLP and converts the resulting summary into an audible voice output using Google Text-to-Speech (`gTTS`).

Designed specifically for seamless execution in **Google Colab** or any standard Python environment.

---

## 🚀 Features

* **Extractive Text Summarization:** Utilizes **spaCy** and word-frequency scoring algorithms to identify and extract the most critical sentences from a source document.
* **Text-to-Speech (TTS) Integration:** Converts the condensed summary into high-quality spoken audio using `gTTS`.
* **Cloud-Friendly (Google Colab Ready):** Bypasses local sound-driver limitations by utilizing IPython audio widgets for direct browser playback.
* **Zero Complex Setup:** Automatically installs dependencies and downloads required language models on the fly.

---

## 🛠️ Tech Stack

* **Python 3.x**
* **spaCy** (NLP Tokenization & Sentence Segmentation)
* **gTTS (Google Text-to-Speech)** (Speech Synthesis)
* **IPython Display** (Audio playback interface)

---

## 📂 Project Workflow

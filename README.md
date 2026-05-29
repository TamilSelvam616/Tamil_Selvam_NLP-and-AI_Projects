# AI-Based Smart Language Translator & Grammar Correction System

A high-performance NLP pipeline built inside Google Colab that automatically corrects broken English grammar, translates text into target languages (like Tamil), and provides real-time vocabulary insights. 

This project bypasses traditional web interface latency by running localized, state-of-the-art Deep Learning models directly on cloud-based GPU hardware.

## 🚀 Key Features
* **AI Grammar Correction:** Uses a fine-tuned T5 Transformer model to fix complex syntax and tense mistakes contextually.
* **Smart Pipeline Sequencing:** Corrects grammar *before* translating to ensure high-quality, distortion-free translations.
* **Dynamic Study Mode:** Uses `spaCy` to strip common stopwords, isolate advanced vocabulary, and fetch live definitions via a REST API.
* **GPU Accelerated:** Optimized to run seamlessly on Google Colab using a free T4 GPU runtime.

## 🏗️ System Architecture


##v[Raw English Input] ──► [Grammar Correction (T5)] ──► [Clean English Text] ──► [Translation & Study Mode]



## 🛠️ Tech Stack & Components
* **Environment:** Google Colab (NVIDIA T4 GPU)
* **Grammar Model:** Hugging Face `vennify/t5-base-grammar-correction` (Fine-tuned on the JFLEG Dataset)
* **NLP Pipeline Engine:** `spaCy` (`en_core_web_sm` model)
* **Translation Core:** `deep-translator` library
* **Core Libraries:** `transformers`, `torch`, `requests`
* **Knowledge Base:** Free Dictionary API

## 📊 Sample Execution Output


======================================================================
📥 ORIGINAL INPUT: 'She dont likes the complicated assignments'
======================================================================
✨ AI CORRECTED:   She doesn't like the complicated assignments.
🌐 TAMIL TRANSLATION: அவள் சிக்கலான பணிகளை விரும்புவதில்லை.

📚 STUDY MODE INSIGHTS:
  • Complicated: Difficult to analyze or understand.
  • Assignment: A task or piece of work assigned to someone as part of a course.
======================================================================


## 👨‍💻 Developer Info

* **Name:** Tamil Selvam
* **Academic Level:** B.Sc. CS AI&ML 2nd Year

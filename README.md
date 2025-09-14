# 🌸 Smart Poems Generator

A **personalized poetry generation platform** built with **ReactJS** and **NLP**, guiding users through a **6-step inspiration flow** to create emotionally tailored poems.  
The system combines **dataset-driven suggestions**, **Word2Vec-based inspiration extraction**, and **fine-tuned generative models** to deliver unique and context-aware poems.

---

## ✨ Features
- 🎭 **Guided 6-step flow** for poem creation (topics → emotions → moments → phrases → rhyming → generation).  
- 📚 **Dataset preprocessing** of **180K+ poems**, structured into **200+ topics, emotions, and phrases**.  
- 🧠 **Word2Vec-powered NLP pipeline** for keyword extraction, achieving **BLEU score: 0.79**.  
- 🤖 **LangChain + HuggingFaceEndpoint integration** with **fine-tuned GPT-2 model** trained on 300+ poems.  
- 🌐 **ReactJS-based frontend** with a clean, interactive user experience.  
- 💡 Provides **inspirations & suggestions** before poem generation to enhance creativity.  

---

## 🏗️ Tech Stack
- **Backend / Orchestration:** LangChain  
- **NLP / ML Models:**  
  - Hugging Face Transformers  
  - GPT-2 (fine-tuned)  
  - Word2Vec (topic & phrase extraction)  
- **APIs:** HuggingFaceEndpoint  
- **Dataset:** 180K+ poems (cleaned & structured)

---

## 📊 Dataset & NLP Pipeline
- Raw dataset: **180K poems** across multiple themes.  
- Preprocessing steps:  
  - Tokenization & cleaning  
  - Stopword removal  
  - Word2Vec training  
  - Topic & phrase clustering → mapped into **200+ topics/emotions/phrases**.  
- Evaluation: **BLEU Score = 0.79** → ensures generated suggestions align well with dataset inspiration.  

---

## 🔄 Workflow
1. **User Input** → Topic, Style, Emotions, Moments, Phrases.  
2. **Inspiration Suggestions** → NLP pipeline provides related rhymes, phrases, and keywords.  
3. **LangChain Prompt Template** → Combines user details with structured inspiration.  
4. **HuggingFaceEndpoint (fine-tuned GPT-2)** → Generates context-aware, emotionally rich poems.  
5. **ReactJS Frontend** → Displays poem with guided 6-step flow.  

---

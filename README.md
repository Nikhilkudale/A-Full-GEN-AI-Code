# 🤖 GenAI Full Course - Projects

Complete Generative AI projects built with Hugging Face, Transformers, and Streamlit.

## 📁 Projects

### 1️⃣ **generateai_day1** - Hugging Face Models
Text generation, Q&A, and model exploration using Hugging Face.

- `huggingface_qa.py` - Question Answering pipeline
- `huggingface_text_gen.py` - Text generation models
- `test_huggingface.py` - Testing different models

### 2️⃣ **generateai_day2** - AI Chatbot (Production Ready)
A fully functional AI Chatbot built with Streamlit and DialoGPT.

**Features:**
- ✅ Conversational AI with DialoGPT
- ✅ Chat history management
- ✅ Clean UI with Streamlit
- ✅ Error handling & validation
- ✅ Ready to deploy

**Run Locally:**
```bash
cd generateai_day2
pip install -r requirements.txt
streamlit run src/app.py
```

**Deploy to Streamlit Cloud:**
1. Go to [share.streamlit.io](https://share.streamlit.io)
2. Select this repo
3. File path: `generateai_day2/src/app.py`
4. Deploy!

## 📚 Learning Path

1. Start with **Day 1** - Learn Hugging Face basics
2. Move to **Day 2** - Build a production chatbot
3. Explore different models and customize

## 🎯 Technologies

- **Python 3.10+**
- **Transformers** - Hugging Face NLP library
- **Streamlit** - Web UI framework
- **PyTorch** - Deep learning backend

## 📋 Requirements

```
streamlit>=1.28.0
transformers>=4.35.0
torch>=2.0.0
torchvision>=0.15.0
torchaudio>=2.0.0
```

## 🚀 Deployment

Deploy to Streamlit Community Cloud (free):
- No Docker needed
- Auto-deploys on git push
- Always online

## 📖 Resources

- [Streamlit Docs](https://docs.streamlit.io)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers)
- [DialoGPT Model](https://huggingface.co/microsoft/DialoGPT-medium)

---

**Built with ❤️ for learning Generative AI**

# Movie Review Sentiment Analysis 🎬🧠

An NLP-based sentiment analysis system that classifies movie reviews as **positive or negative** using a fine-tuned **DistilBERT** model.  
The model is trained on the IMDb dataset and deployed via an interactive **Gradio** interface for real-time predictions.

> ⚠️ This project is designed to run on **Google Colab**. The complete workflow executes from a single notebook.

---

## 🔍 Problem Statement

Understanding audience sentiment from movie reviews is essential for content creators, streaming platforms, and recommendation systems.  
Manual analysis is inefficient at scale, making automated sentiment classification a practical NLP application.

This project solves the problem by:
- Fine-tuning a transformer-based model on large-scale review data
- Optimizing training efficiency
- Deploying a user-friendly inference interface

---

## ✨ Key Features

- 🧠 Fine-tuned **DistilBERT-base-uncased** for sentiment classification  
- 📊 Binary classification (Positive / Negative)  
- ⚡ Optimized training using **fp16 mixed-precision**  
- 🎛️ Interactive **Gradio web demo**  
- ☁️ Runs entirely on **Google Colab**

---

## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **Hugging Face Transformers**
- **DistilBERT**
- **Natural Language Processing (NLP)**
- **Gradio**
- **Google Colab**

---

## 🧠 Model & Training Details

- **Base Model:** DistilBERT-base-uncased  
- **Task:** Binary sentiment classification  
- **Dataset:**  
  - IMDb movie reviews  
  - **25,000 samples** used for training  
- **Training Optimizations:**  
  - Applied **fp16 mixed-precision training**  
  - Reduced training time by approximately **30%** without performance degradation  

---

## 📊 Evaluation Results

The model achieved strong performance on validation data:

| Metric | Score |
|------|------|
| Accuracy | **91.19%** |
| F1-Score | **0.9119** |

These results demonstrate effective learning while maintaining computational efficiency.

---

## 🚀 How to Run the Project

### 👉 Run on Google Colab (Recommended)

1. Open the notebook in Colab:
   
   👉 **[Open in Google Colab](https://colab.research.google.com/drive/1hGD6SPIHvxZhvpPMJ8Th7tZP-IA4LkkA)**

2. Run all cells from top to bottom  
   (`Runtime → Run all`)

3. Launch the **Gradio interface** from the final cell.

4. Enter a movie review to get a **real-time sentiment prediction**.

> ⚠️ The entire notebook must be executed for the Gradio app to work correctly.

---

## 🧪 Sample Use Cases

- Movie and TV show review analysis  
- Audience sentiment tracking  
- Recommendation system input signals  
- NLP model benchmarking

---

## 📌 Project Highlights (For Recruiters)

- Fine-tuned a **transformer-based NLP model** on large-scale text data  
- Applied **mixed-precision training** for performance optimization  
- Achieved **high accuracy and F1-score** on validation data  
- End-to-end pipeline (**data → training → evaluation → deployment**)  
- Clean, **reproducible notebook-based workflow**

---

## 📈 Future Improvements

- Multi-class sentiment classification  
- Aspect-based sentiment analysis  
- Support for longer reviews and multilingual input  
- Deployment as a **standalone production web application**

---

## 👤 Author

**Aswin M**  
AI / ML Enthusiast | Undergraduate Computer Science Student  

🔗 GitHub: https://github.com/asw-beep  

---

## 📄 License

This project is open-source and available under the **MIT License**.

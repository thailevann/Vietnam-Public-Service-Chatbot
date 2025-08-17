# Vietnam-Public-Service-Chatbot

This repository contains a lightweight, domain-adapted language model for **Vietnamese public administrative services**.  
The goal is to improve question answering for procedures on the official portal [dichvucong.gov.vn](https://dichvucong.gov.vn/).  

📂 **Dataset & Model**  
All training and evaluation resources are released publicly on Hugging Face:  
👉 [HuggingFace Collection](https://huggingface.co/collections/thailevann/dch-v-cong-2025-68693de7539f6852fca3ef64)

---

## 🏗️ Model Architecture

1. **Continued Pretraining**  
   Adapts a lightweight base language model to the **public service domain**.  
2. **Supervised Fine-Tuning (SFT)**  
   On domain-specific **question–answer pairs**.  
3. **Two-Pass Inference**  
   Refines responses by incorporating previous context → improves both **factual accuracy** and **clarity**.  

<p align="center">
  <img width="812" height="447" alt="architecture" src="https://github.com/user-attachments/assets/441eb638-d191-441a-af6f-f79b9035b096" />
</p>

---

## 📊 Evaluation Results

### Multiple-Choice Benchmark
<p align="center">
  <img width="521" height="342" alt="multichoice" src="https://github.com/user-attachments/assets/aef955db-c88b-4138-a435-8ad3f390de2f" />
</p>

### Question Answering Benchmark
<p align="center">
  <img width="637" height="150" alt="qa" src="https://github.com/user-attachments/assets/15a81098-8ca2-4690-9297-ad2c9df2c24f" />
</p>

---

## 📌 Conclusion
In this work, we present a lightweight, domain-adapted language model for Vietnamese public administrative question answering. By combining continued pretraining, supervised fine-tuning, and inference refinement, our approach improves factual accuracy and generation quality on both instruction-answer and multiple-choice tasks.  

We release all training and evaluation resources to promote reproducibility and further research.

# General Health Query Chatbot (Prompt Engineering Based)

## Task Objective

The objective of this project is to build a simple conversational chatbot that can answer **general health-related questions** using a Large Language Model (LLM). The chatbot is designed to provide clear, friendly and safe responses while avoiding harmful medical advice.

The system focuses on:
- Answering common health questions
- Providing simple and understandable explanations
- Maintaining user safety
- Encouraging consultation with healthcare professionals for serious issues

---

## Approach Used

Unlike traditional machine learning tasks, this project does **not use a dataset**.  
Instead, the chatbot works on **real-time user queries**.

The system includes:
- Prompt Engineering
- Safety Filtering
- Interactive Chat Loop
- Large Language Model (LLM)

---

## Model Used

### Mistral-7B-Instruct (Open-Source LLM)

The chatbot uses **Mistral-7B-Instruct**, an open-source Large Language Model capable of understanding and generating natural language responses.

The model was loaded locally in **4-bit quantized format** to run efficiently on Google Colab GPU.

---

## Why We Used Local Mistral Instead of OpenAI or HuggingFace API

### 1️⃣ No API Cost / Fully Free
- OpenAI requires billing and API credits.
- HuggingFace Inference API has usage limits and permission restrictions.
- Running Mistral locally avoids all external costs.

### 2️⃣ No Internet/API Dependency
- The chatbot runs fully offline once the model is loaded.
- No quota errors or API failures.

### 4️⃣ More Control & Customization
Running the model locally allows:
- Better prompt control
- Custom safety filtering
- Adjustable generation settings
- Interactive conversational loop

---

## Safety Handling

A safety filter was implemented to detect harmful or sensitive queries such as:
- Self-harm
- Overdose
- Dangerous medical instructions

If unsafe input is detected, the chatbot refuses to respond and advises consulting a professional.

---

## Prompt Engineering

The chatbot uses a carefully designed prompt to ensure:

- Friendly and simple responses
- No harmful medical advice
- No medicine prescriptions
- Encouragement to consult doctors for serious symptoms

---

## Features

- Interactive chatbot system
- Real-time query handling
- Prompt-engineered safe responses
- Safety filtering
- Runs locally without API
- Supports general health queries

---

## Example Queries

- What causes a sore throat?
- Is paracetamol safe for children?
- How can I improve sleep quality?
- What are symptoms of flu?

---

## Key Results and Findings

- The chatbot successfully answers general health-related questions.
- Prompt engineering helped produce clear, simple, and friendly responses.
- The safety filter effectively prevents harmful or dangerous advice.
- The interactive system allows real-time conversational health assistance.
- The chatbot demonstrates how open-source LLMs can be used to build safe conversational AI systems.

---

## Skills Gained

- Prompt design and testing
- Working with Large Language Models (LLMs)
- Building conversational AI systems
- Implementing safety filters in chatbots
- Running open-source models locally

---

## 🛠 Technologies Used

- Python  
- Transformers (HuggingFace)  
- PyTorch  
- Google Colab (GPU)  

---

## Conclusion

This project demonstrates how prompt engineering and open-source LLMs can be used to build a safe and simple healthcare chatbot. The system successfully answers general health-related queries while maintaining safety and clarity. Although it is not a replacement for professional medical advice, it serves as an educational and supportive conversational tool.

---


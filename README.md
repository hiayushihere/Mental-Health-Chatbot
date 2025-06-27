# Mental-Health-Chatbot
Leveraging NLP, Deep Learning, and Generative AI for Empathetic Mental Health Support
-> Overview
The Mental Health Companion is an intelligent chatbot system designed to assist users experiencing stress and emotional challenges. It leverages a hybrid pipeline combining transformer-based classification models (like RoBERTa) and fine-tuned generative models (GPT-based or Mistral with LoRA adapters) to offer:

Accurate stress detection
Insightful stress type classification
Compassionate, empathetic response generation
The chatbot is grounded in real-world mental health data and empathetic conversations, aiming to create a safe, non-judgmental, and supportive virtual space for users.

 ->Project Goals
Detect stress and emotional states in user inputs
Identify the type of stress (e.g., anxiety, PTSD, burnout, etc.)
Generate empathetic and context-aware responses
Support continuous interaction until the user chooses to stop
Lay the groundwork for an accessible mental health companion powered by AI

-> Core Features
Feature	Description
Stress Classification	Uses a fine-tuned RoBERTa model to detect whether the user is stressed
Stress Type Prediction	If stressed, predicts stress type based on subreddit categories (e.g., r/anxiety, r/ptsd)
Empathetic Response Generation	Employs a fine-tuned language model (GPT/Mistral) on the EmpatheticDialogues dataset
Conversational Loop	Enables continuous dialogue with stop command
Clean & Modular Code	Separates classification and generation logic for easy extension

->Datasets Used
EmpatheticDialogues Dataset
For training a generative model that produces emotionally aligned responses
Dreaddit (Stress) Dataset
For binary and multi-class stress classification based on subreddit sources

-> Tech Stack
Languages & Frameworks: Python, PyTorch, Hugging Face Transformers, LangChain
Models: RoBERTa (for stress detection), Mistral/GPT (for response generation)
Preprocessing: Text cleaning, tokenization, dataset balancing
Fine-Tuning: LoRA for lightweight adaptation of large models
Deployment (Future Scope): Flask or Gradio interface

-> How It Works
Input: The user submits a text expressing feelings.

Step 1 - Stress Detection:
A RoBERTa model checks if the user is stressed.

Step 2 - Stress Type Prediction (if stressed):
The chatbot identifies the likely stress category based on subreddit labels.

Step 3 - Response Generation:
A fine-tuned Mistral/GPT model generates an empathetic response tailored to the user's context.

Output: The response is displayed. The user may continue the conversation or type "stop" to exit.

<img width="1374" alt="Screenshot 2025-05-11 at 12 56 00 AM" src="https://github.com/user-attachments/assets/42536aff-e82d-4eef-b89c-d9a8230bc494" />
<img width="1404" alt="Screenshot 2025-05-11 at 12 46 11 AM" src="https://github.com/user-attachments/assets/018be5de-2c55-4efa-9165-44ffac556f7b" />


-> About Me
Final year student passionate about NLP, mental health, and building empathetic AI systems.
Open to work in machine learning, AI research, and product roles in tech.
LinkedIn - https://www.linkedin.com/in/ayushi-singh-77053a271/
Email id - Ayushi87u@gmail.com
-> Contributions & Acknowledgments
Inspired by real-world challenges in mental health awareness and support.
Thanks to the open-source community and dataset creators for their foundational work.

-> Final Note
This chatbot is not a substitute for professional mental health care. If you're struggling, please reach out to a certified therapist or counselor. ❤️


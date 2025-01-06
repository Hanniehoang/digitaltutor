# Digital Undergraduate Tutor: Chemical Engineering Support Tool 

## Group Project
This is a collaborative project developed by a team of 6 members

## Project Overview
This project focuses on creating an advanced, privacy-preserving learning tool tailored for Chemical Engineering students. By leveraging Microsoft Phi3.5 Mini, an open-source language model, and cutting-edge fine-tuning techniques, the tool provides personalized, context-aware assistance.

- **Model Used:** Microsoft Phi3.5 Mini (Open-source language model)
- **Fine-tuning Methods:** Parameter-Efficient Fine-Tuning (PEFT) - **QLoRA**, **LoRA**, **Unsloth**
- **Retrieval-Augmented Generation (RAG):** For dynamic, context-aware responses.
- **Deployment:** Docker container for local, privacy-preserving deployment.

### Key Features:
- Fine-tuned model for efficient learning and minimal resource consumption.
- Integration of official **Chemical Engineering lecture materials, unit readers, textbooks, and manuals** for training.
- On-device, privacy-preserving solution for personalized tutoring.
- Model evaluation using custom **question-answer** datasets in JSON format.

### Technologies Used:
- **Programming Languages:** Python
- **Machine Learning Libraries:** TensorFlow, Hugging Face, LangChain, LlamaIndex
- **Tools:** Docker, HPC (High-Performance Computing) 
- **Modeling Techniques:** QLoRA, LoRA, Unsloth (PEFT), Retrieval-Augmented Generation (RAG)
- **Data Preprocessing Tools:** LangChain, LlamaParse

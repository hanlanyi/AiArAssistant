# AiArAssistant

![System Overview](pics/overview.png)

**AiArAssistant** is a next-generation software framework that fuses **Artificial Intelligence (AI)** with **Augmented Reality (AR)** to create intelligent, interactive, and dynamic AR experiences.

This project empowers AR environments with advanced AI capabilities—ranging from contextual information retrieval to autonomous manipulation of virtual objects—by seamlessly integrating local Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and agent-based architectures with real-time AR platforms.

## ✨ Key Features

- **Intelligent AR Interaction**  
  Control and modify virtual 3D objects in AR using natural language commands.

- **RAG-Enhanced Knowledge**  
  Retrieve and generate contextually accurate responses from personal or domain-specific knowledge bases.

- **Multi-Agent Coordination**  
  Route user intents through an agent manager that selects the most appropriate AI tools for the task.

- **Modular MLOps + LoRA**  
  Fine-tune and manage models locally with Hugging Face, GPU acceleration, and modular components for training, embedding, and ranking.

- **Cross-Device AR Compatibility**  
  Works with a variety of AR glasses and devices, enabling portability and scalability.

## 🧠 Architecture Overview

The system is divided into two main domains:

### AI Modules
- **MLOps**: Handles training, validation, and fine-tuning (e.g., LoRA) of models.
- **Local LLM**: Runs inference using on-device LLMs powered by Hugging Face and shared memory for speed.
- **RAG**: Retrieves knowledge from documents and combines it with LLMs for grounded responses.
- **Agent Manager**: Classifies user intent and routes commands to the appropriate modules.

### AR Modules
- **AR Network**: Connects AR devices like headsets and smart glasses.
- **ARO Manager**: Controls AR objects and manages their properties and behaviors.
- **AI Client**: Communicates with AI backend, sends and receives commands.
- **UI**: User interface for inputting commands and visualizing the AR environment.

---

> 🧩 AiArAssistant aims to bridge the gap between immersive environments and intelligent systems—giving users the power to not only explore AR, but to shape it with their words.

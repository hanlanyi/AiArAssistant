# AiArAssistant

![System Overview](pics/overview.png)

**AiArAssistant** is a software framework that fuses **Artificial Intelligence (AI)** with **Augmented Reality (AR)** to create intelligent, interactive, and dynamic AR experiences.

This project empowers AR environments with advanced AI capabilities by integrating local Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), an AI agent layer, and the MCP (Model Context Protocol) server, while maintaining real-time performance across AR platforms.

## Key Features

- **Intelligent AR Interaction**  
  Control and modify virtual 3D objects in AR using natural language commands.

- **MCP Server with Agent Routing**  
  The MCP server hosts the agent system to interpret, classify, and route user intents to the right AI modules.

- **RAG-Enhanced Knowledge**  
  Retrieve and generate contextually accurate responses from personal or domain-specific knowledge bases using RAG.

- **Local LLM Inference**  
  Run inference with local LLMs for low-latency, on-device or edge execution.

- **Cross-Device AR Compatibility**  
  Works with a variety of AR glasses and devices.

## Architecture Overview

The system is divided into two main domains that communicate in real time:

### AI Domain
- **RAG**: Retrieves knowledge and grounds responses.
- **Local LLM**: Executes inference on local or edge hardware.
- **AI Agent**: Interprets intents and chooses tools and workflows.
- **MCP**: Orchestrates the AI components and exposes services to AR.

### AR Domain
- **AR Network**: Connects AR devices and routes data streams.
- **ARO Manager**: Controls AR objects and manages their properties and behaviors.
- **Communication**: Bridges AR and AI with a real-time messaging layer.
- **UI**: User interface for input and visualization in AR.

---

> **AiArAssistant** bridges immersive environments and intelligent systems, giving users the power to shape AR with their words via the MCP server.

# 🤖 AI Agent with Tool Usage (LangChain + LangGraph)

An intelligent AI agent that can **reason, decide, and take actions** using tools like a calculator and greeting system.  
Built using LangChain and LangGraph, this project demonstrates the core concepts of **Agentic AI**.

<img width="1536" height="1024" alt="AI agent with tool integration" src="https://github.com/user-attachments/assets/28dfc713-4e46-4e9c-9ea6-4204ea15d758" />


---

## 🚀 Project Overview

This project showcases how to build an AI agent that goes beyond simple text generation.

Instead of just responding, the agent:
- Understands user intent  
- Decides whether to act or respond  
- Uses tools dynamically  
- Streams responses in real time  

---

## 🧠 Key Concepts

### 🔹 ReAct Architecture (Reason + Act)
The agent follows a reasoning pattern:
- Think → Decide → Act → Respond

- <img width="1536" height="1024" alt="AI agent architecture flowchart diagram" src="https://github.com/user-attachments/assets/8a8242ec-349b-4475-b6ef-81f92d444464" />


---

### 🔹 Tool Integration
Custom tools are created and registered with the agent:

- 🧮 **Calculator Tool** → Performs arithmetic operations  
- 👋 **Greeting Tool** → Interacts with users  

The agent decides when to use these tools dynamically.

---

### 🔹 LLM as Decision Engine
The Large Language Model:
- Understands user input  
- Selects the right action  
- Generates responses  

---

### 🔹 Agent Orchestration
Using LangGraph:
- Connects LLM + tools  
- Manages reasoning flow  
- Executes actions step-by-step  

---

### 🔹 Streaming Responses
Responses are streamed in real time, improving user experience and transparency.

---

## ⚙️ Tech Stack

- Python  
- LangChain  
- LangGraph  
- OpenAI API *(can be replaced with Gemini API)*  
- dotenv  

---

## 📂 Project Structure

├── main.py
├── .env
├── README.md

## Install Dependencies :
pip install -r requirements.txt

## Setup Environment Variables :

OPENAI_API_KEY=enter here 

Note: OpenAI API is paid. You can replace it with Gemini API for cost optimization.

## Run the Application
python main.py

Example Usage :
You: Add 10 and 20  
Assistant: The sum of 10 and 20 is 30  

You: Say hello to Harathi  
Assistant: Hello Harathi, I hope you are well today  

## Challenges Faced
Understanding how the agent decides when to use tools

Debugging tool input/output handling

Managing API keys securely

Handling streaming responses

Ensuring consistent agent behavior

## Key Learnings
AI agents can reason and act, not just respond

Tool integration is key to building real-world AI systems

LLMs can act as decision-making engines

Agentic AI requires system design, not just prompts

## Future Improvements
Add memory (conversation history)

Multi-step reasoning workflows

Integration with external APIs

Replace OpenAI with Gemini for cost efficiency

Build real-world automation use case

## Connect With Me

If you’re interested in AI, automation, or building intelligent systems, feel free to connect with me on LinkedIn!

## 🏁 Conclusion

This project helped me realize that AI is not just about generating text—it’s about designing systems that can think, decide, and act.

Building this agent gave me hands-on experience with real-world AI workflows and strengthened my foundation in Agentic AI.

This is just the beginning of my journey into building intelligent, autonomous systems.

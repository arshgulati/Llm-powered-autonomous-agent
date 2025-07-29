# Llm-powered-autonomous-agent
# LLM Agent Project: LangChain-based Multi-Tool Agent (Simulated Search Version)
Multi-Tool LLM Agent
-----------------------
This script implements a LangChain-based autonomous LLM agent capable of:
- Interpreting complex natural language tasks
- Decomposing them into subgoals
- Selecting and executing appropriate tools
- Synthesizing final responses

Assignment Tasks Covered:
-------------------------
1. Agent Design: Modular setup using LangChain
2. Tool Use Integration: Web Search (simulated), Calculator, Python Executor, Summarizer
3. Prompt Engineering & Planning: Handled by LangChain's Conversational ReAct agent
4. Memory & Context Management: ConversationBufferMemory
5. Evaluation Suite: Test query with multi-step reasoning

Setup Instructions:
-------------------
1. Install dependencies:
    pip install langchain langchain-community langchain-experimental tiktoken unstructured pypdf

2. Run the agent:
    python main.py

Query Example:
--------------
"Find Elon Musk's recent companies and calculate how his net worth changed."

Project Files:
--------------
- assignment.py: Main logic
- ReadMe

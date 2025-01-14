# LangChain Multi-Tool Agent with OpenAI Integration

This project demonstrates the use of LangChain tools to create a multi-tool agent capable of retrieving information from various sources like Wikipedia, LangChain documentation, and Arxiv research papers. The agent uses **OpenAI's GPT-4** model for enhanced reasoning and response generation.

---

## Features
- **Wikipedia Search**: Queries Wikipedia for concise information using the `WikipediaQueryRun` tool.
- **Arxiv Research Papers**: Fetches the latest research papers using the `ArxivQueryRun` tool.
- **LangChain Documentation Search**: Allows users to search LangChain documentation using a custom retriever tool powered by FAISS.
- **Agent Executor**: Combines all tools to provide a single query interface, managed by an OpenAI-powered agent.

---

## Requirements
- Python 3.8+
- API keys for OpenAI and required services.
- Installed dependencies from `requirements.txt`.

---

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/aditya10avg/MultiSearch-Agent.git
   cd MultiSearch-Agent.git
```

2. Install required Python packages:
```bash
 pip install -r requirements.txt
```

3. Set up your environment variables in a .env file:

```bash
 OPEN_AI_API_KEY=your_openai_api_key
```

## How to Use







![Screenshot from 2025-01-14 16-48-41](https://github.com/user-attachments/assets/6a39097e-dbf5-4aa6-ab29-d19d2f867197)![Screenshot from 2025-01-14 16-48-53](https://github.com/user-attachments/assets/5cdfdd01-ff46-4ddb-a8f5-fb2811f6323b)
![Screenshot from 2025-01-14 16-48-41](https://github.com/user-attachments/assets/745c0930-215b-412d-b7cc-429d1348bb06)

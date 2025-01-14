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

1. Run the agent.ipynb.
2. Enter the query when you run that cell.
  Reference Image.
 ![Screenshot from 2025-01-14 16-48-53](https://github.com/user-attachments/assets/5cdfdd01-ff46-4ddb-a8f5-fb2811f6323b)

4. The agent will:

  - Retrieve relevant data using the available tools.
  - Display the results in a structured format. 


## Tools and Modules

1. Wikipedia Search
API Wrapper: WikipediaAPIWrapper
Tool: WikipediaQueryRun
Description: Fetches concise information from Wikipedia based on user queries.


2. LangChain Documentation Search
Document Loader: WebBaseLoader
Vector Store: FAISS with OpenAIEmbeddings
Retriever Tool: Allows search functionality within LangChain documentation.

3. Arxiv Research Papers
API Wrapper: ArxivAPIWrapper
Tool: ArxivQueryRun
Description: Retrieves top research papers from Arxiv related to the user query.

## Notes
1. Verbose Mode: Enabled for debugging. Disable it by setting verbose=False in the AgentExecutor.
2. Custom Prompt: The agent uses a custom prompt loaded from LangChain Hub.


## Acknowledgments
LangChain Team for providing robust tools for building this agent. Langchain is really helpful.



## Screenshots of its working.
![Screenshot from 2025-01-14 16-48-41](https://github.com/user-attachments/assets/6a39097e-dbf5-4aa6-ab29-d19d2f867197)


# StonksGuy

StonksGuy is a simple AI-Agent based project designed to assist users with financial data analysis and web searches. Built using the Phi framework and OpenAI's APIs, it integrates tools like YFinance and DuckDuckGo to provide detailed insights and summaries. StonksGuy leverages powerful Groq models for enhanced reasoning and tool usage.

---

## **Features**

### **Agents**

#### 1. Web Search Agent
- Searches the web for information using DuckDuckGo.
- Always includes sources for credibility.
- Supports markdown formatting for rich text responses.

#### 2. Finance AI Agent
- Provides stock price data, analyst recommendations, stock fundamentals, and company news using YFinance tools.
- Displays data in tabular format for easy comprehension.

#### 3. Multi-AI Agent
- Combines the capabilities of both the Web Search Agent and Finance AI Agent.
- Summarizes data and presents detailed, structured responses.

---

## **Technologies Used**

- **Phi Framework**: For building AI agents and integrating tools.
- **OpenAI API**: For high-quality language model capabilities.
- **Groq Models**: Optimized models for reasoning and tool usage.
- **YFinance Tools**: For financial data.
- **DuckDuckGo Tools**: For web searches.
- **dotenv**: For environment variable management.

---

## **Installation**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/stonksGuy.git
   cd stonksGuy
   ```

2. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the environment variables:**
   - Create a `.env` file in the project root.
   - Add your OpenAI API key:
     ```env
     OPENAI_API_KEY=your_openai_api_key
     ```

4. **Run the application:**
   ```bash
   python playground.py
   ```

---

## **Usage**

### **Running the Playground**
- Access the application by navigating to the localhost URL displayed in your terminal after running the script.
- Interact with the agents for web searches or financial data analysis.

### **Example Query**
For the Multi-AI Agent, use queries like:
```python
multi_ai_agent.print_response("Summarize analyst recommendations and share the latest news for NVDA stock", stream=True)
```

---

## **Project Structure**

```
stonksGuy/
├── playground.py       # Main application script for the Playground
├── finance_agent.py    # Defines the Finance AI Agent and Web Search Agent
├── requirements.txt    # Python dependencies
├── .env                # Environment variables
└── README.md           # Project documentation
```




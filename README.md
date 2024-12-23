# AI Agent Suite with LLaMA 3.3 70B on Groq Cloud

## Overview
This project leverages the **LLaMA 3.3 70B versatile model** on **Groq Cloud** to create a suite of AI agents capable of performing advanced tasks in finance and web data retrieval. The agents are designed to provide seamless access to actionable insights, tailored to specific domains.

### Features
1. **Groq Agent**  
   - Interfaces with the Groq Cloud infrastructure to efficiently run the LLaMA 3.3 model.  
   - Manages the initialization and inference processes for all agents.

2. **Finance Agent**  
   - Specializes in analyzing and retrieving financial data.  
   - Provides detailed reports, trends, and predictions based on user queries.
   - Makes table for better comparision between stocks and other financial queries.

3. **Finance and Web Agent**  
   - Combines finance analysis with web scraping capabilities.  
   - Gathers information from the web to complement financial data, ensuring comprehensive responses.
   - Gives real time news about different financial instituitions 

---

### Prerequisites
- Python 3.8+
- Access to Groq Cloud
- Required libraries (install via `requirements.txt`)
- API key (Can use openai api for a more powerful model)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ai-agent-suite.git
   cd ai-agent-suite

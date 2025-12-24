# AI Agent with Gemini Function Calling

An autonomous AI-powered command-line agent built using **Google Gemini 1.5 Flash** that dynamically invokes tools (function calling) to solve user queries such as mathematical calculations, prime number detection, and real-time cryptocurrency pricing.

## Features  
- Fetches real-time cryptocurrency prices using CoinGecko API  
- Maintains multi-turn conversational context  
- Uses Gemini function calling for intelligent tool selection  
- Secure API key handling using environment variables  

##  Tech Stack
- Node.js  
- JavaScript (ES Modules)  
- Google Gemini API  
- CoinGecko REST API  
- dotenv  

##  Project Structure

AI-Agent-gemini-function-calling/
├── src/
│ └── agent.js
├── .env.example
├── .gitignore
├── package.json
└── README.md
---

## Setup Instructions
```bash
git clone https://github.com/jeet7867/AI-Agent-gemini-function-calling.git
cd AI-Agent-gemini-function-calling
npm install
cp .env.example .env
```

## Add your API key in .env:
```
GEMINI_API_KEY=your_api_key_here
```

## Run the Project
```
node src/agent.js

```

# Key Learning Outcomes

Implemented Gemini function calling for tool-based reasoning

Built an autonomous AI agent with decision-making capability

Integrated external REST APIs for real-time data

Managed multi-turn conversation history

Followed secure API key management best practices
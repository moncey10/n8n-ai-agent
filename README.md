#  My First AI Agent on n8n

A conversational AI Agent built using n8n workflow automation tool.

##  Features
- Powered by Google Gemini 1.5 Flash (Free)
- Remembers full conversation history
- Can solve math problems (Calculator)
- Can search Wikipedia for knowledge
- Can write and explain code

##  Tools & Technologies
- n8n Cloud (workflow automation)
- Google Gemini 1.5 Flash (AI model)
- Simple Memory (conversation memory)
- Calculator (math tool)
- Wikipedia (knowledge tool)
- Code Tool (coding tool)

##  How to Run This Project

### Step 1 - Setup n8n
- Go to cloud.n8n.io and create a free account
- OR install locally: `npm install n8n -g`

### Step 2 - Get Gemini API Key
- Go to aistudio.google.com
- Sign in with Google account
- Click "Get API Key" and copy it

### Step 3 - Import Workflow
- Download the JSON file from this repo
- Open n8n canvas
- Click "..." menu → "Import from file"
- Select the downloaded JSON file

### Step 4 - Add Your API Key
- Click on "Google Gemini Chat Model" node
- Click "Create new credential"
- Paste your Gemini API key
- Select model: gemini-1.5-flash
- Click Save

### Step 5 - Test Your Agent
- Click "Open chat" button
- Start chatting!

## 💬 Example Questions to Ask
| Question | Tool Used |
|---|---|
| What is 144 divided by 12? | Calculator |
| Who invented the telephone? | Wikipedia |
| Write a Python hello world | Code Tool |
| What is machine learning? | Gemini AI |

##  Project Structure
```
n8n-ai-agent/
│
├── My_First_AI_Agent.json   # n8n workflow file
└── README.md                # This file
```

##  Author
- Built by Moncey
- Built with n8n Cloud + Google Gemini

##  License
This project is open source and free to use.

# 🤖 AI HR Assistant for Telegram (HR Budy)

This project was developed during the **Oracle Next Education (ONE) + Alura Immersion Program**, focusing on building an AI-powered HR assistant capable of interacting with users through Telegram, maintaining conversational context, and retrieving information from a database.

## About the Project

The system simulates a Human Resources assistant that communicates with candidates via Telegram.

The AI agent is capable of:

* Receiving messages through Telegram
* Maintaining conversation context
* Querying data stored in a MySQL database
* Generating responses using Artificial Intelligence
* Automatically sending responses back to users

## Technologies Used

* n8n
* Telegram Bot API
* Cohere AI
* MySQL
* AI Agent
* Simple Memory

##  Workflow Architecture

```text
Telegram Trigger
       │
       ▼
    AI Agent
       │
 ┌─────┴─────┐
 ▼           ▼
Memory     MySQL
       │
       ▼
Telegram Response
```

## Features

### Conversational AI

Users can interact with the assistant through Telegram and receive AI-generated responses.

### Context Memory

The agent maintains conversation history, enabling more natural and contextual interactions.

### Database Integration

The assistant can access information stored in a MySQL database to answer specific questions.

### Automated Responses

All responses are automatically delivered back to the user through Telegram.

##  Demo

Add screenshots of the workflow and conversation examples in this section.

### n8n Workflow

![Workflow](./images/workflow.png)

## What I Learned

During the development of this project, I practiced and improved skills related to:

* Process Automation
* API Integrations
* Applied Artificial Intelligence
* Prompt Engineering
* Database Management
* AI Agent Development
* Workflow Orchestration with n8n

## Future Improvements

* Implement Retrieval-Augmented Generation (RAG)
* Integrate a Vector Database
* Improve candidate screening capabilities
* Add job posting management
* Implement candidate-job matching analysis
* Develop an administrative dashboard

## Author

**Leandro Jesus**

Full Stack Developer with a focus on Artificial Intelligence, Automation, and Blockchain Technologies.

# tags
n8n
telegram
ai-agent
artificial-intelligence
cohere
mysql
automation
chatbot
hr-tech

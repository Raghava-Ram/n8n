# n8n Workflows Collection

This repository contains a collection of n8n workflows in JSON format, showcasing various automation scenarios and integrations. These workflows demonstrate different use cases for n8n, from simple form handling to complex AI-powered automation systems.

## 📋 Workflows Overview

### 1. **Automation 1** - Consultation Form Handler
A basic workflow that demonstrates form handling and data collection.

**Features:**
- Web form for consultation requests
- Google Sheets integration for data storage
- Service selection (Consultation/Trading)
- Automatic timestamp tracking

**Use Case:** Lead generation and consultation booking system

### 2. **Gmail AI Reply** - Intelligent Email Assistant
An AI-powered email management system that automatically processes and responds to emails.

**Features:**
- Gmail integration with polling trigger
- AI-powered email analysis and categorization
- Automatic label assignment (courses, doubts, sponsors)
- Smart response generation with HTML formatting
- OpenAI GPT-4 integration

**Use Case:** Automated email management and customer support

### 3. **My Google Calendar Agent Flow** - Calendar Management Assistant
An AI agent that helps manage Google Calendar events through natural language processing.

**Features:**
- Natural language calendar event creation
- Google Calendar integration
- AI agent with memory buffer
- Session management for conversations
- Event retrieval and management capabilities

**Use Case:** Personal calendar management through conversational AI

### 4. **Personal Assistant using Telegram** - Telegram Bot Assistant
A Telegram bot that acts as a personal assistant with task management capabilities.

**Features:**
- Telegram bot integration
- AI-powered conversation handling
- Google Tasks integration
- Real-time messaging
- Task management and retrieval

**Use Case:** Personal productivity assistant accessible via Telegram

### 5. **Nodes-in-n8n** - Comprehensive Node Examples
A comprehensive workflow demonstrating various n8n node types and integrations.

**Features:**
- Multiple trigger types (Form, Telegram, Schedule, Webhook, Gmail)
- Various node examples for learning purposes
- Integration examples with different services

**Use Case:** Learning and reference for n8n node types and configurations

## 🚀 Getting Started

### Prerequisites
- n8n instance (self-hosted or cloud)
- Required API credentials for:
  - Gmail (OAuth2)
  - OpenAI API
  - Telegram Bot API
  - Google Calendar API
  - Google Sheets API

### Installation
1. Clone this repository
2. Import the JSON files into your n8n instance
3. Configure the required credentials for each workflow
4. Activate the workflows as needed

## 🔧 Configuration

### Required Credentials
- **Gmail OAuth2**: For email automation workflows
- **OpenAI API**: For AI-powered features
- **Telegram Bot API**: For Telegram bot functionality
- **Google Calendar API**: For calendar management
- **Google Sheets API**: For data storage

### Environment Setup
Each workflow may require specific environment variables or API keys. Refer to the individual workflow documentation for detailed setup instructions.

## 📁 File Structure
```
n8n/
├── Automation 1.json                    # Basic form handling workflow
├── Gmail AI Reply.json                  # AI email assistant
├── My Google calendar agent flow.json   # Calendar management AI
├── Personal Assistant using Telegram.json # Telegram bot assistant
├── Nodes-in-n8n.json                   # Comprehensive node examples
└── README.md                           # This file
```

## 🤖 AI Integration

Most workflows utilize OpenAI's GPT models for intelligent automation:
- **Email Analysis**: Categorizing and responding to emails
- **Calendar Management**: Natural language event creation
- **Task Management**: Intelligent task handling
- **Conversational AI**: Natural language processing for various tasks

## 🔄 Workflow Types

### Trigger-based Workflows
- **Form Triggers**: Handle web form submissions
- **Gmail Triggers**: Process incoming emails
- **Telegram Triggers**: Handle bot messages
- **Schedule Triggers**: Time-based automation
- **Webhook Triggers**: External API integrations

### AI-powered Workflows
- **LangChain Agents**: Intelligent task processing
- **OpenAI Integration**: Natural language understanding
- **Memory Management**: Context-aware conversations

## 📊 Data Flow

1. **Input**: Various triggers (forms, emails, messages, schedules)
2. **Processing**: AI agents and automation logic
3. **Integration**: External services (Google, Telegram, etc.)
4. **Output**: Responses, data storage, notifications

## 🛠️ Customization

Each workflow can be customized by:
- Modifying trigger conditions
- Adjusting AI prompts
- Changing integration endpoints
- Adding new nodes for additional functionality

## 📝 Notes

- All workflows are in JSON format for easy import into n8n
- Some workflows may require specific API credentials
- AI-powered workflows use OpenAI's GPT models
- Google services integration requires proper OAuth2 setup

## 🤝 Contributing

Feel free to contribute by:
- Adding new workflows
- Improving existing workflows
- Adding documentation
- Reporting issues

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: Make sure to configure all required API credentials and test workflows in a development environment before deploying to production.

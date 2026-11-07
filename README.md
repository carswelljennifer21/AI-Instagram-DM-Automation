# 📩 AI Instagram DM Automation

An AI-powered Instagram DM automation workflow built with **n8n, Google Sheets, and AI model integration** that processes incoming messages, tracks conversations, detects duplicate messages, handles failed executions, and routes conversations to human assistance when needed.

## 🎯 Project Overview

Businesses receive Instagram messages from customers asking questions, requesting information, and seeking assistance.

Managing every conversation manually can become difficult, especially when multiple customers send messages at the same time.

This automation helps organize and process incoming Instagram messages while keeping track of conversation history and making human assistance available when needed.

## 🚨 The Problem

Handling Instagram messages manually can lead to:

- Delayed customer responses
- Repeated message processing
- Lost conversation context
- Difficulty tracking customer inquiries
- Failed automation executions
- Important requests being overlooked

## 💡 The Solution

This n8n workflow automates important parts of Instagram DM processing.

The automation:

1. Receives incoming Instagram messages.
2. Identifies the sender using their sender ID.
3. Checks for duplicate messages.
4. Retrieves the customer's previous conversation history.
5. Processes the message using AI and the approved knowledge base.
6. Tracks conversation information and message status in Google Sheets.
7. Handles failed messages through a retry process.
8. Routes conversations requiring personal assistance to a human.

## 🔧 Workflow

```text
Incoming Instagram DM
          ↓
Identify Sender
          ↓
Check Duplicate Message
          ↓
Retrieve Conversation Memory
          ↓
AI Message Processing
          ↓
Check Response / Handoff
          ↓
Update Conversation Records
          ↓
Google Sheets Tracking
          ↓
Human Assistance When Needed
```

## 🛠️ Technologies Used

- **n8n** — Workflow automation platform
- **Instagram Integration** — Handles incoming Instagram messages
- **Google Sheets** — Tracks conversation and message statuses
- **AI Model Integration** — Processes customer messages using an approved knowledge base
- **JSON** — Handles structured message and workflow data

## 📋 Data Used

The workflow processes information such as:

- Sender ID
- Incoming customer message
- Conversation history
- Customer intent
- Interest level
- Handoff status
- Message processing status

## 💬 Example Scenario

A customer sends a message requesting to speak directly with a business representative.

The workflow processes the message and identifies that human assistance is needed.

Example:

```text
Customer Message:
"Can I speak directly with someone, please?"

          ↓

Identify Sender
          ↓

Retrieve Conversation History
          ↓

Process Customer Intent
          ↓

Identify Human Assistance Request
          ↓

Update Handoff Status
          ↓

Route to Human Assistance
```

## 🔄 Error Handling

The workflow includes error-handling features to help manage unsuccessful executions.

These include:

- Failed-message tracking
- Retry handling
- Resetting failed messages to pending
- Sender ID preservation during retries
- Conversation memory retrieval
- Message status updates

These features help maintain conversation context and support reliable message processing.

## 📊 Benefits

This automation can help businesses:

- Organize incoming Instagram messages
- Maintain conversation history
- Reduce duplicate message processing
- Improve customer inquiry handling
- Track message statuses
- Manage failed executions
- Identify conversations requiring human assistance
- Reduce repetitive manual work

## 🔐 Security

**Never upload credentials or sensitive information to GitHub.**

Do not include:

- Instagram access tokens
- API keys
- Passwords
- n8n credentials
- Private customer messages
- Personal customer information
- Private Google Sheets links or data
- Client-specific configuration details

Before sharing workflow screenshots or JSON files, remove all credentials and confidential information. Only publish client work with the appropriate permission.

## 🚀 Possible Improvements

Future versions could include:

- More advanced customer intent detection
- Additional FAQ categories
- Customer inquiry analytics
- Response performance reports
- CRM integration
- More advanced conversation management
- Additional messaging platform integrations
- Human approval for selected AI responses

## 📌 Project Status

**Completed — Client Project / Portfolio Overview**

This project demonstrates an Instagram DM automation workflow developed and tested using n8n.

It showcases practical experience in AI-assisted message processing, conversation memory, duplicate detection, error handling, Google Sheets tracking, and human handoff.

Client-specific configurations, credentials, and proprietary workflow details are excluded from this portfolio description.

## 👤 Author

**Jennifer**

AI Automation & n8n Workflow Developer

### Skills Demonstrated

`n8n` `AI Automation` `Instagram DM Automation` `Google Sheets` `Conversation Memory` `JSON` `Error Handling` `Duplicate Detection` `Human Handoff` `Workflow Automation` `Customer Support Automation`

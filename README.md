# Sales Enablement Chatbot

## 📌 Overview
This project is a **sales enablement chatbot** built using **Botpress** to assist employees and customers with quick access to company resources.  

The bot provides information on products, company policies, sales collateral, and training/onboarding assistance. If an answer isn’t available, it gracefully handles fallback responses and allows users to ask additional questions.

---

## ⚙️ Features
- **Welcome Message**
  - Greets users with a friendly introduction.

- **Main Menu Options**
  - **Product Information Retrieval** – Provides details about company products and services.  
  - **Company Policies and Procedures** – Shares HR, compliance, and internal guidelines.  
  - **Sales Collateral and Resources** – Provides sales teams with brochures, presentations, and reference documents.  
  - **Training and Onboarding Assistance** – Supports employees in their onboarding journey.  

- **Knowledge Base Integration**
  - Uses Botpress Knowledge Agent to respond with accurate information.
  - Handles multiple queries in one session.

- **Fallback Handling**
  - Provides a “Sorry, I don’t know the answer…” response when information is unavailable.
  - Encourages users to re-ask or explore other categories.

- **Continuous Interaction**
  - Offers users the ability to ask **more questions** before ending the conversation.

---

## 🛠️ Tech Stack
- **Botpress** – Chatbot automation framework  
- **Knowledge Agent** – For handling product, policy, and training knowledge queries  
- **Custom Knowledge Base** – Company-specific documents and data  

---

## 🔄 Workflow Summary
1. **Start Conversation** → Greet user.  
2. **Show Main Options** → Product Info, Company Policies, Sales Resources, Training Support.  
3. **Retrieve Information** from knowledge base.  
4. **Fallback Handling** → If no answer is found, provide default response.  
5. **More Questions?** → Offer user the ability to continue or exit.  
6. **End Conversation**.  

---

## 🖼️ Bot Workflow Diagram
![Knowledge Base Chatbot Flow](./sales_enablement-bot-flow.png)  
*(This diagram shows the chatbot’s flow for handling knowledge base queries and providing fallback responses.)*  

---

## 🚀 Setup Instructions

### 1. Botpress Installation
- Install [Botpress](https://botpress.com/).
- Import this flow into your Botpress workspace.

### 2. Knowledge Base Setup
- Upload product documents, company policies, and training resources into the Botpress Knowledge Agent.
- Train the bot to improve accuracy in responding to queries.

### 3. Fallback Configuration
- Customize fallback messages to direct users to support staff or a knowledge portal.

### 4. Run the Bot
- Start Botpress server.
- Deploy on preferred channel (internal webchat, Slack, Teams, etc.).

---

## 📂 Project Structure
```
📦 knowledge-bot
 ┣ 📜 README.md
 ┣ 📜 knowledge-bot-flow.png   # Workflow screenshot
 ┗ 📂 botpress-bot-files
```

---

## ✅ Future Enhancements
- Add **multi-language support** for international teams.  
- Integrate with **document management systems** (Google Drive, SharePoint).  
- Add **live agent escalation** if the bot cannot answer after 2 attempts.  

---

## 👨‍💻 Author
Developed by **[Your Name]**  
For inquiries, reach out at **your-email@example.com**

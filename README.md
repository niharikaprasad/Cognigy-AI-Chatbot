# InsureMax Chat Agent

**InsureMax Chat Agent** is a fully functional conversational AI chatbot built using **Cognigy.AI**. This project demonstrates a production-ready workflow for a car insurance company, showcasing integration with **Azure AI LLMs**, knowledge stores, adaptive cards, and advanced AI-enhanced responses.  

---

## **Features**

- **Conversational AI with Azure LLMs**  
  Utilizes Azure OpenAI (GPT-4o-mini) for natural language understanding and generation. Responses are AI-enhanced, context-aware, and personalized based on user input.

- **Knowledge Store Integration**  
  FAQs and insurance policies are structured in a knowledge store. Users can ask questions like coverage, deductibles, and claim procedures, and the bot provides accurate, real-time answers.

- **Workflow & Connections**  
  - **Main Flow:** Handles core conversations and user inquiries.  
  - **Authentication Flow:** Secure login and invoice verification.  
  - **Connections:** Integrated with Azure AI LLMs for chat and embeddings, and supports adaptive card responses for a rich UI.

- **AI-Enhanced Responses**  
  The bot can rephrase responses, acknowledge user context (e.g., emergencies), and provide human-like engagement using AI enhancement settings.

- **User Login Authentication**  
  Users can log in securely with username and password to access personalized features, such as invoice requests and claim history.

- **Invoice Request & Email Feature**  
  Users can request copies of invoices. The bot validates user input and can trigger automated responses or emails for invoice delivery.

- **Image Upload Support**  
  Users can upload images (e.g., accident photos) for claims directly through the webchat interface.

- **Adaptive Card Templates**  
  Uses Microsoft Adaptive Cards for user-friendly interactions including login forms, invoice requests, and other input forms.

---

## **Project Structure**

Cognigy-AI-Chatbot/
│
├─ Flow-1.Main.cognigy # Main conversational flow
├─ Flow-2.Authentication.cognigy # Login and invoice verification flow
├─ README.md # Project documentation
├─ adaptive-cards/ # Adaptive card JSON templates
└─ assets/ # Optional assets (images, icons)


---

## **Demo & Usage**

- **Webchat Demo:** [Insert your Cognigy webchat link here]  
- **Local Import:**  
  1. Download the `.cognigy` files from this repo.  
  2. Import them into your Cognigy.AI workspace.  
  3. Configure connections to Azure LLMs and Knowledge Store as per your workspace settings.

---

## **Technologies Used**

- **Cognigy.AI** – Conversational AI platform  
- **Azure OpenAI Service** – LLM for AI-enhanced chat and embeddings  
- **Knowledge Store** – Structured FAQ and policy data  
- **Adaptive Cards** – User-friendly interactive messages  
- **Node.js / Python** – For custom function integrations (optional)

---

## **License**

This project is for demonstration purposes. Adapt and use according to your organization’s guidelines.

---

## **Contact**

For questions or demo requests, contact **Niharika Prasad** at [your email] or via [LinkedIn profile].



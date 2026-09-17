# AI WhatsApp Restaurant Ordering Assistant

I built this project to explore how AI can simplify the restaurant ordering process through WhatsApp.

The idea is simple: instead of customers having to ask restaurant staff about the menu, availability, or order details, they can have a conversation with an AI assistant.

### How it works

The customer sends a message on WhatsApp → n8n receives it → Gemini understands the request → the AI can check the restaurant's inventory or FAQs → the order is recorded in Google Sheets → the customer receives a response on WhatsApp.

![Workflow](workflow.png)

### What it can do

- Answer restaurant FAQs
- Check item availability
- Understand customer requests
- Maintain conversation context
- Take and record orders
- Respond automatically on WhatsApp

### Tools used

**n8n** · **Google Gemini** · **WhatsApp** · **Google Sheets**

### Example

**Customer:**  
Do you have a Margherita pizza?

**AI:**  
Yes, Margherita pizza is available. Would you like to order one?

**Customer:**  
Yes, I want 2.

The AI checks the available inventory, continues the conversation, and records the order after confirmation.

### Why I built it

I wanted to build something beyond a basic AI chatbot and understand how an AI model can interact with real data and complete an actual user workflow.

While building it, I focused on the conversation flow, access to relevant information, and what should happen when the user's request doesn't match the available data.

### Future improvements

- Add complaint and feedback handling
- Add order tracking
- Add human escalation
- Analyze customer conversations to identify recurring issues

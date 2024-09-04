# WhatsApp Bot for Sales and Order Management
This project involves a sophisticated WhatsApp bot designed to act as a customer-facing sales agent, utilizing a LangChain-based system with Groq and OpenAI technologies. The bot is structured to handle a variety of customer interactions, including:

### Product Searches: 
Finding and retrieving product information based on user queries.
### Price Checks: 
Providing the price of products.
### Stock Availability: 
Checking if products are in stock.
### Order Management: 
Placing orders, checking order status, and tracking delivery.
## Key Components:
### LangChain Integration: 
Utilizes LangChain for managing conversation flow and decision-making.
### Groq API: 
Integrates with Groq for advanced language model interactions.
### Hierarchical Supervisor Structure: 
Implements a global supervisor and sub-supervisors to route conversations between different agents (Sales Agent, Order Handling Agent) based on the nature of the user queries.
### Dynamic Agent Handling: 
Includes agents for product search, stock checking, price checking, order status, and delivery status.
## Workflow:
### Supervisor Agent: 
Determines the appropriate next agent based on the user's query and the conversation history.
### Sales Agent: Manages 
product-related queries, routing to specific agents for product search, price checks, and stock availability.
### Order Handling Agent: 
Handles order-related tasks, including order placement and delivery status.
## Features:
### State Management: 
Uses a state graph to manage the workflow and transitions between agents.
### Custom Prompts: 
Defines specific prompts for each agent to guide their responses and actions.
### Error Handling: 
Includes retry mechanisms and configuration checks to ensure smooth operation.

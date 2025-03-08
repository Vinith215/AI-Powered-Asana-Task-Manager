# AI-Powered-Asana-Task-Manager

This project is an AI-powered task management assistant that integrates OpenAI’s GPT model with Asana’s API to automate task creation. It enables users to conversationally create tasks in Asana, providing due dates and project assignments dynamically. The AI interprets user input, determines if a new task needs to be created, and executes the necessary API calls to Asana. The system follows a two-step process:

Understanding user intent and identifying if task creation is required.
Invoking the Asana API to create the task and providing feedback.

Features & Functionalities
✅ Conversational AI Task Management – Users can chat with the AI to add tasks in Asana.
✅ Dynamic Task Creation – Tasks can be scheduled for specific dates or default to today.
✅ Asana API Integration – Automatically creates tasks in specified projects.
✅ Tool Invocation – Uses OpenAI's function-calling capability to determine when to create a task.
✅ Memory Persistence – The conversation history is maintained for context-aware responses.

How It Works
User inputs a message (e.g., "Create a task: Submit report by tomorrow")
AI processes the request and determines if a task needs to be created.
AI calls Asana API to create the task with relevant details (task name, due date, project ID).
AI confirms task creation or provides an error message if the request fails.
Conversation continues with further task management requests.

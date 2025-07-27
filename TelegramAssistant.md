## Telegram AI Assistant with n8n


A smart, multimodal Agent built using [n8n](https://n8n.io) that integrates with **Telegram**, **Google Tasks**, **Google Calendar**, and **Google Sheets**. It accepts both **text and audio input**, responds using **OpenAI models**, and manages daily productivity through a **multi-agent system**.


- 🗣️ **Multimodal Input**: Accepts both text and voice messages via Telegram.

- 🧠 **Model**: Uses OpenAI's GPT models to generate intelligent replies.

- 📝 **Simple Memory**: Retains context across sessions for smoother conversations.

- 📅 **Task Tool**: When users inquire about their tasks, the assistant fetches and presents daily tasks from Google Tasks directly in Telegram.

- 🕒 **Calendar Integration Tool**: A dedicated workflow is triggered based on user requests to interact with Google Calendar—either to create new events,fetchs existing calendar events or update the calendar details.

- 🧩 **Multi-Agent Architecture**: The assistant is built using modular agents, each responsible for handling specific types of user requests (e.g., task retrieval, calendar updates, memory handling), ensuring scalability and maintainability.


![alt text](Images/telegram1.png)

![alt text](Images/telegram2.png)

## Output 

![alt text](Images/telegram-ouput.jpg)

![alt text](Images/telegramOutput.jpg)
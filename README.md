# 🤖 AI Agent with Gemini AI using n8n

This project demonstrates how to build a basic AI Agent in [n8n](https://n8n.io/) using **Google Gemini AI**, with memory and calculation capabilities. It automates the process of receiving a user query, processing it using an LLM, maintaining context, and responding with accurate results — including calculations like squaring numbers.

## 🛠️ Features

- ✅ Integrates Google Gemini AI for natural language understanding
- ✅ Maintains memory context using `Simple Memory`
- ✅ Performs calculations using the `Calculator` tool
- ✅ Fully visual, no-code workflow in n8n
- ✅ Handles real-time user input and returns intelligent responses

---

## 📌 Workflow Overview

1. **Trigger**: `When chat message received`
2. **AI Agent**:
    - Uses `Google Gemini Model` for LLM tasks
    - Utilizes `Simple Memory` for short-term memory
    - Connects to a `Calculator` for mathematical operations
3. **Output**: Displays AI-generated responses, including computed results

---

## 🧪 Example

**Input**:  
> `square of 999`  

**Output**:  
> `The square of 999 is 998001.`

---

## 🧰 Tools Used

- [n8n](https://n8n.io/) - Workflow automation platform
- [Google Gemini AI](https://ai.google.dev/gemini-api/docs) - Language model for understanding and generating text
- n8n Nodes:
  - Chat Trigger
  - AI Agent
  - Simple Memory
  - Calculator

---

## 🚀 Getting Started

1. **Clone or import** this project into your n8n workspace.
2. **Configure your credentials** for Google Gemini API.
3. Set up memory and tool nodes like:
    - Simple Memory
    - Calculator
4. Trigger the workflow using chat input.
5. Get intelligent and contextual responses instantly.

---

## 📸 Screenshot

![Workflow Screenshot](https://github.com/1900690105/AiAgent/blob/main/Screenshot%202025-07-09%20023632.png)

> Example of a working AI Agent workflow that calculates the square of a number using Gemini and n8n.

---

## 🙌 Credits

Built with ❤️ using:
- Google Gemini AI
- n8n
- Inspiration from OpenAI-style AI agents

---

## 📬 Contact

For suggestions, feedback, or collaboration opportunities:  
📧 **your.email@example.com**  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/your-profile)

---

## 🏷️ Tags

`AI Agent` `n8n` `Gemini AI` `Google AI` `Automation` `LLM` `Workflow` `Low Code` `AI Tools`

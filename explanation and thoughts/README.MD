# 🤖 Hybrid AI System: Thinker + Doer Architecture

This project is a **hybrid AI system** built from scratch. It consists of two collaborating models **"The idea is to make two models precisely Generative LLM and an AI Agent in ONE FRAMEWORK"**:

- **Model A (Thinker)**: A generative model like GPT that understands, reasons, and suggests tasks.
- **Model B (Doer)**: An agent-based system that can act in the real world — booking tickets, opening URLs, fetching data via APIs, etc.

Together, they simulate intelligent decision-making followed by real-world action — creating a powerful and practical AI assistant.

---

## 📌 Objectives

- Combine LLM (generative AI) with agent-based automation
- Enable an AI assistant to **think** and then **act**
- Learn full-stack AI engineering, tools, and architecture hands-on

---

## 🛠️ Tools & Technologies

| Layer | Tool / Framework | Description |
|-------|------------------|-------------|
| 🧠 Model A (Thinker) | OpenAI GPT / Ollama / LLaMA | Natural language reasoning and generation |
| 🦾 Model B (Doer) | LangChain Agents / Selenium / Requests | Executes tasks via browser or API |
| 🧪 Workflow Control | Python, Logic Trees | Controls communication between A and B |
| 🖥️ UI Layer | Gradio / Streamlit / CLI | Interface to interact with both models |
| 🌐 Web API | Flask / FastAPI | Handles backend routing if deployed |
| 📦 Deployment (Mandatory) | Hugging Face Spaces / Render / Localhost(it was never an option) | For hosting the hybrid system |

---

## 📐 Architecture Overview
+-------------+ +--------------------+ +----------------+
| User | ---> | Model A (Thinker) | ---> | Decision JSON |
+-------------+ +--------------------+ +--------+-------+
|
v
+-------------+-------------+
| Model B (Doer Agent) |
+-------------+-------------+
|
v
[ Executes task via API /  browser / OS automation ]
## Example real life case

---

## 🧩 Workflow

1. **User Input** — e.g., "I want to travel to Bangalore"
2. **Model A processes** intent, generates structured output like:
   ```json
   {
     "intent": "travel_booking",
     "destination": "Bangalore",
     "type": "train",
     "date": "next Monday"
   }
 3.  **Model B executes the task via tools like:**

     Google Maps API

    IRCTC or MakeMyTrip API (or Selenium simulation)

    Fetches results or executes bookings

4. **Response displayed** via UI or CLI
**📚 What we're gonna Learn**
Prompt engineering & context planning

Real-world LLM integration (OpenAI / Ollama)

Automation with LangChain agents or Selenium

API calling & data parsing

UI building (Gradio / Streamlit)

Hybrid AI design patterns
#Here's the complete overview of the plan in Phases,
**📆 Project Milestones**
**Phase	          Goal	                              Status**
**Phase 1	      Learn Python, Flask, APIs	          🔄 In Progress**
**Phase 2	      Build Thinker (Model A)	            ⬜ Not Started**
**Phase 3	      Build Doer (Model B)	              ⬜ Not Started**
**Phase 4	      Connect A ↔ B	                      ⬜ Not Started**
**Phase 5	      Add UI	                            ⬜ Not Started**
**Phase 6	      Final Testing	                      ⬜ Not Started**
**Phase 7	      Deployment	                        ⬜ Not Started**





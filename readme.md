<div align="center">
  <h1>🤖 Schedulify — AI Concierge for Workday Automation</h1>
  <p>
    A Multi-Agent AI System that autonomously manages meetings, inbox, reminders, and tasks — 
    giving professionals back their precious time.
  </p>
</div>

---

## 📌 Introduction
Workplace AI has evolved from passive chatbots to autonomous systems capable of **reasoning, collaborating, and taking actions**.  
Schedulify explores this next phase — an **AI Concierge** that understands context, makes decisions, and automates workflows end-to-end instead of merely answering questions.

---

## 🚨 Problem Statement
Modern professionals drown in:
- endless inbox threads
- scattered tasks
- manual scheduling
- forgettable reminders and deadlines

These repetitive chores silently waste **hours every week**, fragment focus, and reduce productivity.

**Schedulify solves this** by taking over administrative burden through an intelligent AI agentic workflow.  
It can:
- summarize long inbox messages
- extract actionable tasks
- detect and store reminders
- check calendar availability & schedule meetings
- maintain structured action logs

By behaving like a **reliable personal assistant that never forgets**, Schedulify frees users to focus on high-impact work.

---

## 🧠 Overview & Novelty
Schedulify is not a single assistant — it is a **multi-agent collaboration system** orchestrated to behave like a digital workforce.

### 🧩 Specialized Agents
| Agent | Capability |
|-------|-------------|
| Summarization Agent | Condenses long inbox messages |
| Scheduling Agent | Checks availability, resolves conflicts, creates calendar events |
| Task Extraction Agent | Converts unstructured text into actionable to-do lists |
| Reminder Agent | Detects deadlines and creates reminders |
| Logging Agent | Maintains structured logs for full transparency |

Instead of rigid if-else workflows, Schedulify uses:
- Natural language understanding
- Multi-step LLM reasoning
- Tool-calling
- Shared memory and state continuity

This orchestration enables the system to adapt fluidly to messy, real-world conversations.

---

## 🔁 Methodology & Flow
Every workflow follows a consistent execution pipeline:

      ┌─────────────────────────────┐
                     │  Supervisor / Router Agent   │
                     └──────────────┬───────────────┘
                                    │
  ┌─────────────────────────────────────────────────────────────────┐
  │                         Multi-Agent System                       │
  │                                                                   │
┌──────────────┐ ┌────────────────┐ ┌────────────────────┐ ┌──────────────┐
│ InboxAgent │ │ TaskExtractor │ │ ReminderAgent │ │ Scheduler │
└──────────────┘ └────────────────┘ └────────────────────┘ └──────────────┘
│ │ │ │
└───────────────┬────┴───────────────┬────┴───────────────┬──────┘
│ │ │
┌────────────────┐ ┌───────────────────┐ ┌────────────────┐
│ Inbox Tool │ │ Reminder Store │ │ Calendar Tools │
└────────────────┘ └───────────────────┘ └────────────────┘

---


## 🧰 Technology Stack
| Component | Technology |
|----------|-------------|
| Programming Language | Python |
| LLM | Google Gemini (via Google ADK) |
| Agent Framework | Google ADK (Agent / Sequential / Parallel / Loop Agents) |
| Memory | InMemorySessionService |
| Tools | Inbox, Calendar, Reminder, Logging (Dummy Stores) |
| Architecture | Modular and extensible — ready for integration via MCP |

---

## 🚀 Vision & Future Scope
Schedulify is designed for real-world expansion:
- 🔗 Connect to Gmail / Outlook inbox
- 📅 Sync with Google Calendar / MS Calendar
- 🧾 Export reminders to task platforms (Notion, Todoist, ClickUp)
- 🧠 Multi-model agent teams with reasoning feedback loops
- 🛡️ Enterprise-grade authentication and permissions

---

## 🏁 Conclusion
Schedulify demonstrates that **AI Agents can manage workdays just like real virtual assistants** — remembering context, collaborating across workflows, and taking autonomous actions.

This project serves as a blueprint for the next era of workplace automation — where AI becomes a **proactive partner**, not just a conversational bot.

---



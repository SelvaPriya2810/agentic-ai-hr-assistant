# 🤖 HR Assistant – Agentic AI App

This project is a multi-tool **Agentic AI Assistant** designed to help an HR professional at a startup plan and manage the hiring process. It demonstrates reasoning, tool orchestration, and memory retention using LangChain Agents and OpenAI.

## 📌 Objective

To build an AI-powered assistant that supports:

* 🧠 Understanding hiring needs
* ✍️ Generating role-specific job descriptions
* 🛠️ Recommending hiring pipelines
* 💸 Estimating hiring costs

---

## 💪 Tech Stack

| Tool/Tech                  | Purpose                                      |
| -------------------------- | -------------------------------------------- |
| `LangChain`                | Agent architecture, tool integration         |
| `OpenAI GPT-4`             | Natural language understanding & generation  |
| `LangChain Tools`          | Custom HR tools: JD, Plan, Cost              |
| `ConversationBufferMemory` | Memory retention for multi-step interactions |


---

## 🧠 Features

* **Multi-step reasoning**: Agent follows logical steps across tools
* **Memory**: Retains conversation context across inputs
* **Custom tools**:

  * `JobDescriptionGenerator`
  * `HiringPlanTool`
  * `CostEstimatorTool`
* **Company Personalization**: Incorporates business context and job market relevance

---

## 🚀 How to Run

1. Open the notebook in this repository
2. Add your OpenAI API key in the designated cell
3. Run all cells top to bottom
4. Start interacting with the agent using queries like:

   * "Create a job description for a DevOps Engineer"
   * "Suggest a hiring plan for a Data Analyst"
   * "How much does it cost to hire a Senior Software Engineer?"

---



## 💡 Future Enhancements

* Add salary estimation with dynamic role/region data
* Expand tools for interview questions and onboarding tasks
* Frontend UI using Streamlit or Gradio
* Deploy as an internal HR tool for startups

---

## 👩‍💻 Author

**Selvapriya Selvakumar**


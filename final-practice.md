## 12.6 Capstone Exercises – Practical AI Architecture Scenarios

These exercises are designed to **apply all chapters** (LLMs, agentic AI, MCP, RAG, multi-agent orchestration, evaluation, deployment, and frontend integration) in practical, real-world scenarios. Each scenario includes free-tier, hands-on experimentation.

---

### Exercise 1 – Restaurant POS Assistant

**Scenario:** You are building an AI-powered assistant for a restaurant POS system.  
**Tasks:**

1. Connect the AI assistant to **order database** and **menu API** via MCP endpoints.
2. Implement an **agent that takes customer orders**, checks inventory, and calculates total.
3. Add **RAG retrieval** for menu item descriptions, ingredients, and promotions.
4. Create **memory for recurring customers** to suggest favorite dishes.
5. Integrate a **React/Next.js frontend** for live interaction and streaming feedback.

---

### Exercise 2 – Multi-Tool Knowledge Assistant

**Scenario:** Build an agent capable of answering company internal queries using multiple tools.  
**Tasks:**

- Tool 1: Internal documentation search (vector DB).
- Tool 2: Calculator for numerical questions.
- Tool 3: Email reminder creation (mock API).
- Orchestrate via MCP with structured actions.

---

### Exercise 3 – Stateful Agent with Context Memory

**Scenario:** Personal AI assistant for project management.  
**Tasks:**

- Store conversation memory and context in vector DB.
- Allow agent to recall project deadlines and tasks.
- Implement Reflect-Refine loops to improve answer quality.

---

### Exercise 4 – Multi-Agent Collaboration

**Scenario:** E-commerce customer support.  
**Tasks:**

- Agent A: Handles product queries.
- Agent B: Handles shipping & delivery.
- Agent C: Handles payment issues.
- MCP server routes and coordinates requests across agents.

---

### Exercise 5 – Real-Time RAG Integration

**Scenario:** AI assistant for a knowledge base.  
**Tasks:**

- Use FAISS or Chroma vector DB for retrieval.
- Chunk and index company manuals, FAQs, and SOPs.
- Agent queries DB and summarizes answers for user.

---

### Exercise 6 – Tool Fallback & Reliability

**Scenario:** Financial calculation assistant.  
**Tasks:**

- Primary tool: Python calculation service.
- Fallback: External API calculator.
- Agent should retry or escalate if errors occur.

---

### Exercise 7 – Deployment & Monitoring

**Scenario:** Multi-agent chatbot for public Q&A.  
**Tasks:**

- Deploy MCP server locally and on free-tier cloud (Colab/Kaggle/HF Spaces).
- Set up logs, metrics, and drift monitoring.
- Evaluate token usage, latency, and structured output consistency.

---

### Exercise 8 – Safety & Evaluation

**Scenario:** AI agent for content moderation.  
**Tasks:**

- Create unit tests for prompts.
- Implement keyword & embedding filters.
- Evaluate outputs using OpenAI Evals or DeepEval alternatives.

---

### Exercise 9 – Streaming UI Integration

**Scenario:** AI assistant for technical support.  
**Tasks:**

- Connect Golang backend agent with React/Next.js streaming interface.
- Display step-by-step solutions as agent computes.
- Include fallback messages if agent fails or timeouts occur.

---

### Exercise 10 – Multi-Agent Restaurant Use Case (Capstone)

**Scenario:** Combine your Restaurant POS with multi-agent capabilities.  
**Agents & Tools:**

- Agent A: Takes orders and validates inventory.
- Agent B: Suggests promotions or upsells using RAG.
- Agent C: Generates receipts & updates backend.
- MCP server coordinates actions and maintains context.
- Frontend: React/Next.js dashboard showing live orders, memory, and recommendations.
- Bonus: Integrate evaluation pipeline to check agent consistency and correctness.

---

**Instructions for All Exercises:**

1. Use **free-tier platforms** (Colab, Kaggle, HF Spaces, local environments).
2. Wrap all tools as **MCP-compatible endpoints**.
3. Keep **structured actions and context propagation** consistent.
4. Log every step for auditing and debugging.
5. Benchmark **response time, token usage, and output correctness**.
6. Iterate using Reflect-Refine loops to improve agent responses.

> Completing these exercises provides practical mastery over **AI architecture, multi-agent systems, LLM orchestration, and full-stack integration** for real-world applications.

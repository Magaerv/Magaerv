# Hi, I'm Mariela 👋
### AI & Automation Developer — Agents · RAG · Multi-agent orchestration

I build reliable, grounded AI systems and process automations: LLM agents with
function calling and MCP, retrieval-augmented generation with grounding and
abstention, and multi-tenant automation architectures with API integration,
persistence, and failure handling.

**Stack:** TypeScript · JavaScript · Node.js · Python · PostgreSQL · SQL / NoSQL ·
REST APIs · Webhooks · OAuth 2.0 · n8n · LLM APIs · MCP · Azure AI Foundry ·
Azure AI Search · Docker · Git

---

## 🚀 Featured projects

### 🩺 RAG engine with grounding over clinical documentation
Azure OpenAI + Azure AI Search. Answers **only** from the documentation, cites the
exact source for every claim, and **abstains** when the answer isn't in the docs.
Evaluated against **42 questions (11 deliberately unanswerable): 100% correct
citations and 100% correct abstentions** — and the evaluation caught 3 defects that
manual testing had missed. Design decisions documented (semantic vs. hybrid search,
measured abstention threshold).
→ https://github.com/Magaerv/rag-documentacion-clinica

### 🔀 Multi-tenant AI classification & response system
Built on **n8n**. A single workflow serves unlimited clients by resolving tenant
configuration **at runtime**; two input channels (web form + WhatsApp);
conversational memory persisted in PostgreSQL; and **three resilience layers**
(retry → alternative provider → deterministic fallback) so the system keeps
responding when a model degrades. Architecture and design trade-offs documented.
→ https://github.com/Magaerv/Sistema-multi-tenant-de-clasificacion-con-IA

---

## 📚 Currently
Preparing **Microsoft Certified: Azure AI Apps and Agents Developer Associate**
(exam October 2026).

## 📫 Reach me
📍 Córdoba, Argentina · Open to fully-remote roles
🔗 [linkedin.com/in/magaerv](https://www.linkedin.com/in/magaerv) · ✉️ magaerv.dev@gmail.com

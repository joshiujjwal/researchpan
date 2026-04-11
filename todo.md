# researchpan — TODO

**Type:** Multi-Agent AI Research and Ideation Platform  
**Stack:** Not yet chosen (README/concept only)  
**Status:** 0% complete — no code implemented

---

## Actions To Take

- [ ] **Set up project scaffold** — Create a Node.js + TypeScript (or Python/FastAPI) backend; install core AI SDK dependencies (Anthropic/OpenAI); set up `src/`, `tests/`, and `docs/` directory structure
- [ ] **Design agent framework** — Build a `BaseAgent` class with role-specific system prompts, context window management, and an inter-agent communication protocol
- [ ] **Implement the 6 specialized agents** — Build Marketing, Sales, Engineering, Security, Product, and Finance agents with distinct expertise prompts and structured output schemas
- [ ] **Add multi-agent orchestration engine** — Implement a discussion coordinator with turn-taking, shared context accumulation, and a self-improvement feedback loop based on outcome analysis
- [ ] **Build web UI with real-time updates** — Create a frontend dashboard (React or Next.js) for inputting ideas, viewing live agent discussions via WebSocket, and exporting generated roadmaps

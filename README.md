<h1 align="center">Vikas Yadav</h1>
<p align="center">
  <b>Full-Stack Software Engineer</b> · Node · Postgres · Next.js · <b>Agentic AI</b>
</p>

<p align="center">
  I build production backends and grounded agents — the model reads, tools and SQL decide.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vikasyadav62">
    <img src="https://img.shields.io/badge/LinkedIn-Vikas%20Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/vikasyadav_eth">
    <img src="https://img.shields.io/badge/X-vikasyadav__eth-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://leetcode.com/vikas62502/">
    <img src="https://img.shields.io/badge/LeetCode-vikas62502-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=vikas62502&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="profile views" />
</p>

---

### What I work on

- **Production full stack** — Express/Node APIs, PostgreSQL, Redis, Next.js admin surfaces, payments and wallet ledgers
- **Agentic systems** — vision + tool-calling loops: extract IDs from a screenshot or a sentence, query the source of truth, answer in plain language
- **Grounding** — the LLM never invents amounts, statuses, or users; evals and model fallbacks belong in the loop, not as an afterthought

---

### How I build agents

```text
  question / screenshot
           │
           ▼
   extract structured IDs     ← Gemini (JSON only)
           │
           ▼
   tools: SQL / APIs / MCP    ← Postgres, wallet, inventory
           │
           ▼
   observe → maybe another tool
           │
           ▼
   human answer from tool output only

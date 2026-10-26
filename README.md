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
```

Interview version: **planner → tools → observe → answer**. If the tool says unpaid, the answer is unpaid.

---

### Stack

**Languages**  
`JavaScript` `TypeScript` `SQL`

**Backend**  
`Node.js` `Express` `Sequelize` `PostgreSQL` `Redis` `REST`

**Frontend**  
`React` `Next.js` `Tailwind CSS`

**Agentic AI**  
`Gemini` `tool calling` `structured output` `vision / OCR` `MCP` `evals`

**Infra**  
`Docker` `Nginx` `Linux` `AWS` `Git`

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="36" height="36" alt="javascript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="36" height="36" alt="typescript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="36" height="36" alt="nodejs"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="36" height="36" alt="express"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="36" height="36" alt="postgresql"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="36" height="36" alt="redis"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="36" height="36" alt="react"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="36" height="36" alt="nextjs"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="36" height="36" alt="docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="36" height="36" alt="aws"/>
</p>

---

### Featured

Public demos go here. Keep work-repo code private.

| Project | What it shows |
| --- | --- |
| **[ledger-agent](https://github.com/vikas62502)** *(add repo)* | Grounded dispute agent: screenshot → tools (`find_by_utr`, `find_tag_serial`, `list_txns`) → cited answer. Eval set of paid/unpaid cases. |
| **Production APIs** | High-volume Node + Postgres: wallets, payments, inventory, role-scoped access |
| **MCP (optional extra)** | Same tools exposed to Cursor — REST agent first, MCP as a thin wrapper |

---

### GitHub

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=vikas62502&show_icons=true&theme=transparent&hide_border=true&count_private=true" alt="stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vikas62502&layout=compact&theme=transparent&hide_border=true" alt="top langs" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=vikas62502&theme=transparent&hide_border=true" alt="streak" />
</p>

---

### Contact

- LinkedIn: [vikasyadav62](https://www.linkedin.com/in/vikasyadav62)
- X: [vikasyadav_eth](https://x.com/vikasyadav_eth)
- LeetCode: [vikas62502](https://leetcode.com/vikas62502/)

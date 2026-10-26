<h1 align="center">Vikas Yadav</h1>
<p align="center">
  <b>Full-Stack Engineer</b> · TypeScript · Node.js · Next.js · React Native · PostgreSQL · AWS
</p>

<p align="center">
  I ship production products — payments, wallets, and admin systems — and agents that answer from SQL and APIs.
</p>

<p align="center">
  <a href="https://vikasyadav.online">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/vikasyadav62/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:vikasyadav62502@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://x.com/vikasyadav_eth">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://leetcode.com/vikas62502/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
</p>

<p align="center">
  New Delhi · open to relocation · Backend / Full Stack / React Native
</p>

---

### Now

Full Stack Engineer at **Chairbord** (Apr 2024 – present). I build the FASTag platform end to end: React Native app, Next.js admin, and Node.js / PostgreSQL APIs for **10,000+ users**.

- Payments through **Cashfree**, **Sab Paisa**, and banking APIs, with webhook reconciliation, retries, and timeouts
- **Redis** and **BullMQ** for 800+ background jobs a day, with **35% lower read latency**
- **AWS** (ECS, ECR, S3, RDS), Docker, Nginx, and CI/CD, with Grafana, Prometheus, and Loki — **99.9% uptime**

Before that, a full-stack internship at Cadillacs: Next.js and React for 2,000+ users, and Node APIs over 1,000+ transactions.

---

### Selected work

| Work | What it shows |
| --- | --- |
| **FASTag platform** | Mobile app, admin panel, wallet ledger, and bank integrations. [Chairbord_V2](https://github.com/Vikas62502/Chairbord_V2) |
| **Inventory and quotation** | TypeScript Node backends and Next.js UIs. [inventorybackend](https://github.com/Vikas62502/inventorybackend) · [inventoryfrontend](https://github.com/Vikas62502/inventoryfrontend) · [quotation](https://github.com/Vikas62502/quotation) |
| **Grounded dispute agent** | Screenshot or sentence in, then tools (`find_by_utr`, `find_tag_serial`, `list_txns`) and a cited answer. If the tool says unpaid, the answer is unpaid. |
| **Voice assistant** | Flutter demo where the user stays in control of what the assistant can do. [Voice-Assistance-APK-GEN](https://github.com/Vikas62502/Voice-Assistance-APK-GEN) |
| **WhatsApp campaigns** | TypeScript campaign manager. [whatsapp-campaign-manager](https://github.com/Vikas62502/whatsapp-campaign-manager) |
| **Stripe payments** | A separate TypeScript payment service. [stripePaymentService](https://github.com/Vikas62502/stripePaymentService) |

---

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,express,postgresql,mongodb,redis,docker,aws,nginx,tailwind,flutter,git,linux&perline=8" alt="TypeScript, JavaScript, React, Next.js, Node.js, Express, PostgreSQL, MongoDB, Redis, Docker, AWS, Nginx, Tailwind, Flutter, Git, Linux" />
</p>

| Area | What I use |
| --- | --- |
| **Languages** | TypeScript, JavaScript, SQL, Dart |
| **Clients** | React, Next.js, React Native, Redux, Flutter, Tailwind |
| **Backend** | Node.js, Express, Sequelize, REST, microservices, Socket.IO, webhooks, JWT, RBAC, BullMQ |
| **Data** | PostgreSQL, MongoDB, MySQL, Redis |
| **Cloud** | AWS ECS, ECR, Lambda, S3, RDS, Docker, Nginx, CI/CD |
| **Quality** | Jest, Swagger, Postman, Grafana, Prometheus, Loki |
| **Agents** | Gemini tool-calling, structured output, vision / OCR, MCP, evals and model fallbacks in the loop |

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

Amounts, statuses, and users come from the database or the API. The same tools can sit behind REST first, with MCP as a thin wrapper.

---

### GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vikas62502&show_icons=true&theme=tokyonight&hide_border=true&hide=contribs&rank_icon=github" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vikas62502&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=vikas62502&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

---

<p align="center">
  <a href="https://vikasyadav.online"><b>vikasyadav.online</b></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/vikasyadav62/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:vikasyadav62502@gmail.com">vikasyadav62502@gmail.com</a>
  &nbsp;·&nbsp;
  <a href="https://x.com/vikasyadav_eth">X</a>
  &nbsp;·&nbsp;
  <a href="https://leetcode.com/vikas62502/">LeetCode</a>
</p>

[AlexKwan_GitHub_Profile_README.md](https://github.com/user-attachments/files/22800645/AlexKwan_GitHub_Profile_README.md)
# 👋 Hi there, I'm **Alex Kwan (aiexkwan)**
💻 **Software Engineer | AI Systems Integrator | WMS Architect**  
📍 Based in Manchester, UK  

---

## 🧠 About
我專注於 **Web-based WMS（倉庫管理系統）**、**AI/ML 整合** 及 **製造業自動化**。  
目前以 **TypeScript + Next.js + Supabase + GraphQL** 為核心，結合 **AI Agent Orchestration** 與 **圖譜記憶（Neo4j）**，打造可持續演進的 SaaS 生態。

- 🔧 主導多個 **TypeScript + Supabase** 專案（SaaS 化、一體化設計）  
- 🧩 研究 **MCP servers、AI memory agents、可觀測性與可視化 dashboard**
- 🧾 習慣以文件驅動（架構決策、RLS 策略、性能指標、測試策略）

---

## 🚀 Featured Projects
| Project | Description | Tech | Activity |
|:--|:--|:--|:--|
| [**web-pennine-wms**](https://github.com/aiexkwan/web-pennine-wms) | 企業級 Web WMS（掃碼標籤、RLS、報表、卡片化 UI） | TypeScript · Next.js · Supabase · GraphQL | ⏱️ Active |
| [**online-stock-control-system**](https://github.com/aiexkwan/online-stock-control-system) | 在線存貨管理（多用戶、權限、報表） | TypeScript · Supabase | 📅 Ongoing |
| [**blog-with-comments**](https://github.com/aiexkwan/blog-with-comments) | 可評論的極簡網誌平台 | TypeScript | 🕓 Active |
| [**ai-sdk-starter-xai**](https://github.com/aiexkwan/ai-sdk-starter-xai) | 建構 AI-integrated SDK 的起步範本 | TypeScript | 🧩 Active |

> 🔎 更多專案（含私有倉庫）：WMS SaaS、AI Agent 工具鏈、可視化分析卡片

---

## 🧰 Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,nextjs,react,apollo,graphql,supabase,postgres,nodejs,python,neo4j,docker,vercel,git&perline=7" />
</p>

- 前端：Next.js（App Router）、React、Tailwind、shadcn/ui  
- 後端：Supabase（Auth/RLS/Functions/Storage/Realtime）、Edge Functions  
- 資料：PostgreSQL、Row Level Security、GraphQL（Apollo + Codegen）  
- AI：RAG pipeline、Agent Orchestration（AutoGen / CrewAI / Graphiti MCP）、向量檢索  
- Dev：Docker、GitHub Actions、Playwright / Vitest

---

## 🧩 System Architecture (WMS)

```mermaid
graph TD
  A[Next.js App<br/>Cards / Dashboards] --> B[Apollo Client<br/>GraphQL]
  B --> C[Supabase GraphQL / REST]
  C --> D[(PostgreSQL)]
  C --> E[Supabase Auth<br/>RLS Policies]
  C --> F[Storage / Labels<br/>PDF / Images]
  D --> G[Views / Mat. Tables]
  A --> H[Edge Functions<br/>Webhooks / Printing]
  H --> I[Label Service<br/>QR / Barcodes]
  A --> J[Realtime Subscriptions]
  J --> C
  D --> K[Analytics Exports<br/>CSV / PDF / Excel]
```

---

## 🤖 AI Agent Orchestration (Memory-centric)

```mermaid
flowchart LR
  U[User / Ops] <---> UI[Next.js UI]
  UI --> AG[Agent Orchestrator<br/>AutoGen / CrewAI / Graphiti MCP]
  AG --> RAG[RAG Pipeline<br/>Embeddings / Chunking / Policies]
  RAG --> KB[(Supabase Vector DB<br/>Docs / SOP / Orders)]
  AG --> MEM[(Neo4j Memory Graph<br/>Episodes / Facts / Preferences)]
  AG --> SVC[Supabase Functions / Edge]
  SVC --> DB[(PostgreSQL)]
  AG --> OBS[Observability<br/>Logs / Metrics / Traces]
```

---

## 🌱 Learning & Research

- **RLS + user_metadata** 權限模型與審計追蹤  
- **Neo4j Memory Graph** & Data Lineage  
- **Automated RAG pipelines**（索引、策略、Prompt 組件化）  
- **MCP × Docker**：Tool-as-a-Service 整合  

---

## 📊 Stats
<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=aiexkwan&show_icons=true&theme=gruvbox&count_private=true" />
  <img height="160em" src="https://github-readme-streak-stats.herokuapp.com/?user=aiexkwan&theme=gruvbox" />
</p>

---

## 📫 Connect
<p align="center">
  <a href="https://github.com/aiexkwan"><img src="https://img.shields.io/badge/GitHub-000?style=flat&logo=github&logoColor=white"/></a>
  <a href="mailto:aiexkwan@gmail.com"><img src="https://img.shields.io/badge/Email-F97316?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

### ✨ “Build systems that learn — and people who evolve.”

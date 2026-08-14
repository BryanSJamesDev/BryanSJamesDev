<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f1117,50:1a1f2e,100:0f1117&height=140&section=header" width="100%"/>

<table>
<tr><td align="center" width="100%">

<h1>📊 BRYAN SAMUEL JAMES</h1>
<h3>Software Engineer &nbsp;·&nbsp; AI Agents &nbsp;·&nbsp; RAG Pipelines &nbsp;·&nbsp; Data Infrastructure</h3>
<sub>MSCS @ Northeastern University &nbsp;|&nbsp; Open to SWE / Data Engineering / AI-ML Internships & Co-ops</sub>

</td></tr>
</table>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-bryansamueljames.vercel.app-0f1117?style=flat-square&logo=vercel&logoColor=00E5A0&labelColor=1a1f2e)](https://bryansamueljames.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-Connect-0f1117?style=flat-square&logo=linkedin&logoColor=00B4D8&labelColor=1a1f2e)](https://www.linkedin.com/in/bryan-james-1530891b3/)
[![Email](https://img.shields.io/badge/EMAIL-bryansamjames%40gmail.com-0f1117?style=flat-square&logo=gmail&logoColor=FF6B6B&labelColor=1a1f2e)](mailto:bryansamjames@gmail.com)
[![Blog](https://img.shields.io/badge/BLOG-bryanjames.hashnode.dev-0f1117?style=flat-square&logo=hashnode&logoColor=A78BFA&labelColor=1a1f2e)](https://bryanjames.hashnode.dev/)

![Profile Views](https://komarev.com/ghpvc/?username=BryanSJamesDev&color=1a1f2e&style=flat-square&label=PROFILE+VIEWS)

</div>

<br/>

## 🎯 KEY METRICS DASHBOARD

<div align="center">

| ![](https://img.shields.io/badge/100%25-CATCH_RATE-00E5A0?style=for-the-badge&labelColor=0f1117) | ![](https://img.shields.io/badge/0%25-FALSE_POSITIVES-00E5A0?style=for-the-badge&labelColor=0f1117) | ![](https://img.shields.io/badge/80%25+-CITATION_COVERAGE-00B4D8?style=for-the-badge&labelColor=0f1117) | ![](https://img.shields.io/badge/200-TRIAL_EXPERIMENT-A78BFA?style=for-the-badge&labelColor=0f1117) |
|:---:|:---:|:---:|:---:|
| Contract-Guard | Contract-Guard | Policy Change Radar | Contract-Guard |

</div>

<br/>

## 📁 ABOUT

I build systems that are supposed to break, then I go verify whether they actually do. Every project follows the same pattern: naive version, guarded version, controlled experiment, real numbers reported either way.

I've worked across the stack (Python, TypeScript, Java, SQL, Go, Rust), but the thread through all of it is the same: catch problems before they become someone else's problem, and prove it with data instead of claiming it in a bullet point.

---

## 📈 FLAGSHIP PROJECTS

<table width="100%">
<tr>
<td width="50%" valign="top">

<h3>🛡️ Contract-Guard</h3>
<sub><b>Schema-Contract-Enforced Data Ingestion Platform</b></sub>

`Python` `Airflow` `dbt` `PostgreSQL`

Dual ingestion pipelines (naive vs. contract-validated) with 5-check batch validation, quarantining schema drift before it reaches the warehouse.

<table>
<tr><td>Catch Rate</td><td align="right"><b>100%</b> 🟢</td></tr>
<tr><td>False Positives</td><td align="right"><b>0%</b> 🟢</td></tr>
<tr><td>Validation Overhead</td><td align="right"><b>+15.5ms</b> 🟡</td></tr>
<tr><td>Baseline Corruption</td><td align="right"><b>100%</b> 🔴</td></tr>
</table>

[**→ View Repo**](https://github.com/BryanSJamesDev/contract-guard)

</td>
<td width="50%" valign="top">

<h3>🔍 Policy Change Radar</h3>
<sub><b>RAG Pipeline with Retrieval Evaluation</b></sub>

`Python` `FAISS` `Sentence-Transformers`

Retrieval-augmented generation grounding LLM outputs in retrieved evidence, evaluated against defined benchmarks at every pipeline stage, not vibes.

<table>
<tr><td>Citation Coverage</td><td align="right"><b>80%+</b> 🟢</td></tr>
<tr><td>Retrieval Relevance</td><td align="right"><b>70%+</b> 🟢</td></tr>
<tr><td>Vector Store</td><td align="right"><b>FAISS</b></td></tr>
</table>

[**→ View Repo**](https://github.com/BryanSJamesDev/policy-change-radar)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>📊 Portfolio Risk & Analytics Engine</h3>
<sub><b>Functional Risk Engine, Property-Tested</b></sub>

`Python` `Hypothesis` `Streamlit`

Every risk metric (VaR, CVaR, drawdown) is a pure function with zero shared mutable state, verified with property-based tests across randomly generated inputs.

<table>
<tr><td>Design</td><td align="right"><b>Pure Functions</b></td></tr>
<tr><td>Testing</td><td align="right"><b>Property-Based</b></td></tr>
<tr><td>Anomaly Model</td><td align="right"><b>GARCH(1,1)</b></td></tr>
<tr><td>Built With</td><td align="right"><b>Claude Code</b></td></tr>
</table>

[**→ View Repo**](https://github.com/BryanSJamesDev/quant-risk-engine)

</td>
<td width="50%" valign="top">

<h3>🤖 AgentFirst</h3>
<sub><b>MCP-Based AI Commerce Agent</b></sub>

`TypeScript` `React` `MCP` `Node.js`

An AI agent that browses, designs, and completes a full transaction inside ChatGPT using the Model Context Protocol, built at the InsForge Agentic Dev Tools Hackathon.

<table>
<tr><td>Payments</td><td align="right"><b>Stripe</b></td></tr>
<tr><td>Test Coverage</td><td align="right"><b>Every Layer</b></td></tr>
<tr><td>Team Size</td><td align="right"><b>3 Engineers</b></td></tr>
</table>

[**→ View Repo**](https://github.com/aryayt/insforge-hk-agentfirst)

</td>
</tr>
</table>

---

## 🧪 EXPERIMENT: CONTRACT-GUARD (200-TRIAL BENCHMARK)

<div align="center">

| Metric | Unguarded Baseline | Contract-Guard | Delta |
|:---|:---:|:---:|:---:|
| Schema drift catch rate | `0%` | **`100%`** | 🟢 +100pp |
| False positive rate | `n/a` | **`0%`** | 🟢 clean |
| Silent corruption rate | `100%` | **`0%`** | 🟢 -100pp |
| Median overhead | `n/a` | **`+15.5ms`** | 🟡 tradeoff |

</div>

---

## 🏆 HACKATHONS

<table width="100%">
<tr><td width="12%" align="center">🏆</td><td width="88%"><b>Top 20</b>, Agent Forge AI Hackathon (Silicon Valley): built <b>AutoBrief</b>, an AI meeting/project brief generator</td></tr>
<tr><td align="center">🤝</td><td><b>Agents You Love 2 Hackathon</b> (Frontier Tower, SF): built <b>Vibe-Pair</b>, a teammate/event-matching agent across GitHub, Slack, Linear, Gmail</td></tr>
<tr><td align="center">⚡</td><td><b>InsForge Agentic Dev Tools Hackathon</b>: built <b>AgentFirst</b></td></tr>
<tr><td align="center">🔧</td><td><b>Caterpillar India Hackathon</b>: built a voice-guided inspection system with step prompts, dictation, keyword triggers, image capture, and automated report validation</td></tr>
</table>

---

## ⚙️ TECH STACK

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/-Python-0f1117?style=flat-square&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/-TypeScript-0f1117?style=flat-square&logo=typescript&logoColor=3178C6)
![Java](https://img.shields.io/badge/-Java-0f1117?style=flat-square&logo=openjdk&logoColor=E76F00)
![Go](https://img.shields.io/badge/-Go-0f1117?style=flat-square&logo=go&logoColor=00ADD8)
![Rust](https://img.shields.io/badge/-Rust-0f1117?style=flat-square&logo=rust&logoColor=E4E4E4)
![C++](https://img.shields.io/badge/-C%2B%2B-0f1117?style=flat-square&logo=cplusplus&logoColor=00599C)
![SQL](https://img.shields.io/badge/-SQL-0f1117?style=flat-square&logo=postgresql&logoColor=4479A1)

**AI / ML**

![PyTorch](https://img.shields.io/badge/-PyTorch-0f1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-0f1117?style=flat-square&logo=tensorflow&logoColor=FF6F00)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-0f1117?style=flat-square&logo=huggingface&logoColor=FFD21E)
![LangChain](https://img.shields.io/badge/-LangChain-0f1117?style=flat-square&logoColor=1C3C3C)

**Data & Infrastructure**

![Airflow](https://img.shields.io/badge/-Airflow-0f1117?style=flat-square&logo=apacheairflow&logoColor=017CEE)
![Snowflake](https://img.shields.io/badge/-Snowflake-0f1117?style=flat-square&logo=snowflake&logoColor=29B5E8)
![Docker](https://img.shields.io/badge/-Docker-0f1117?style=flat-square&logo=docker&logoColor=2496ED)
![AWS](https://img.shields.io/badge/-AWS-0f1117?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Azure](https://img.shields.io/badge/-Azure-0f1117?style=flat-square&logo=microsoftazure&logoColor=0078D4)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-0f1117?style=flat-square&logo=postgresql&logoColor=4169E1)

**Web**

![React](https://img.shields.io/badge/-React-0f1117?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/-Node.js-0f1117?style=flat-square&logo=node.js&logoColor=339933)
![Next.js](https://img.shields.io/badge/-Next.js-0f1117?style=flat-square&logo=next.js&logoColor=white)

</div>

---

## 📊 GITHUB ANALYTICS

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=BryanSJamesDev&show_icons=true&theme=dark&hide_border=true&bg_color=0f1117&title_color=00E5A0&icon_color=00B4D8&text_color=c9d1d9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BryanSJamesDev&layout=compact&theme=dark&hide_border=true&bg_color=0f1117&title_color=00E5A0&text_color=c9d1d9" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=BryanSJamesDev&theme=dark&hide_border=true&background=0f1117&ring=00E5A0&fire=00B4D8&currStreakLabel=00E5A0" />

<img src="https://github-profile-trophy.vercel.app/?username=BryanSJamesDev&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" />

</div>

---

## 📉 CONTRIBUTION ACTIVITY

<div align="center">

<img src="https://raw.githubusercontent.com/BryanSJamesDev/BryanSJamesDev/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

---

## 🎓 EDUCATION

<table width="100%">
<tr>
<td width="50%">

**Master of Science, Computer Science**
Northeastern University, Boston, MA
`Sep 2025 – Dec 2027` · In Progress

</td>
<td width="50%">

**Bachelor of Technology, Information Technology**
Vellore Institute of Technology (VIT), India
`Jul 2021 – May 2025` · Completed

</td>
</tr>
</table>

---

<div align="center">

### 📡 CURRENT STATUS

![Building](https://img.shields.io/badge/BUILDING-AI_Agents_·_RAG_·_Data_Infra-00E5A0?style=for-the-badge&labelColor=0f1117)
![Open To](https://img.shields.io/badge/OPEN_TO-SWE_·_Data_Eng_·_AI--ML_Roles-00B4D8?style=for-the-badge&labelColor=0f1117)

*If you read this far, you already know more about how I build than most resumes will tell you. Let's talk.*

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f1117,50:1a1f2e,100:0f1117&height=80&section=footer" width="100%"/>

</div>

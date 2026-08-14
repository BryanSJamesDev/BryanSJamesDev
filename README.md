<div align="center">

```
$ whoami
> Bryan Samuel James — Software Engineer, MSCS @ Northeastern

$ status --current
> Building AI agents, RAG pipelines, and data infrastructure
> that hold up under a controlled experiment, not just a demo.

$ availability
> Open to Software Engineering / Data Engineering / AI-ML
> internships & co-ops
```

[![Portfolio](https://img.shields.io/badge/Portfolio-bryansamueljames.vercel.app-0b0f19?style=for-the-badge)](https://bryansamueljames.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bryan-james-1530891b3/)
[![Email](https://img.shields.io/badge/Email-bryansamjames%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bryansamjames@gmail.com)
[![Blog](https://img.shields.io/badge/Blog-bryanjames.hashnode.dev-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)](https://bryanjames.hashnode.dev/)

</div>

---

## `$ cat about.md`

I build systems that are supposed to break, and then I go verify whether they actually do. Most of my projects follow the same shape: build the naive version, build the guarded version, run a controlled experiment, and report the real numbers, not the ones that sound good in a pitch.

I've worked across the stack — Python, TypeScript, Java, SQL, Go, Rust — but the thread through all of it is the same: catch problems before they become someone else's problem.

---

## `$ ls ./flagship-projects`

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ Contract-Guard
**Schema-contract-enforced data ingestion platform**

`Python` `Airflow` `dbt` `PostgreSQL`

Dual ingestion pipelines (naive vs. contract-validated) with 5-check batch validation, quarantining schema drift before it reaches the warehouse.

**Measured, not claimed:**
- ✅ `100%` catch rate on breaking schema drift
- ✅ `0%` false positives
- ⚡ `+15.5ms` median validation overhead
- ❌ `100%` silent corruption — unguarded baseline

[**→ View Repo**](https://github.com/BryanSJamesDev/contract-guard)

</td>
<td width="50%" valign="top">

### 🔍 Policy Change Radar
**RAG pipeline with retrieval evaluation**

`Python` `FAISS` `Sentence-Transformers`

Retrieval-augmented generation grounding LLM outputs in retrieved evidence, with a custom evaluation methodology measured against defined benchmarks — not vibes.

**Measured, not claimed:**
- ✅ `80%+` citation coverage
- ✅ `70%+` retrieval relevance
- 🎯 Evaluated at every pipeline stage

[**→ View Repo**](https://github.com/BryanSJamesDev/policy-change-radar)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Portfolio Risk & Analytics Engine
**Functional risk engine, property-tested**

`Python` `Hypothesis` `Streamlit`

Every risk metric (VaR, CVaR, drawdown) is a pure function with zero shared mutable state — verified with property-based tests across randomly generated inputs, not fixed examples.

**Built with:**
- 🧮 Incremental dependency graph (no full recomputes)
- 📉 GARCH(1,1) volatility anomaly detection
- 🤖 Claude Code as part of the real workflow

[**→ View Repo**](https://github.com/BryanSJamesDev/quant-risk-engine)

</td>
<td width="50%" valign="top">

### 🤖 AgentFirst
**MCP-based AI commerce agent**

`TypeScript` `React` `MCP` `Node.js`

An AI agent that browses, designs, and completes a full transaction inside ChatGPT using the Model Context Protocol — built at the InsForge Agentic Dev Tools Hackathon.

**Shipped:**
- 💳 Native Stripe checkout integration
- ✅ Automated tests across every layer
- 👥 3-person team, Git-based code review

[**→ View Repo**](https://github.com/aryayt/insforge-hk-agentfirst)

</td>
</tr>
</table>

---

## `$ ./run-benchmark.sh --project=contract-guard`

> A 200-trial controlled experiment, guarded pipeline vs. unguarded baseline:

| Metric | Unguarded Baseline | Contract-Guard |
|---|---|---|
| Schema drift catch rate | `0%` | **`100%`** |
| False positive rate | — | **`0%`** |
| Silent corruption rate | `100%` | **`0%`** |
| Median overhead | — | **`+15.5ms`** |

---

## `$ cat hackathons.log`

- 🏆 **Top 20** — Agent Forge AI Hackathon (Silicon Valley) — built **AutoBrief**, an AI meeting/project brief generator
- 🤝 **Agents You Love 2 Hackathon** (Frontier Tower, SF) — built **Vibe-Pair**, a teammate/event-matching agent across GitHub, Slack, Linear, Gmail
- ⚡ **InsForge Agentic Dev Tools Hackathon** — built **AgentFirst**
- 🔧 **Caterpillar India Hackathon** — built a voice-guided inspection system: step prompts, dictation, keyword triggers, image capture, and automated report validation

---

## `$ cat tech-stack.json`

**Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML**
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square)

**Data & Infra**
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Web**
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

---

## `$ curl github-stats --live`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=BryanSJamesDev&show_icons=true&theme=dark&hide_border=true&bg_color=0b0f19&title_color=58a6ff&icon_color=58a6ff" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BryanSJamesDev&layout=compact&theme=dark&hide_border=true&bg_color=0b0f19&title_color=58a6ff" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=BryanSJamesDev&theme=dark&hide_border=true&background=0b0f19&ring=58a6ff&fire=58a6ff" />

</div>

---

## `$ cat education.yaml`

```yaml
current:
  degree: "Master of Science, Computer Science"
  school: "Northeastern University, Boston, MA"
  duration: "Sep 2025 – Dec 2027"

completed:
  degree: "Bachelor of Technology, Information Technology"
  school: "Vellore Institute of Technology (VIT), India"
  duration: "Jul 2021 – May 2025"
```

---

## `$ echo $STATUS`

```
> Currently building: AI agents, RAG systems, data infrastructure
> Currently learning: whatever the next project demands
> Open to: SWE / Data Engineering / AI-ML internships & co-ops
> Reach me at: bryansamjames@gmail.com
```

<div align="center">

*If you read this far, you already know more about how I build than most resumes will tell you. Let's talk.*

</div>

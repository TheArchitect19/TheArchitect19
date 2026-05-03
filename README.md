<!-- ──────────────────────────────────────────────────────────────────── -->
<!--                  AYUSH KUMAR · Engineering Profile                   -->
<!-- ──────────────────────────────────────────────────────────────────── -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=42&duration=3000&pause=800&color=FFFFFF&center=true&vCenter=true&width=720&height=70&lines=Ayush+Kumar;Backend+%C2%B7+Platform+%C2%B7+AI+Engineer;Building+systems+that+stay+up+at+3am" alt="typing" />

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/STATUS-shipping_in_production-white?style=flat-square&labelColor=000000&color=white">
  <img src="https://img.shields.io/badge/STATUS-shipping_in_production-black?style=flat-square&labelColor=ffffff&color=black" />
</picture>
&nbsp;
<img src="https://img.shields.io/badge/BASED-Hyderabad,_IN-blue?style=flat-square&labelColor=000000&color=blue" />
&nbsp;
<img src="https://img.shields.io/badge/OPEN_TO-senior_roles-success?style=flat-square&labelColor=000000&color=00C896" />

<br/><br/>

<a href="mailto:ayush.krsh9@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://linkedin.com/in/ayushkumar1907">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://leetcode.com/ayush-eth">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
</a>
<a href="https://codeforces.com/profile/plutus.10">
  <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" />
</a>

</div>

<br/>

---

<table border="0">
<tr>
<td width="60%" valign="top">

### `// the way I build`

I build backend systems that handle real load — not toy demos.

The work I'm proudest of usually looks boring from the outside: a sharded write path that doesn't fall over at **1B rows**, a workflow engine that uses **Kahn's algorithm** because cycles are bugs not features, a **300M parameter SLM** I trained from scratch on my laptop because I wanted to *actually* understand transformers — not import them.

I don't care about being right. I care about systems that stay up at 3am.

</td>
<td width="40%" valign="top">

### `// currently`

```yaml
role:     platform engineer
company:  Steps AI
shipping: agent infrastructure
training: 300M param SLM
mood:     write more, talk less
```

</td>
</tr>
</table>

<br/>

<div align="center">

`▸ ─────────────────────────────────────────────────────────────── ◂`

</div>

<br/>

## <img src="https://img.icons8.com/fluency/32/briefcase.png" width="22"/> &nbsp;`01 — work`

<br/>

<table>
<tr>
<td width="80" align="center" valign="top">
<br/>
<img src="https://img.icons8.com/fluency/64/artificial-intelligence.png" width="56"/>
</td>
<td valign="top">

#### **Steps AI** &nbsp;·&nbsp; *AI / Platform Engineer*
<sub>`oct '25 — present` &nbsp;·&nbsp; Hyderabad, IN</sub>

▸ Built a **DAG-based AI workflow engine** with **Kahn's topological sort**, per-step error policies (Fail/Skip/Retry), **DLQ** for failed runs, and **139+ integrations** across 24 providers.

▸ Engineered a **multi-tenant agent hosting platform** — tenants connect via **CNAME**, platform dynamically provisions **path-scoped Kubernetes routes** per tenant, resolving host headers to isolated agent pods.

▸ Designed a **human-in-the-loop interrupt system** — agent pauses on low confidence, enqueues to **SQS**, support agent joins via **WebSocket**, end-user receives live status over **SSE**.

▸ Hardened **Kubernetes Ingress** with TLS, environment isolation, dynamic per-tenant provisioning.

`Kubernetes` `LangChain` `LangGraph` `SQS` `WebSocket` `SSE`

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="80" align="center" valign="top">
<br/>
<img src="https://img.icons8.com/fluency/64/database.png" width="56"/>
</td>
<td valign="top">

#### **Xequalto Analytics** &nbsp;·&nbsp; *Software Development Engineer*
<sub>`aug '24 — oct '25` &nbsp;·&nbsp; Remote, IN</sub>

▸ Designed an **ETL pipeline** to ingest **1B+ rows** with batched ingestion, transformation, and fault-tolerant loading into **PostgreSQL** at scale.

▸ Architected **hash-based horizontal table sharding** in PostgreSQL for writes; replicated to **ClickHouse** for OLAP reads, with fan-out queries aggregated at the app layer.

▸ Integrated **Protocol Buffers** for service-to-service contracts → **60% serialization gain**.

▸ Designed compact **binary encoding** to replace JSON in hot paths → **40% payload cut**.

▸ Migrated to **Redis connection pool**, exposed **GraphQL APIs**, engineered **zero-downtime deploys** via **ArgoCD + OIDC + ECR**.

`PostgreSQL` `ClickHouse` `Protobuf` `Redis` `ArgoCD` `GraphQL`

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="80" align="center" valign="top">
<br/>
<img src="https://img.icons8.com/fluency/64/source-code.png" width="56"/>
</td>
<td valign="top">

#### **Gokapture** &nbsp;·&nbsp; *Software Engineer Intern*
<sub>`feb '23 — aug '24` &nbsp;·&nbsp; Remote, IN</sub>

▸ Contributed to a high-throughput **Go service** powering the core **Generative AI image pipeline** — refactored goroutine concurrency, reduced median latency under load.

▸ Built an internal **branch-preview deployment system in Go** — engineers push a branch, get a live URL (Vercel-style, internal infra).

▸ Established a **local GitHub Actions sandbox using `act`** — feedback loop cut from minutes to seconds.

▸ Set up **ngrok tunnels** for webhook + 3rd-party API testing without staging dependencies.

`Go` `GitHub Actions` `Docker` `ngrok`

</td>
</tr>
</table>

<br/>

<div align="center">

`▸ ─────────────────────────────────────────────────────────────── ◂`

</div>

<br/>

## <img src="https://img.icons8.com/fluency/32/rocket.png" width="22"/> &nbsp;`02 — what I'm building`

<br/>

<table>
<tr>
<td width="50%" valign="top">

<div align="center">

<img src="https://img.icons8.com/fluency/96/brain.png" width="64"/>

### **SLM** · LinkedIn Post Generator

</div>

```yaml
parameters:    300M
architecture:  decoder-only · custom hybrid
positional:    RoPE
attention:     multi-head causal · KV-cache
ffn:           SwiGLU
norm:          Pre-RMSNorm
tokenizer:     custom BPE (from scratch)
training:      bf16 · MPS · Apple M5
```

> Built ground-up. No HuggingFace weights, no pretrained base. Tokenizer, transformer blocks, training loop — everything written from zero.

</td>
<td width="50%" valign="top">

<div align="center">

<img src="https://img.icons8.com/fluency/96/financial-growth.png" width="64"/>

### **Quper** · FinOps Platform

</div>

```yaml
status:        in production
stack:         go · postgres · clickhouse
role:          led product team end-to-end
adopted by:    The Chatterjee Group
               (45-country conglomerate)
               Cricut (US consumer tech)
```

> Real-time cloud cost intelligence. Took it from architecture to delivery. Currently running inside enterprise infrastructure across multiple Fortune-class clients.

</td>
</tr>
</table>

<br/>

<div align="center">

`▸ ─────────────────────────────────────────────────────────────── ◂`

</div>

<br/>

## <img src="https://img.icons8.com/fluency/32/maintenance.png" width="22"/> &nbsp;`03 — stack`

<div align="center">

<table>
<tr><td><b>Languages</b></td><td>

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

</td></tr>
<tr><td><b>Backend</b></td><td>

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GoFiber](https://img.shields.io/badge/Fiber-00ACD7?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

</td></tr>
<tr><td><b>Data</b></td><td>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

</td></tr>
<tr><td><b>Infra</b></td><td>

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</td></tr>
<tr><td><b>AI · ML</b></td><td>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=flat-square&logo=langchain&logoColor=white)
![Metal](https://img.shields.io/badge/Metal_MPS-000000?style=flat-square&logo=apple&logoColor=white)

</td></tr>
<tr><td><b>Protocols</b></td><td>

![Protobuf](https://img.shields.io/badge/Protobuf-4285F4?style=flat-square&logo=google&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=google&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)

</td></tr>
</table>

</div>

<br/>

<div align="center">

`▸ ─────────────────────────────────────────────────────────────── ◂`

</div>

<br/>

## <img src="https://img.icons8.com/fluency/32/medal.png" width="22"/> &nbsp;`04 — proof of work`

<br/>

<table>
<tr>
<td align="center" width="20%">
<img src="https://img.icons8.com/fluency/64/leadership.png" width="44"/>
<br/><sub><b>FLAGSHIP</b></sub>
<br/><b>Quper</b>
<br/><sub>used by TCG + Cricut</sub>
</td>
<td align="center" width="20%">
<img src="https://img.icons8.com/fluency/64/trophy.png" width="44"/>
<br/><sub><b>COMPETITIVE</b></sub>
<br/><b>ICPC '23</b>
<br/><sub>regionalist · rank 73</sub>
</td>
<td align="center" width="20%">
<img src="https://img.icons8.com/fluency/64/code.png" width="44"/>
<br/><sub><b>ALGORITHMS</b></sub>
<br/><b>LeetCode</b>
<br/><sub>top 7% globally</sub>
</td>
<td align="center" width="20%">
<img src="https://img.icons8.com/fluency/64/launched-rocket.png" width="44"/>
<br/><sub><b>SCALE</b></sub>
<br/><b>10K+ users</b>
<br/><sub>asksenior backend</sub>
</td>
<td align="center" width="20%">
<img src="https://img.icons8.com/fluency/64/blockchain-technology.png" width="44"/>
<br/><sub><b>HACKATHON</b></sub>
<br/><b>Hack-O-Octo</b>
<br/><sub>winner · blockchain</sub>
</td>
</tr>
</table>

<br/>

<div align="center">

`▸ ─────────────────────────────────────────────────────────────── ◂`

</div>

<br/>

## <img src="https://img.icons8.com/fluency/32/github.png" width="22"/> &nbsp;`05 — open source`

<table>
<tr>
<td width="50%" valign="top">

<img src="https://img.icons8.com/fluency/48/test-tube.png" width="32" align="left" style="margin-right:10px"/>

#### [Keploy](https://github.com/keploy/keploy)
Refactored core modules to NestJS, built repo analytics tooling for the API testing platform.

</td>
<td width="50%" valign="top">

<img src="https://img.icons8.com/fluency/48/cloud-development.png" width="32" align="left" style="margin-right:10px"/>

#### [EvalAI · CloudCV](https://github.com/Cloud-CV/EvalAI)
100+ tests added, full PostgreSQL upgrade, comprehensive API documentation rewrite.

</td>
</tr>
</table>

<br/>

<div align="center">

`▸ ─────────────────────────────────────────────────────────────── ◂`

</div>

<br/>

## <img src="https://img.icons8.com/fluency/32/combo-chart.png" width="22"/> &nbsp;`06 — telemetry`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=TheArchitect19&show_icons=true&theme=transparent&hide_border=true&title_color=ffffff&icon_color=ffffff&text_color=8b949e&ring_color=ffffff" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=TheArchitect19&theme=transparent&hide_border=true&ring=ffffff&fire=ffffff&currStreakLabel=ffffff&sideLabels=8b949e&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff" />

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=TheArchitect19&bg_color=00000000&color=ffffff&line=ffffff&point=ffffff&area=true&area_color=ffffff&hide_border=true" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=TheArchitect19&theme=nord&no-frame=true&no-bg=true&row=1&column=7&margin-w=10" />

</div>

<br/>

---

<div align="center">

```
─────────────────────────────────────────────
        if you build cool things,
            we should talk.
─────────────────────────────────────────────
```

<br/>

<img src="https://komarev.com/ghpvc/?username=TheArchitect19&label=PROFILE+VIEWS&color=000000&style=flat-square" />

<sub>last commit: just now &nbsp;·&nbsp; always shipping</sub>

</div>

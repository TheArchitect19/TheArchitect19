<!-- ──────────────────────────────────────────────────────────────────── -->
<!--                                                                      -->
<!--   AYUSH KUMAR · 001                                                  -->
<!--   Last edited: 2026                                                  -->
<!--                                                                      -->
<!-- ──────────────────────────────────────────────────────────────────── -->

<div align="center">

```
                                                                       
   █████╗ ██╗   ██╗██╗   ██╗███████╗██╗  ██╗     ██╗  ██╗██████╗     
  ██╔══██╗╚██╗ ██╔╝██║   ██║██╔════╝██║  ██║     ██║ ██╔╝██╔══██╗    
  ███████║ ╚████╔╝ ██║   ██║███████╗███████║     █████╔╝ ██████╔╝    
  ██╔══██║  ╚██╔╝  ██║   ██║╚════██║██╔══██║     ██╔═██╗ ██╔══██╗    
  ██║  ██║   ██║   ╚██████╔╝███████║██║  ██║     ██║  ██╗██║  ██║    
  ╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚══════╝╚═╝  ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝    
                                                                       
  ─────────────────────────────────────────────────────────────────    
   engineer · systems thinker · ships things that don't break          
  ─────────────────────────────────────────────────────────────────    
```

</div>

<p align="center">
  <a href="mailto:ayush.krsh9@gmail.com"><img src="https://img.shields.io/badge/-mail-000000?style=for-the-badge&logoColor=white&labelColor=000000" /></a>
  <a href="https://linkedin.com/in/ayushkumar1907"><img src="https://img.shields.io/badge/-linkedin-000000?style=for-the-badge&logoColor=white&labelColor=000000" /></a>
  <a href="https://leetcode.com/ayush-eth"><img src="https://img.shields.io/badge/-leetcode-000000?style=for-the-badge&logoColor=white&labelColor=000000" /></a>
  <a href="https://codeforces.com/profile/plutus.10"><img src="https://img.shields.io/badge/-codeforces-000000?style=for-the-badge&logoColor=white&labelColor=000000" /></a>
</p>

<br/>

---

<table>
<tr>
<td width="55%" valign="top">

### `// the way I build`

I build backend systems that handle real load — not toy demos.

The work I'm proudest of usually looks boring from the outside: a sharded write path that doesn't fall over at 1B rows. A workflow engine that uses Kahn's algorithm because cycles are bugs, not features. A tokenizer written from scratch because I wanted to *actually* understand BPE, not import it.

I don't care about being right. I care about systems that stay up at 3am.

</td>
<td width="45%" valign="top">

### `// currently`

```
┌─────────────────────────────────────┐
│                                     │
│  ▸ steps ai · platform engineer     │
│  ▸ shipping agent infrastructure    │
│  ▸ training a 300M param SLM        │
│  ▸ writing more, talking less       │
│                                     │
└─────────────────────────────────────┘
```

</td>
</tr>
</table>

<br/>

---

## `01 — work`

```
╭─ STEPS AI ─────────────────────────────────  oct '25 → present ─╮
│                                                                  │
│   AI Engineer · Platform Engineer                                │
│                                                                  │
│   ▸  DAG-based AI workflow engine — Kahn's topological sort,     │
│      per-step error policies, DLQ, 139+ integrations             │
│                                                                  │
│   ▸  Multi-tenant agent hosting — tenants connect via CNAME,     │
│      platform provisions path-scoped K8s routes per tenant       │
│                                                                  │
│   ▸  Human-in-the-loop interrupt system — SQS for handoff,       │
│      WebSocket for support agent, SSE for end-user updates       │
│                                                                  │
│   ▸  Hardened K8s ingress with TLS, env isolation, dynamic       │
│      tenant provisioning                                         │
│                                                                  │
╰──────────────────────────────────────────────────────────────────╯

╭─ XEQUALTO ANALYTICS ───────────────────────  aug '24 → oct '25 ─╮
│                                                                  │
│   Software Development Engineer                                  │
│                                                                  │
│   ▸  ETL pipeline → ingest 1B+ rows, batched, fault-tolerant     │
│   ▸  Hash-based horizontal sharding in PostgreSQL → ClickHouse   │
│      replication for OLAP reads, fan-out aggregation             │
│   ▸  Protocol Buffers across services → 60% serialization gain   │
│   ▸  Custom binary encoding in hot paths → 40% payload cut       │
│   ▸  Redis connection pooling for burst traffic                  │
│   ▸  GraphQL APIs for client-driven data querying                │
│                                                                  │
╰──────────────────────────────────────────────────────────────────╯

╭─ GOKAPTURE ────────────────────────────────  feb '23 → aug '24 ─╮
│                                                                  │
│   Software Engineer Intern                                       │
│                                                                  │
│   ▸  Go service powering generative AI image pipeline —          │
│      goroutine concurrency tuning, hot-path latency reduction    │
│   ▸  Built internal branch preview deploy system in Go           │
│      (Vercel-style, but for internal infra)                      │
│   ▸  Local CI sandbox with `act` — minutes → seconds feedback    │
│   ▸  ngrok tunnels for webhook + 3rd-party integration testing   │
│                                                                  │
╰──────────────────────────────────────────────────────────────────╯
```

<br/>

## `02 — what I'm building`

<table>
<tr>
<td width="50%" valign="top">

#### ▸ SLM · LinkedIn Post Generator

```
language       PyTorch + Metal/MPS
parameters     300M
architecture   decoder-only · custom hybrid
positional     RoPE
attention      multi-head causal · KV-cache
ffn            SwiGLU
norm           Pre-RMSNorm
tokenizer      custom BPE (from scratch)
training       bf16 mixed-precision · M5 chip
```

Built ground-up. No HuggingFace weights, no pretrained base. Tokenizer, transformer blocks, training loop — everything written from zero.

</td>
<td width="50%" valign="top">

#### ▸ Quper · FinOps Platform

```
status         in production
stack          go · postgres · clickhouse
role           led product team end-to-end
adopted by     The Chatterjee Group
               (45-country conglomerate)
               Cricut (US consumer tech)
```

Real-time cloud cost intelligence. Took it from architecture to delivery. Currently running inside enterprise infra.

</td>
</tr>
</table>

<br/>

## `03 — stack`

```
┌─ languages ──────────────────────────────────────────────────────────┐
   go      python      typescript      c++      java      c
└──────────────────────────────────────────────────────────────────────┘

┌─ backend ────────────────────────────────────────────────────────────┐
   nestjs      go fiber      fastapi      node.js      graphql
└──────────────────────────────────────────────────────────────────────┘

┌─ data ───────────────────────────────────────────────────────────────┐
   postgresql      clickhouse      redis      mongodb      dynamodb
└──────────────────────────────────────────────────────────────────────┘

┌─ infra ──────────────────────────────────────────────────────────────┐
   kubernetes      argocd      docker      ecr      oidc      aws
└──────────────────────────────────────────────────────────────────────┘

┌─ ai · ml ────────────────────────────────────────────────────────────┐
   pytorch      langchain      langgraph      metal/mps      bpe
└──────────────────────────────────────────────────────────────────────┘

┌─ protocols ──────────────────────────────────────────────────────────┐
   protobuf      websocket      sse      sqs      rest      grpc
└──────────────────────────────────────────────────────────────────────┘
```

<br/>

## `04 — proof of work`

<table>
<tr>
<td align="center" width="25%">
<sub>COMPETITIVE</sub><br/>
<b>ICPC '23</b><br/>
<sub>regionalist · rank 73</sub>
</td>
<td align="center" width="25%">
<sub>ALGORITHMS</sub><br/>
<b>LeetCode</b><br/>
<sub>top 7% globally</sub>
</td>
<td align="center" width="25%">
<sub>SCALE</sub><br/>
<b>10K+ users</b><br/>
<sub>asksenior backend</sub>
</td>
<td align="center" width="25%">
<sub>HACKATHON</sub><br/>
<b>Hack-O-Octo</b><br/>
<sub>winner · blockchain</sub>
</td>
</tr>
</table>

<br/>

## `05 — open source`

```
keploy       →  refactored core modules to NestJS, built repo analytics
evalai       →  100+ tests added, postgres upgrade, full API docs rewrite
```

<br/>

---

## `06 — telemetry`

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=TheArchitect19&show_icons=true&theme=transparent&hide_border=true&title_color=ffffff&icon_color=ffffff&text_color=8b949e&ring_color=ffffff" />
  <img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=TheArchitect19&theme=transparent&hide_border=true&ring=ffffff&fire=ffffff&currStreakLabel=ffffff&sideLabels=8b949e&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff" />
</div>

<div align="center">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=TheArchitect19&bg_color=00000000&color=ffffff&line=ffffff&point=ffffff&area=true&area_color=ffffff&hide_border=true" />
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

<sub>last commit: just now · always shipping</sub>

</div>

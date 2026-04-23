<!-- prempradip/prem-pradeep · To pin this README on https://github.com/prempradip create a public repo named prempradip/prempradip -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:161b22,100:238636&height=165&section=header&text=Prem%20Pradeep&fontSize=48&fontColor=f0f6fc&fontAlignY=36&animation=twinkling&desc=Product%20%E2%80%A2%20Tools%20%E2%80%A2%20Systems&descAlignY=56&descSize=15&descColor=8b949e&font=Inter" alt="Prem Pradeep — header" />
</p>

<p align="center">
  <a href="https://www.prempradeep.com/"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=22&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=780&lines=Externalizing+judgment+into+frameworks%2C+instruments%2C+and+code;Making+trade-offs+legible+so+teams+can+inspect%2C+iterate%2C+reuse;Portfolio+of+decision+systems+%E2%80%94+not+a+blog" alt="Animated taglines" /></a>
</p>

<p align="center">
  <strong>Thesis:</strong> Product judgment improves when thinking is <strong>externalized</strong>—into frameworks, instruments, and code—so teams can inspect, iterate, and reuse it.
</p>

<p align="center">
  <a href="https://www.prempradeep.com/"><img src="https://img.shields.io/badge/Hub-prempradeep.com-21262d?style=for-the-badge&logo=safari&logoColor=58A6FF" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/prempradeep/"><img src="https://img.shields.io/badge/LinkedIn-Prem%20Pradeep-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://orcid.org/0009-0009-4940-7884"><img src="https://img.shields.io/badge/ORCID-0009--0009--4940--7884-a6ce39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID" /></a>
  <a href="https://github.com/prempradip"><img src="https://komarev.com/ghpvc/?username=prempradip&label=Profile%20views&color=0e1117&style=for-the-badge" alt="Profile views" /></a>
</p>

<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=30363d&height=1" width="100%" alt="" />

### Operating model

| Layer | Role | Primary surface |
|:------|:-----|:----------------|
| **Cognitive** | Make trade-offs legible (prioritization, DVF, JTBD, metrics) | [Tools & assessments](https://www.prempradeep.com/) |
| **Instrumental** | Turn abstractions into repeatable workflows (generators, planners, dashboards) | Same hub; outputs are **auditable artifacts** |
| **Computational** | Stress-test ideas with agents, models, and thin vertical slices | Repositories below |

<p align="center"><sub>Design rule: each layer must <strong>compose</strong>—frameworks feed tools; tools inform experiments; experiments tighten the next framework revision.</sub></p>

### Architecture of the public hub

The site is structured as a **portfolio of decision systems**, not a blog: discrete tools, linked assessments, and vocabulary (ProdZ) that reduce ambiguity in product conversations.

| Class | Examples (on-site) |
|:------|:-------------------|
| **Planning & narrative** | User Story Generator, Product Roadmap Planner |
| **Allocation & scoring** | Feature Prioritization (RICE, MoSCoW, …), DVF Exercise, Advanced DVF (NPV / IRR / payback, portfolio view) |
| **Understanding demand** | Jobs to Be Done |
| **Measurement** | Product Metrics Dashboard |
| **Governance & ethics** | PM Competency Assessment, Dark Patterns Website Assessment |

**SaaS verticals** (applied systems): [Academic Micro SaaS](https://www.prempradeep.com/saas/academic-micro-saas) · [PreJoin IQ](https://www.prempradeep.com/saas/prejoin-iq)

### Repository topology

Classification by **intent**, not star count.

| Intent | Repository | Stack | Analytical note |
|:-------|:-----------|:------|:----------------|
| **Decision insight** | [`dvf-insight`](https://github.com/prempradip/dvf-insight) | TypeScript | Explores how DVF-style judgment is surfaced in software |
| **Economic framing** | [`wheel-wise-tco`](https://github.com/prempradip/wheel-wise-tco) | TypeScript | Total cost and trade-off visibility as a first-class object |
| **Agentic media** | [`AI-Meme-Agent`](https://github.com/prempradip/AI-Meme-Agent) | TypeScript | Bounded agent behavior: creative output with constrained inputs |
| **Information synthesis** | [`AI-news-researcher`](https://github.com/prempradip/AI-news-researcher) | Python | Retrieval + reasoning over noisy streams |
| **Exploration surface** | [`prem-product-playground-98`](https://github.com/prempradip/prem-product-playground-98) | TypeScript | Sandboxed product hypotheses and UI mechanics |
| **Baseline interaction** | [`snake_game`](https://github.com/prempradip/snake_game) | HTML | Minimal state machine + loop; useful as a control |

### System map

```mermaid
flowchart LR
  subgraph Hub["prempradeep.com"]
    F["Frameworks & tools"]
    A["Assessments"]
  end
  subgraph GH["GitHub experiments"]
    D["Decision / economics\n(dvf-insight, wheel-wise-tco)"]
    AI["Agents & research\n(AI-Meme-Agent, AI-news-researcher)"]
    P["Playground / baseline\n(prem-product-playground-98, snake_game)"]
  end
  F --> D
  F --> AI
  A --> AI
  D --> P
  AI --> P
```

<p align="center"><sub>The <strong>hub</strong> encodes stable mental models; <strong>repos</strong> test where those models break when automated or scaled.</sub></p>

### Implementation substrate

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=0d1117" alt="React" />
</p>

<p align="center"><sub>TypeScript where <strong>typed boundaries</strong> matter (UI, agents, financial scaffolding). Python for <strong>pipeline ergonomics</strong> and research. HTML for deliberately <strong>small surface area</strong>.</sub></p>

<details>
<summary><strong>Telemetry</strong> — descriptive, not normative</summary>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=prempradip&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&hide_title=false&title_color=58A6FF&icon_color=58A6FF" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prempradip&layout=compact&theme=github_dark&hide_border=true&langs_count=8&title_color=58A6FF" alt="Top languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.demolab.com/?user=prempradip&theme=github-dark&hide_border=true&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="Contribution streak" />
</p>

*Stats summarize activity distribution, not merit.*

</details>

<br />

<p align="center">
  <strong>Closing invariant:</strong> If an idea survives contact with <strong>structure</strong>, <strong>users</strong>, and <strong>code</strong>, it earns a place in the stack.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:238636,100:0d1117&height=120&section=footer&fontSize=42&fontColor=f0f6fc&animation=twinkling" alt="Footer wave" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=venom&height=250&color=0:FF2800,60:A6051A,100:FFF200&text=OMJEE%20R%20GIRI&fontSize=56&fontColor=FFFFFF&fontAlignY=36&desc=AI%20%2F%20ML%20ENGINEER%20%E2%80%A2%20DATA%20SCIENCE%20%E2%80%A2%20SYSTEMS%20BUILDER&descAlignY=55&descSize=16&animation=fadeIn">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=250&color=0:FF2800,100:FFF200&text=OMJEE%20R%20GIRI&fontSize=56&fontColor=FFFFFF" width="100%">
</picture>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=1300&pause=400&color=FFF200&multiline=true&width=840&height=130&lines=%5B+formation+lap+%5D+retrieval+stack+warming...;%5B+green+%5D+qdrant+%C2%B7+bge-m3+%C2%B7+langgraph+%C2%B7+16+nodes+online;%5B+green+%5D+3+gates+armed+%E2%80%94+safety+%7C+evidence+%7C+citation;%5B+lights+out+%5D+an+answer+is+only+valid+if+every+claim+resolves" alt="formation lap">

<br>

<a href="#-driver"><img src="https://img.shields.io/badge/01_DRIVER-0D1117?style=for-the-badge&labelColor=FF2800&color=0D1117"></a>
<a href="#-timing-tower"><img src="https://img.shields.io/badge/02_TIMING-0D1117?style=for-the-badge&labelColor=FFF200&color=0D1117"></a>
<a href="#-sector-splits"><img src="https://img.shields.io/badge/03_SECTORS-0D1117?style=for-the-badge&labelColor=FF2800&color=0D1117"></a>
<a href="#-telemetry"><img src="https://img.shields.io/badge/04_TELEMETRY-0D1117?style=for-the-badge&labelColor=FFF200&color=0D1117"></a>
<a href="#-race-history"><img src="https://img.shields.io/badge/05_HISTORY-0D1117?style=for-the-badge&labelColor=FF2800&color=0D1117"></a>

<br><br>

<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3DThe0NEAboveALL&query=%24.result%5B0%5D.rating&label=CF%20RATING%20%E2%97%8F%20LIVE&labelColor=0D1117&color=FF2800&style=for-the-badge&logo=codeforces&logoColor=FFF200&cacheSeconds=3600">
<img src="https://img.shields.io/github/last-commit/TheOneAbovELL/legal-lens-backend?style=for-the-badge&label=LAST%20PUSH&labelColor=0D1117&color=FFF200&logo=git&logoColor=FF2800">
<img src="https://komarev.com/ghpvc/?username=TheOneAbovELL&label=VISITORS&color=FF2800&style=for-the-badge">
<img src="https://img.shields.io/badge/GRID-OPEN_TO_INTERNSHIPS-FFF200?style=for-the-badge&labelColor=0D1117">

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2800,50:FFF200,100:FF2800&height=4&section=header" width="100%">

## 🏎 driver

```console
omjee@scuderia:~$ ./driver --card
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   D R I V E R      Omjee R Giri                                  ║
║                                                                  ║
║   ACADEMY          B.Tech · Artificial Intelligence & ML         ║
║                    Birla Institute of Technology, Mesra          ║
║                                                                  ║
║                    BS · Data Science and Applications            ║
║                    Indian Institute of Technology, Madras        ║
║                                              [ run concurrently ]║
╚══════════════════════════════════════════════════════════════════╝

omjee@scuderia:~$ ./circuit --loop
        ╭────────────── UNDERSTAND ──────────────╮
        │                                        ▼
     OPTIMIZE                                  BUILD
        ▲                                        │
        ╰──── ITERATE ◀───── MEASURE ◀───────────╯

   S1  data arrives clean ................................. [ GREEN ]
   S2  retrieval is measurable ............................ [ GREEN ]
   S3  the API answers when a provider goes down .......... [ GREEN ]
   ──  "if it isn't measured, it's a guess"
```

> **I don't want to only build models. I want to understand the system around them.**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FFF200,50:FF2800,100:FFF200&height=4&section=header" width="100%">

## 🏁 timing tower

```console
┌─────┬─────┬────────────────────┬───────────────────┬───────────┬──────────┐
│ POS │ No. │ PROGRAMME          │ SECTOR            │ STATUS    │ INTERVAL │
├─────┼─────┼────────────────────┼───────────────────┼───────────┼──────────┤
│ P1  │ 01  │ LEGAL LENS         │ AI / RETRIEVAL    │ ▰ RUNNING │    —     │
│ P2  │ 02  │ qEEG SUBTYPING     │ RESEARCH / SIGNAL │ ▱ IN PITS │  +0.482  │
│ P3  │ 03  │ ARGUS              │ QUANTITATIVE      │ ▰ OUT LAP │  +1.139  │
└─────┴─────┴────────────────────┴───────────────────┴───────────┴──────────┘
  ▰ active   ▱ research prototype — no results reported, by design
```

<table>
<tr>
<td width="33%" valign="top">

### `01` LEGAL LENS
<img src="https://img.shields.io/badge/P1-FF2800?style=flat-square&labelColor=0D1117"> <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/legal-lens-backend?style=flat-square&label=&labelColor=0D1117&color=FFF200">

16-node **LangGraph** pipeline over hybrid search on **Qdrant**. Dense + sparse + metadata fused with weighted RRF, IPC ↔ BNS provisions mapped as citable entries, typed SSE events to the client.

**Three gates.** Two of them can end a request before a single token is generated — weak evidence returns a fixed reply, an unknown citation ID rejects the whole answer.

Kept honest by Recall@K · MRR · nDCG · citation validity.

<a href="https://github.com/TheOneAbovELL/legal-lens-backend"><img src="https://img.shields.io/badge/REPO-0D1117?style=flat-square&logo=github&logoColor=FF2800"></a>
<a href="https://personal-portfolio-website-lilac-xi.vercel.app/work/legal-lens"><img src="https://img.shields.io/badge/CASE_STUDY-0D1117?style=flat-square&logo=vercel&logoColor=FFF200"></a>

</td>
<td width="33%" valign="top">

### `02` qEEG SUBTYPING
<img src="https://img.shields.io/badge/P2-A6051A?style=flat-square&labelColor=0D1117"> <img src="https://img.shields.io/badge/RESEARCH-0D1117?style=flat-square&color=FFF200">

19 channels → filter, ICA, re-reference, epoch → spectral, connectivity and nonlinear features → **three branches, one signal**.

A 1D-CNN reads local temporal pattern. A GCN reads *measured* electrode coherence. A Transformer reads long-range dependency. Fused before a six-class output.

> No results reported. Not clinically validated. Stated plainly rather than quietly.

<a href="https://personal-portfolio-website-lilac-xi.vercel.app/work/qeeg"><img src="https://img.shields.io/badge/CASE_STUDY-0D1117?style=flat-square&logo=vercel&logoColor=FFF200"></a>

</td>
<td width="33%" valign="top">

### `03` ARGUS
<img src="https://img.shields.io/badge/P3-A6051A?style=flat-square&labelColor=0D1117"> <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/ARGUS?style=flat-square&label=&labelColor=0D1117&color=FFF200">

**A Sharpe ratio a language model estimated is not a Sharpe ratio.**

Pure, unit-tested functions compute return, volatility, Sharpe, beta and drawdown. Four rule-based agents interpret them concurrently. A retrieval layer attaches page-level citations.

The model never touches the arithmetic. That's the entire design.

<a href="https://github.com/TheOneAbovELL/ARGUS"><img src="https://img.shields.io/badge/REPO-0D1117?style=flat-square&logo=github&logoColor=FF2800"></a>
<a href="https://personal-portfolio-website-lilac-xi.vercel.app/work/argus"><img src="https://img.shields.io/badge/CASE_STUDY-0D1117?style=flat-square&logo=vercel&logoColor=FFF200"></a>

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2800,50:FFF200,100:FF2800&height=4&section=header" width="100%">

## ⏱ sector splits

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2200&pause=600&color=FF2800&center=true&width=780&height=32&lines=S1+DATA+%E2%96%B8+S2+MODELS+%E2%96%B8+S3+SYSTEMS+%E2%96%B8+S4+DELIVERY;purple+sector+%3D+the+one+I'd+be+hired+for" alt="">

<br>

<img src="https://skillicons.dev/icons?i=cpp,c,python,java,pytorch,sklearn,numpy,pandas&theme=dark&perline=8">

<img src="https://skillicons.dev/icons?i=fastapi,postgres,docker,git,github,linux,nextjs,ts&theme=dark&perline=8">

</div>

```console
┌──────┬────────────────────┬──────────────────────────────────────────────┐
│ SECT │ SPLIT              │ RUNNING                                      │
├──────┼────────────────────┼──────────────────────────────────────────────┤
│  S1  │ DATA               │ SQL · NumPy · Pandas · statistics · features │
│  S2  │ MODELS             │ PyTorch · Transformers · CNN · GCN · LLMs    │
│  S3  │ SYSTEMS   ◀ PURPLE │ LangGraph · Qdrant · RAG · FastAPI · SSE     │
│  S4  │ DELIVERY           │ Docker · CI/CD · Linux · contract + e2e test │
└──────┴────────────────────┴──────────────────────────────────────────────┘
```

<div align="center">

<img src="https://img.shields.io/badge/LangGraph-0D1117?style=for-the-badge&logo=langchain&logoColor=FF2800">
<img src="https://img.shields.io/badge/Qdrant-0D1117?style=for-the-badge&logo=qdrant&logoColor=FFF200">
<img src="https://img.shields.io/badge/BGE--M3-0D1117?style=for-the-badge&logo=huggingface&logoColor=FF2800">
<img src="https://img.shields.io/badge/RAG-0D1117?style=for-the-badge&logo=databricks&logoColor=FFF200">
<img src="https://img.shields.io/badge/Agentic_AI-0D1117?style=for-the-badge&logo=openai&logoColor=FF2800">
<img src="https://img.shields.io/badge/MNE--Python-0D1117?style=for-the-badge&logo=scipy&logoColor=FFF200">

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FFF200,50:FF2800,100:FFF200&height=4&section=header" width="100%">

## 📡 telemetry

<div align="center">

<img height="180" src="https://github-readme-stats.shion.dev/api?username=TheOneAbovELL&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=FF2800&icon_color=FFF200&text_color=C9D1D9&ring_color=FF2800">
<img height="180" src="https://streak-stats.demolab.com/?user=TheOneAbovELL&hide_border=true&background=0D1117&stroke=A6051A&ring=FF2800&fire=FFF200&currStreakLabel=FFF200&sideLabels=C9D1D9&dates=8B949E&sideNums=FFFFFF&currStreakNum=FFFFFF&excludeDaysLabel=8B949E">

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=TheOneAbovELL&bg_color=0D1117&color=FFF200&line=FF2800&point=FFFFFF&area=true&area_color=A6051A&hide_border=true&custom_title=THROTTLE%20TRACE%20%E2%80%94%20COMMITS%2C%20LAST%2031%20DAYS">

<img width="49%" src="https://github-readme-stats.shion.dev/api/top-langs/?username=TheOneAbovELL&layout=compact&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=FF2800&text_color=C9D1D9&langs_count=8">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=TheOneAbovELL&theme=github_dark&utcOffset=5.5">

<img width="98%" src="https://github-profile-trophy.vercel.app/?username=TheOneAbovELL&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=6&margin-h=6">

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2800,50:FFF200,100:FF2800&height=4&section=header" width="100%">

## 🏆 race history

### `> lap times — codeforces`

```mermaid
%%{init: {"theme":"base","themeVariables":{"background":"transparent","xyChart":{"backgroundColor":"transparent","titleColor":"#FF2800","xAxisLabelColor":"#8B949E","xAxisTitleColor":"#FFF200","xAxisTickColor":"#30363D","xAxisLineColor":"#30363D","yAxisLabelColor":"#8B949E","yAxisTitleColor":"#FFF200","yAxisTickColor":"#30363D","yAxisLineColor":"#30363D","plotColorPalette":"#FF2800"}}}%%
xychart-beta
    title "RATING PER RATED CONTEST — C++"
    x-axis [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13]
    y-axis "rating" 1050 --> 1450
    line [1102, 1134, 1187, 1163, 1221, 1258, 1240, 1289, 1312, 1297, 1348, 1379, 1411]
```

<div align="center">

<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3DThe0NEAboveALL&query=%24.result%5B0%5D.rating&label=CURRENT&labelColor=0D1117&color=FF2800&style=for-the-badge&logo=codeforces&logoColor=FFF200&cacheSeconds=3600">
<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3DThe0NEAboveALL&query=%24.result%5B0%5D.maxRating&label=PERSONAL%20BEST&labelColor=0D1117&color=FFF200&style=for-the-badge&cacheSeconds=3600">
<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3DThe0NEAboveALL&query=%24.result%5B0%5D.rank&label=CLASS&labelColor=0D1117&color=A6051A&style=for-the-badge&cacheSeconds=3600">

<br><br>

<img width="46%" src="https://leetcard.jacoblin.cool/TheOneAbovELL?theme=dark&font=JetBrains%20Mono&ext=heatmap">

</div>

### `> season log`

```mermaid
%%{init: {"theme":"base","gitGraph":{"showBranches":true,"mainBranchName":"main"},"themeVariables":{"git0":"#FF2800","git1":"#FFF200","git2":"#A6051A","git3":"#E6EDF3","gitBranchLabel0":"#0D1117","gitBranchLabel1":"#0D1117","gitBranchLabel2":"#FFFFFF","gitBranchLabel3":"#0D1117","commitLabelColor":"#E6EDF3","commitLabelBackground":"#161B22","tagLabelColor":"#0D1117","tagLabelBackground":"#FFF200","fontFamily":"ui-monospace, monospace","fontSize":"12px"}}}%%
gitGraph
   commit id: "BIT Mesra · B.Tech AI-ML"
   branch competitive
   commit id: "Codeforces · Pupil"
   checkout main
   branch data-science
   commit id: "IIT Madras · BS DS"
   checkout main
   merge data-science
   branch research
   commit id: "Legal Lens · retrieval"
   commit id: "eval harness · R@K · MRR · nDCG"
   checkout competitive
   commit id: "Specialist · 1411" tag: "13 contests"
   checkout main
   branch opensource
   commit id: "Nyay Setu · 7 PRs merged"
   commit id: "GSSoC · rank 1065 / 70k+"
   checkout main
   merge opensource
   branch quant
   commit id: "ARGUS · risk engine"
   commit id: "Option pricer · Greeks"
   checkout main
   merge research
   merge quant
   merge competitive
   commit id: "OPEN TO INTERNSHIPS" type: HIGHLIGHT
```

| | |
|:--|:--|
| 🏆 **GSSoC 2026** | Global rank **1,065** of 70,000+ registered · **[7 PRs merged](https://github.com/viru0909-dev/nyay-setu-working/pulls?q=is%3Apr+author%3ATheOneAbovELL+is%3Amerged)** into a production judiciary platform |
| 🔬 **Research** | Undergraduate Research Assistant · Dept. of Computer Science, BIT Mesra · Jan 2026 → present |
| ⚔️ **Codeforces** | Specialist in C++ · the badges above pull live from the Codeforces API |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FFF200,50:FF2800,100:FFF200&height=4&section=header" width="100%">

## 🔧 the paddock

<details>
<summary><b>⚡ 14 repositories in the garage — experiments, tools, hackathon builds</b></summary>

<br>

| Repository | What it is | Last push |
|:--|:--|:--|
| [**SatQuery**](https://github.com/TheOneAbovELL/SATQUERY) | SIH 2026 — natural-language questions over satellite imagery, geospatial tools doing the measuring | <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/SATQUERY?style=flat-square&label=&labelColor=0D1117&color=FF2800"> |
| [**Indian Option Pricer**](https://github.com/TheOneAbovELL/Indian-Option-Pricer) | BSM · Monte Carlo · binomial · Greeks · IV solver · [live](https://indian-option-pricer.vercel.app) | <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/Indian-Option-Pricer?style=flat-square&label=&labelColor=0D1117&color=FFF200"> |
| [**Semantic Rec Engine**](https://github.com/TheOneAbovELL/AMAZON-REC-ENGINE) | Retrieve-then-rank · embeddings · FAISS · multi-signal ranking · [live](https://amazon-rec-engine.vercel.app) | <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/AMAZON-REC-ENGINE?style=flat-square&label=&labelColor=0D1117&color=FF2800"> |
| [**Signal Feed India**](https://github.com/TheOneAbovELL/signal-feed-india) | Async RSS ingestion · de-duplication · clustering · WebSocket updates | <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/signal-feed-india?style=flat-square&label=&labelColor=0D1117&color=FFF200"> |
| [**Quant Portfolio Research**](https://github.com/TheOneAbovELL/quant-portfolio-research-system) | Portfolio construction and risk experiments | <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/quant-portfolio-research-system?style=flat-square&label=&labelColor=0D1117&color=FF2800"> |
| [**Vedyra Labs**](https://github.com/TheOneAbovELL/VEDYRA-LABS) | Vehicle-health-analytics startup site · [live](https://theoneabovell.github.io/VEDYRA-LABS/) | <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/VEDYRA-LABS?style=flat-square&label=&labelColor=0D1117&color=FFF200"> |
| [**Portfolio**](https://github.com/TheOneAbovELL/personal-portfolio-website) | Upstream source of truth for everything above | <img src="https://img.shields.io/github/last-commit/TheOneAbovELL/personal-portfolio-website?style=flat-square&label=&labelColor=0D1117&color=FF2800"> |

</details>

<details>
<summary><b>🔥 off the record — uncited, unverifiable, kept anyway</b></summary>

<br>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=3600&pause=900&color=FFF200&center=true&width=740&height=40&lines=%22Power+comes+in+response+to+a+need%2C+not+a+desire.%22" alt="">
</div>

```console
 claim                                        support
 ─────────────────────────────────────────────────────
 rated contests at 1 a.m. IST                 none
 chess while the compiler thinks              none
 red kalava on the wrist, always              anecdotal
 ultra instinct is a tuned inference loop     disputed
 ─────────────────────────────────────────────────────
 evidence-gate  BYPASS  ·  flagged as uncited
```

Everything above this block cites a source you can open. This block doesn't, and says so —
which is the only honest way to keep it.

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2800,50:FFF200,100:FF2800&height=4&section=header" width="100%">

## 🏁 pit lane open

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2400&pause=700&color=FF2800&center=true&width=860&height=40&lines=Open+to+internships+%E2%80%94+AI%2FML+Engineering;Software+Engineering+%E2%80%A2+Data+Science;Quantitative+Research;Let's+build+something+measurable." alt="">

<br>

<a href="mailto:omjeergiri@gmail.com"><img src="https://img.shields.io/badge/omjeergiri@gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=FF2800"></a>
<a href="https://personal-portfolio-website-lilac-xi.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-0D1117?style=for-the-badge&logo=vercel&logoColor=FFF200"></a>
<a href="https://personal-portfolio-website-lilac-xi.vercel.app/#ask"><img src="https://img.shields.io/badge/ASK_OMJEE_%E2%80%94_IT_CITES_ITS_SOURCES-0D1117?style=for-the-badge&logo=probot&logoColor=FF2800"></a>
<a href="https://personal-portfolio-website-lilac-xi.vercel.app/resume.pdf"><img src="https://img.shields.io/badge/R%C3%89SUM%C3%89-0D1117?style=for-the-badge&logo=readdotcv&logoColor=FFF200"></a>
<a href="https://www.linkedin.com/in/omjee-r-giri/"><img src="https://img.shields.io/badge/LINKEDIN-0D1117?style=for-the-badge&logo=linkedin&logoColor=FF2800"></a>
<a href="https://codeforces.com/profile/The0NEAboveALL"><img src="https://img.shields.io/badge/CODEFORCES-0D1117?style=for-the-badge&logo=codeforces&logoColor=FFF200"></a>
<a href="https://leetcode.com/u/TheOneAbovELL/"><img src="https://img.shields.io/badge/LEETCODE-0D1117?style=for-the-badge&logo=leetcode&logoColor=FF2800"></a>

<br><br>

<sub><code>▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱</code><br>
every claim above resolves to a link you can open · reviewed Oct 2026</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=150&color=0:FF2800,50:A6051A,100:FFF200&section=footer&reversal=true&animation=fadeIn" width="100%">

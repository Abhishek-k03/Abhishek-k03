<!-- Abhishek Kumar · GitHub Profile README -->

<div align="center">

# Abhishek Kumar

**Backend Engineering · Systems · AI**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=660&lines=Python+%7C+C%2B%2B+%7C+FastAPI+%7C+Django;C%2B%2B20+matching+engine+%E2%80%94+2.6M+ops%2Fsec;Storage+engines+%E2%80%94+WAL%2C+mmap%2C+binary+formats;RAG+%7C+Vector+search+%7C+LLM+orchestration;LeetCode+Knight+%E2%80%94+900%2B+problems+solved" alt="Python and C++ · C++20 matching engine · storage engines · RAG systems · LeetCode Knight" />

<br>

<a href="https://www.abhishek-k.me/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/abhishek312/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://codolio.com/profile/Abhicodolio1"><img src="https://img.shields.io/badge/Codolio-6366F1?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codolio" /></a>
<a href="mailto:abhi3122004ak@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

Final-year CS student at **IIIT Sonepat**, working mostly in **Python and C++**.

I build backend and systems software, and I tend to want to understand the layer underneath the one I'm using — which is how I ended up writing a C++20 limit order book that matches at millions of orders per second, and a graph engine with its own binary on-disk format and write-ahead log instead of reaching for a database. I've also shipped [`swagger2drawio`](https://github.com/Abhishek-k03/swagger2drawio) to PyPI, and I compete regularly — **LeetCode Knight**, ~900 problems solved.

## Projects

**[TradeXchange](https://github.com/Abhishek-k03/TradeXchange)** — *a limit order book matching engine with a C++20 core*
Strict price-time priority matching benchmarked at **2.6M limit-order inserts/sec, p50 200 ns / p99 800 ns**. A FastAPI gateway packs orders into 32-byte C-aligned binary structs and pipes them over ZeroMQ, so the engine reads them straight into memory with no deserialization step.
`C++20` · `ZeroMQ` · `FastAPI` · `React` · `Low latency`

**[OffsetGraph](https://github.com/Abhishek-k03/OffsetGraph)** — *a graph engine written from the bytes up*
Fixed-width binary records with stable byte offsets, a write-ahead log with idempotent crash replay, and pointer-based traversal across in-memory, disk-backed, and mmap modes.
`Python` · `mmap` · `WAL` · `Storage internals`

**[Scrybe](https://github.com/Abhishek-k03/Scrybe)** — *a knowledge base that cites its sources*
Point it at URLs or files; it scrapes, chunks, and embeds them into a vector store, then answers through a chat UI grounded with clickable citations.
`FastAPI` · `React` · `ChromaDB` · `Playwright` · `Groq`

**[Taskflow](https://github.com/Abhishek-k03/Taskflow)** — *real-time task scheduling, end to end*
Scheduling and execution service with cron-configured periodic jobs and a dashboard that streams task status and metrics live over WebSockets.
`FastAPI` · `Next.js` · `TypeScript` · `WebSockets`

## Tech Stack

<table>
<tr>
<td align="right" width="130"><sub><b>CORE</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=python,cpp,ts,js&theme=dark" height="38" alt="Python, C++, TypeScript, JavaScript" /></td>
</tr>
<tr>
<td align="right"><sub><b>BACKEND</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=fastapi,django,flask,postgres,mongodb,sqlite&theme=dark" height="38" alt="FastAPI, Django, Flask, PostgreSQL, MongoDB, SQLite" /> <img src="https://img.shields.io/badge/ZeroMQ-DF0000?style=flat-square&logo=zeromq&logoColor=white" height="24" alt="ZeroMQ" /></td>
</tr>
<tr>
<td align="right"><sub><b>AI / ML</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" height="38" alt="PyTorch, TensorFlow, scikit-learn, OpenCV" /> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" height="24" alt="LangChain" /> <img src="https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square&logoColor=white" height="24" alt="ChromaDB" /></td>
</tr>
<tr>
<td align="right"><sub><b>TOOLING</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=git,docker,linux,bash,cmake,react&theme=dark" height="38" alt="Git, Docker, Linux, Bash, CMake, React" /></td>
</tr>
</table>

## Coding Profile

<div align="center">

<a href="https://codolio.com/profile/Abhicodolio1"><img src="./CodoCard.png" height="200" alt="Codolio profile card — LeetCode 1899 (Knight, peak 1949, 42 contests), CodeChef 1608 (3 star, 7 contests), Codeforces 1585 (Specialist, 6 contests). ~900 problems solved across 259 active days and 55 contests." /></a>
<a href="https://codolio.com/profile/Abhicodolio1"><img src="./devCard.png" height="200" alt="Codolio dev card — problem-solving breakdown by topic and difficulty." /></a>

</div>

## GitHub Stats

<div align="center">

<img height="160" src="https://github-stats-extended.vercel.app/api?username=Abhishek-k03&show_icons=true&include_all_commits=true&hide=stars,issues&rank_icon=github&hide_border=true&disable_animations=true&cache_seconds=86400&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9" alt="GitHub stats" />
<img height="160" src="https://github-stats-extended.vercel.app/api/top-langs/?username=Abhishek-k03&layout=compact&langs_count=6&hide=jupyter%20notebook,html,css&exclude_repo=All-ML-models,Brain-Tumor-Detection-using-CNN,Soil_Classification_annam&size_weight=0.5&count_weight=0.5&hide_border=true&disable_animations=true&cache_seconds=86400&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9" alt="Top languages" />
</div>

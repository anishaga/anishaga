<div align="center">

<img src="assets/banner.svg" alt="Anish Agarwal. I find where the time goes. An animated flame graph." width="100%">

<br>

<a href="https://www.linkedin.com/in/anishaga/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://anishaga.github.io"><img src="https://img.shields.io/badge/Portfolio-Live-0F766E?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live portfolio"></a>
<a href="https://leetcode.com/anishaga/"><img src="https://img.shields.io/badge/LeetCode-Knight-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
<a href="mailto:anishaga2001@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

<br><br>

I build and tune **high-throughput Java systems**: I find where time and memory actually go, and remove the cost at the source.

</div>

---

## ⚡ Engineering impact

<div align="center">

<img src="https://img.shields.io/badge/STARTUP_TIME-%7E85%25_LESS-F0603A?style=for-the-badge&labelColor=0F1C26" alt="About 85 percent less startup time">
<img src="https://img.shields.io/badge/HEAP-%7E62%25_LESS-FF8A4C?style=for-the-badge&labelColor=0F1C26" alt="About 62 percent less heap">
<img src="https://img.shields.io/badge/FX_IMPORT-%7E49%C3%97_FASTER-FFB347?style=for-the-badge&labelColor=0F1C26" alt="About 49 times faster FX import">
<img src="https://img.shields.io/badge/CDC_VS_ORACLE-UP_TO_%7E3%2C000%C3%97-FFD66B?style=for-the-badge&labelColor=0F1C26" alt="Up to about 3,000 times faster than Oracle on the slowest queries">

</div>

Production Java services where startup time, memory, concurrency and failure recovery decide whether things hold up.

- Cut startup time of a core position-valuation service by **~85%**: updates are persisted with a high-watermark transaction ID, so a restart loads only newer trades.
- Cut a service's heap by **~62%** (26 GB to 10 GB) with a compact per-firm store, a leaner cache index and String deduplication.
- Fixed a consumer-thread deadlock and an O(n²) hot-key merge behind a 1.5-week P1, taking 20,000 merges from **~4 s to ~2–3 ms**.
- Sped up an FX rate import **~49×** (37 min to ~45 s) by filtering invalid records before a lock-bound stage.
- Root-caused a JVM at **200+ GB** when the real need was ~15–20 GB, from heap dumps and logs. The hotfix shipped the next day.
- Built an Oracle-to-ClickHouse CDC pipeline in an internal hackathon, up to **~3,000×** faster than Oracle on the slowest queries.

---

## 🔭 Current focus

### WhatsApp-style chat server · pure Java, WebSockets and Kafka

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/WebSockets-4B5563?style=flat-square" alt="WebSockets">
  <img src="https://img.shields.io/badge/Kafka_KRaft-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka in KRaft mode">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose">
  <img src="https://img.shields.io/badge/Status-In_progress-2563EB?style=flat-square" alt="In progress">
</p>

A real-time chat server built from scratch in pure Java, with WebSocket messaging and plain-JDBC persistence in PostgreSQL. Next up: multi-server message routing over Kafka.

---

## 🧩 Selected work

| Project / system | Focus |
|---|---|
| **WhatsApp-style chat server** | Pure Java · WebSockets · plain JDBC on PostgreSQL · multi-server routing over Kafka (in progress) |
| **Startup-time redesign** | Last-write-wins persistence · high-watermark transaction ID · restarts load only newer trades |
| **Heap diet** | Compact per-firm store · ArrayListMultimap · String deduplication · 26 GB → 10 GB |
| **P1 throttler fixes** | Consumer-thread deadlock · O(n²) hot-key merge · immutable, structurally shared version chain |
| **Oracle → ClickHouse CDC** | Debezium on Kafka Connect · Kafka fills replication lag via a max-transaction-ID marker · hackathon |
| **Agentic test generation** | Claude Agent SDK · writer, reviewer and patch agents behind execution gates · challenger subagent · Playwright |

---

## 🏆 Beyond work

| | | |
|---|---|---|
| 🥇 | **LeetCode Knight** | Top 5% globally · 800+ problems · 1850+ contest rating |
| 🚀 | **GeeksforGeeks Job-A-Thon (Amazon Alexa Challenge)** | Ranked 161 of 18,000+ |
| 🏅 | **Virtusa Neural Hack, Season 6** | Grand finalist · top 100 of 7,000+ |
| 🎓 | **Mentor** | 70+ students in data structures and algorithms |

---

## 🛠️ Stack

### Systems & backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Data & infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### Performance & tooling

![JFR](https://img.shields.io/badge/JFR-Flight_Recorder-0F1C26?style=for-the-badge)
![JProfiler](https://img.shields.io/badge/JProfiler-profiling-0F1C26?style=for-the-badge)
![Heap dumps](https://img.shields.io/badge/Heap_dumps-analysis-0F1C26?style=for-the-badge)
![G1GC](https://img.shields.io/badge/G1GC-tuning-0F1C26?style=for-the-badge)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Claude Agent SDK](https://img.shields.io/badge/Claude_Agent_SDK-D97757?style=for-the-badge&logo=claude&logoColor=white)

---

## 🧠 Problems I like working on

<div align="center">
  <img width="100%" src="./assets/interests.svg" alt="Where the time goes, memory and GC, concurrency, data pipelines, and production incidents">
</div>

I like the problems where the profiler disagrees with my first guess.

---

<div align="center">
  <img width="100%" src="./assets/footer.svg" alt="">
</div>

```
┌──(vinit㉿londhe)-[~]
└─$ whoami
```

```
vinit londhe · data engineer
london, uk · queen mary university of london
graduating sept 2026 · open to data engineering roles
```

```
┌──(vinit㉿londhe)-[~]
└─$ cat ./about.md
```

I'm finishing an MSc in Data Science at Queen Mary, with my own work pulled hard
toward the data engineering side of the field — distributed pipelines, event streams,
lakehouse architectures, and the infrastructure that makes analytics and AI actually
work in production.

What I'm drawn to is the unglamorous stuff: schema drift in event streams,
late-arriving data in batch jobs, the wide gap between a model that works in a
notebook and one that runs reliably at 3am on a Tuesday. The plumbing.

```
┌──(vinit㉿londhe)-[~]
└─$ ls ~/stack/
```

```
core/                   python   sql   java   bash
data-engines/           apache-spark   pyspark   structured-streaming   kafka
backend/                flask   rest-api   sqlalchemy
infra/                  aws   gcp   docker   linux   git
data-tooling/           lakehouse-bronze-silver-gold   pgvector   langchain
databases/              postgresql   mysql   sqlite
```

```
┌──(vinit㉿londhe)-[~]
└─$ cat ~/learning/in_progress.log
```

```log
[2026-06-01 09:00] ▶ STARTED   aws-saa-c03           target: end of july
[2026-06-15 14:30] ▶ STARTED   apache-airflow        building DAGs into dissertation
[2026-07-15 10:00] ▶ QUEUED    dbt-fundamentals      transformation layer
[2026-08-01 09:00] ▶ QUEUED    aws-data-engineer     target: end of august
```

> I'd rather log what I'm learning than pretend I already know it.

```
┌──(vinit㉿londhe)-[~/projects]
└─$ ls -la
```

```
drwxr-xr-x   financial-data-platform/      [primary]   python · kafka · pyspark · langchain
drwxr-xr-x   game-event-analytics/         [active]    spark-streaming · kafka · sql
drwxr-xr-x   msc-dissertation/             [building]  pyspark · airflow · dbt · aws
```

---

```
┌──(vinit㉿londhe)-[~/projects/financial-data-platform]
└─$ cat README.md | head -20
```

### Cloud-native financial data platform

An end-to-end transaction analytics platform with a RAG layer over the processed data.

```text
┌─────────────┐    ┌─────────────┐    ┌──────────────┐    ┌──────────────┐
│   ingest    │───▶│   stream    │───▶│   transform  │───▶│    serve     │
│   (Kafka)   │    │  (PySpark)  │    │  (lakehouse) │    │   (RAG/LLM)  │
└─────────────┘    └─────────────┘    └──────────────┘    └──────────────┘
                                              │
                                              ▼
                                     ┌──────────────────┐
                                     │  bronze / silver │
                                     │      / gold      │
                                     └──────────────────┘
```

- Real-time ingestion through Kafka, distributed PySpark ETL on top
- 15+ data quality validation rules across the bronze/silver/gold flow
- RAG-based natural-language interface over millions of processed records

→ [`Vinit-Londhe/financial-data-platform`](https://github.com/Vinit-Londhe)

---

```
┌──(vinit㉿londhe)-[~/projects/game-event-analytics]
└─$ cat README.md | head -20
```

### Multiplayer game event analytics

Real-time analytics for simulated FPS gameplay events. Designed as the kind of
streaming platform a game studio would actually run — modular, reproducible,
documented.

- Five event types ingested in parallel through Kafka
- Spark Structured Streaming for real-time processing
- Batch ETL computes K/D ratios, weapon usage, match-level statistics
- Modular architecture with reproducible pipelines on GitHub

→ [`Vinit-Londhe/game-event-analytics`](https://github.com/Vinit-Londhe)

---

```
┌──(vinit㉿londhe)-[~/projects/msc-dissertation]
└─$ cat README.md | head -10
```

### MSc dissertation · in progress

```
[ status      ] building — Jun → Sep 2026
[ stack       ] pyspark · airflow · dbt · aws · lakehouse
[ scope       ] end-to-end DE: orchestration, transformation, serving
[ visibility  ] repo opens to public on submission
```

My capstone — the first piece of work I'll have shipped that's production-shaped.

→ Repo opens September 2026.

---

```
┌──(vinit㉿londhe)-[~]
└─$ cat ~/work-history.log
```

```log
2024-03  ─ 2024-06   Data Engineering Intern · early-stage analytics startup (remote)
                       · automated ETL pipelines, 500K+ records per run
                       · python data processing, 40% reduction in manual prep
                       · 10+ data validation checks across the flow
                       · batch workloads on AWS infrastructure

2023-03  ─ 2023-09   Software Engineer Intern · Corestance Technology (Pune)
                       · backend services and REST APIs · 1K+ daily requests
                       · SQL optimisation across 5+ tables · 35% query improvement
                       · resolved 15+ production bugs through log analysis
                       · API validation across 20+ endpoints
```

```
┌──(vinit㉿londhe)-[~]
└─$ ./principles.sh
```

```
[1] depth over breadth — get genuinely good at the few tools that run modern DE
[2] build in the open — half-finished things shipped beat polished things imagined
[3] log what you don't know — claimed skills are debt; honest gaps are credibility
[4] the pipeline is the product — if it breaks the business breaks
[5] write more — the engineers I respect most can also explain things
```

```
┌──(vinit㉿londhe)-[~]
└─$ cat ~/looking-for.txt
```

```
role          junior data engineer · graduate scheme · 6–12 month placement
location      london, uk · open to hybrid and remote
start         september 2026
visa          uk graduate visa (psw) eligible — sponsorship path welcome after
interested    teams where data infrastructure is genuinely valued
              — analytics platforms, ml systems, real-time products
not for       roles requiring fabricated experience or 3+ years on a "junior" jd
```

```
┌──(vinit㉿londhe)-[~]
└─$ ./contact.sh
```

```
linkedin    →  linkedin.com/in/vinit-londhe613
email       →  vinit.londhe.ds@gmail.com
writing     →  medium.com/@vinit.londhe.ds  (publishing from summer 2026)
location    →  london, uk
```

```
┌──(vinit㉿londhe)-[~]
└─$ exit

logout
Connection to vinit.londhe closed.
```

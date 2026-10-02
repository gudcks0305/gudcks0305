<div align="center">

# Chan / yuhyeongchan

**Backend Engineer · Java / Spring · AI Runtime · Cloud & Distributed Systems**

Building reliable backend services and practical tools, from AI evaluation pipelines to native macOS utilities.

</div>

<details>
<summary>▶ Explore an AI evaluation workflow</summary>

![Animated diagram of an AI evaluation pipeline from request through durable queue and AI runtime to result](assets/ai-evaluation-pipeline.gif)

</details>

## Selected Impact

| **50K messages** | **~40 / sec** | **10s → 1s** |
| --- | --- | --- |
| Queue preparation reduced from 2 hours to 1 minute | Email delivery throughput with Amazon SES | Java Lambda cold start with SnapStart |

## What I Build

- Backend systems for AI interviews and evaluations, including LLM pipelines, durable job processing, and multi-tenant data workflows.
- Event-driven services and cloud operations across AWS, Kubernetes, Kafka, and GitOps delivery.
- AI applications with Spring AI, LangChain4j, OpenAI models, and speech-to-text / text-to-speech.
- Local-first desktop tools, browser utilities, and native macOS integrations.
- Open-source fixes and systems work in Rust, process memory access, and macOS tooling.

## Open Source Contributions

**8 merged upstream PRs across 7 open-source projects**, verified on October 2, 2026. Merge dates below use Korea Standard Time (UTC+9).

| Project | Contribution | Merged (KST) | Upstream PR |
| --- | --- | --- | --- |
| [JSqlParser](https://github.com/JSQLParser/JSqlParser) | Preserved individually quoted parts of qualified column names, including quoted dots and escaped delimiters, while retaining BigQuery namespace behavior. | 2026-10-01 | [#2735](https://github.com/JSQLParser/JSqlParser/pull/2735) |
| [bot-signal](https://github.com/okasi/bot-signal) | Corrected closed pointer paths being classified as linear movement without changing scoring weights or thresholds. | 2026-10-01 | [#10](https://github.com/okasi/bot-signal/pull/10) |
| [VHS](https://github.com/charmbracelet/vhs) | Fixed missing GIF output after recording and propagated encoder errors to callers. Released in [v0.12.1](https://github.com/charmbracelet/vhs/releases/tag/v0.12.1). | 2026-09-24 | [#788](https://github.com/charmbracelet/vhs/pull/788) |
| [FileBrowser](https://github.com/gtsteffaniak/filebrowser) | Prevented active parallel uploads from being interrupted by per-file inactivity timeouts. Released in [v2.0.7-beta](https://github.com/gtsteffaniak/filebrowser/releases/tag/v2.0.7-beta). | 2026-09-13 | [#2950](https://github.com/gtsteffaniak/filebrowser/pull/2950) |
| [chzzk-plus](https://github.com/kyechan99/chzzk-plus) | Restored hover previews after wide-screen mode replaces the sidebar, preserving preview pinning and cleanup behavior. | 2026-09-12 | [#107](https://github.com/kyechan99/chzzk-plus/pull/107) |
| [CXX](https://github.com/dtolnay/cxx) | Allowed `cxx-build` to complete when the optional shared-header directory is unwritable, while preserving required local-header errors. Released in [1.0.202](https://github.com/dtolnay/cxx/releases/tag/1.0.202). | 2026-09-12 | [#1760](https://github.com/dtolnay/cxx/pull/1760) |
| [Wuma Tracker](https://github.com/wuwamoe/wuma-tracker) | Corrected macOS CI configuration for universal DMG builds with ad-hoc signing and disabled updater artifacts for that job. | 2026-06-06 | [#7](https://github.com/wuwamoe/wuma-tracker/pull/7) |
| [Wuma Tracker](https://github.com/wuwamoe/wuma-tracker) | Added native macOS tracking through Mach process-memory APIs and a shared Windows/macOS process abstraction. | 2026-06-01 | [#6](https://github.com/wuwamoe/wuma-tracker/pull/6) |

## Tech Stack

<details>
<summary>Explore technologies by category</summary>

<h3>Backend &amp; APIs</h3>

![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat&logo=spring&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

<h3>AI Runtime</h3>

![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat&logo=spring&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-1C3C3C?style=flat)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![STT / TTS](https://img.shields.io/badge/STT_/_TTS-555555?style=flat)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat)

<h3>Data &amp; Messaging</h3>

![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)

<h3>Cloud &amp; Delivery</h3>

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat&logo=amazoneks&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat&logo=amazoncloudwatch&logoColor=white)

<h3>Systems &amp; Open Source</h3>

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![macOS Mach API](https://img.shields.io/badge/macOS_Mach_API-000000?style=flat&logo=apple&logoColor=white)
![Mach--O](https://img.shields.io/badge/Mach--O-555555?style=flat)

</details>

## Links

- GitHub: [github.com/gudcks0305](https://github.com/gudcks0305)
- Blog: [velog.io/@gudcks0305](https://velog.io/@gudcks0305)

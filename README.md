<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F5AF0,50:2CB1BC,100:F25F4C&height=210&section=header&text=Shashank%20Ramireddy&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Computer%20Engineering%20%40%20Georgia%20Tech&descSize=18&descAlignY=57&animation=fadeIn" alt="Shashank Ramireddy, Computer Engineering at Georgia Tech" width="100%"/>
</p>

<p align="center">
  <a href="https://sramireddy2.github.io">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=7F5AF0&center=true&vCenter=true&width=640&lines=Reinforcement+learning+research+%40+GT+PAIR+Lab;ML+infrastructure+on+Kubernetes+and+Ray;Distributed%2C+real-time+data+systems;Backends+with+queues%2C+caches+and+tests" alt="Reinforcement learning, ML infrastructure, distributed systems, backend engineering"/>
  </a>
</p>

<p align="center">
  <a href="https://sramireddy2.github.io"><img src="https://img.shields.io/badge/Website-sramireddy2.github.io-7F5AF0?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="https://www.linkedin.com/in/shashankramireddy/"><img src="https://img.shields.io/badge/in-LinkedIn-0A66C2?style=for-the-badge&labelColor=0A66C2" alt="LinkedIn"/></a>
  <a href="mailto:sramireddy7@gatech.edu"><img src="https://img.shields.io/badge/Email-sramireddy7%40gatech.edu-F25F4C?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

## 👋 Hi, I'm Shashank

I'm a Computer Engineering student at Georgia Tech. I like the systems underneath machine learning: the clusters, queues and schedulers that let models train, scale and serve.

- 🔬 **Now:** Student Researcher at Georgia Tech's PAIR Lab, working on reinforcement learning
- 🌱 **Open source:** contributing to [KubeRay](https://github.com/kuberay-project/kuberay), the operator that runs Ray on Kubernetes
- 🏆 **IMC Prosperity 4:** 78th overall and 25th in the US (top 0.26%)
- 🎓 **B.S. Computer Engineering**, Georgia Tech · GPA 3.92 / 4.0

## 🎯 What I work on

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 Reinforcement Learning</h3>
      Research at GT's PAIR Lab on how agents learn from interaction, plus the compute and tooling it takes to run those experiments at scale.
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ ML Infrastructure</h3>
      Kubernetes operators for distributed ML (<a href="https://github.com/kuberay-project/kuberay/pull/5448">KubeRay</a>), and AI agents that change infrastructure only through typed tools and verified fixes (<a href="https://github.com/sramireddy2/NetTwin">NetTwin</a>).
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 Distributed Systems</h3>
      Partitioned streams, ordering and windowed processing with Kafka and Spark (<a href="https://github.com/sramireddy2/marta-headway">Headway</a>), and workers that autoscale on queue depth (<a href="https://github.com/sramireddy2/cellengine">cellengine</a>).
    </td>
    <td width="50%" valign="top">
      <h3>🧱 Backend Engineering</h3>
      REST and WebSocket APIs, Postgres, Redis, job queues and typed tool servers, shipped with Docker, CI and real test suites.
    </td>
  </tr>
</table>

## 💼 Experience

| | Role | Where | When |
|:-:|:--|:--|:--|
| <img src="https://sramireddy2.github.io/logos/gatech.png" height="20" alt="Georgia Tech"/> | **Student Researcher** | Georgia Tech · PAIR Lab | Aug 2026 – now |
| <img src="https://sramireddy2.github.io/logos/deloitte.svg" height="20" alt="Deloitte"/> | **Software Engineering Intern** | Deloitte | Jun – Jul 2026 |
| <img src="https://sramireddy2.github.io/logos/gatech.png" height="20" alt="Georgia Tech"/> | **Student Researcher** | Georgia Tech · CCG / Animal Lab | Jul 2025 – May 2026 |
| <img src="https://sramireddy2.github.io/logos/hireko.png" height="20" alt="Hireko.ai"/> | **Software Engineering Intern** | Hireko.ai | Sep – Dec 2025 |
| <img src="https://sramireddy2.github.io/logos/argonne.svg" height="20" alt="Argonne National Laboratory"/> | **Data Science Intern** | Argonne National Laboratory · Ramanathan Lab | Aug 2024 – May 2025 |

## 🚀 Projects

<img src="https://img.shields.io/badge/ML_Infrastructure_%26_AI_Systems-7F5AF0?style=for-the-badge&logo=kubernetes&logoColor=white" alt="ML Infrastructure and AI Systems"/>

| Project | What it does | Built with |
|:--|:--|:--|
| ☸️ **[KubeRay](https://github.com/kuberay-project/kuberay/pull/5448)**<br/><sub>open-source PR</sub> | Fixed the RayCluster GCS fault-tolerance cleanup Job inheriting the head Pod's anti-affinity. GKE Autopilot rejected the Job, which leaked the Redis namespace and stalled cluster deletion. | Go · Kubernetes · Ray |
| 🕸️ **[NetTwin](https://github.com/sramireddy2/NetTwin)** | A team of AI agents troubleshoots a containerized digital twin of a network (FRR routers running OSPF and BGP, VLANs, nftables). Agents act only through two typed MCP servers, and an independent verifier checks every fix before a person approves it. Benchmarked on 22 planted faults. | Python · MCP · containerlab · Docker |

<img src="https://img.shields.io/badge/Distributed_Systems_%26_Backend-2CB1BC?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Distributed Systems and Backend"/>

| Project | What it does | Built with |
|:--|:--|:--|
| 🚌 **[Headway](https://github.com/sramireddy2/marta-headway)** | Detects bus bunching in Atlanta in real time. Streams MARTA's GTFS-Realtime feed for ~175 buses into Kafka (partitioned by route to keep each line in order), measures gaps in Spark, and pushes a live map over WebSockets once a second. 202 tests plus JMH concurrency benchmarks. | Java 21 · Kafka · Spark · Spring Boot · Docker |
| 🧬 **[cellengine](https://github.com/sramireddy2/cellengine)** | Interactive single-cell RNA-seq clustering service. Django REST API, Postgres, a Redis job queue and S3 storage, with workers autoscaled on queue depth by KEDA on Kubernetes. Caching the expensive graph makes re-clustering take **~1 s instead of ~6 s**. | Django · PostgreSQL · Redis · Kubernetes |
| 🐾 **[Animal Welfare Tracker](https://github.com/sramireddy2/animalwelfare)** | Pipeline that scrapes news RSS feeds, scores sentiment with VADER and TextBlob, stores daily rollups in SQLite, and serves a Flask + Plotly dashboard with CSV export. | Python · Flask · SQLite |

<img src="https://img.shields.io/badge/Performance_%26_Algorithms-F25F4C?style=for-the-badge&logo=rust&logoColor=white" alt="Performance and Algorithms"/>

| Project | What it does | Built with |
|:--|:--|:--|
| 🟩 **[Wordle Solver](https://github.com/sramireddy2/rustwordlesolver)** | Entropy-driven solver with an exact branch-and-bound endgame. Solves all 2,315 answers in six guesses or fewer, averaging **3.46**, and benchmarks every answer in 2–3 s. | Rust |
| 🎵 **[fifths](https://github.com/sramireddy2/fifths)** | Real-time instrument tuner. YIN pitch detection is fed by a lock-free single-producer ring buffer, so the audio thread never takes a lock. | C++20 · CMake · miniaudio |

<img src="https://img.shields.io/badge/Apps%2C_Games_%26_Hackathons-FFB703?style=for-the-badge&logo=unity&logoColor=white" alt="Apps, Games and Hackathons"/>

| Project | What it does | Built with |
|:--|:--|:--|
| 🧸 **[Tinker's Toybox](https://github.com/sramireddy2/tinkerstoybox)**<br/><sub>[▶ play it](https://sramireddy2.github.io/tinkerstoybox/)</sub> | Perspective puzzle game: toys keep their on-screen size, so drop one far away and it lands huge. 15 levels, PhysX, 2,100+ tests, 60 fps in the browser. | Unity · C# · WebGL |
| 👁️ **[RetinAI](https://devpost.com/software/retinai-bfdi2u)** | Chrome extension that adapts any webpage to an accessibility profile, with Gemini on the DOM, ElevenLabs spoken summaries and Snowflake analytics. | Node.js · Firebase · Gemini |
| 🏥 **[LifeLine](https://github.com/sramireddy2/LifeLine)** | Computer-vision monitor for ICU patients: face, emotion and head-pose tracking with movement alerts and a live dashboard, to help nurses respond faster. | Python · MediaPipe · DeepFace |
| 📈 **[Crypto Tracker](https://github.com/sramireddy2/vue-crypto-tracker)**<br/><sub>[live site](https://sramireddy2.github.io/vue-crypto-tracker/)</sub> | Live market dashboard for 250 coins, with Binance WebSocket prices and 7-day sparklines. | Vue 3 · Pinia · Tailwind |

## 🛠️ Tech Stack

<p align="center"><b>Languages</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=python,java,cpp,c,rust,go,ts,js,cs&theme=dark" alt="Python, Java, C++, C, Rust, Go, TypeScript, JavaScript, C#"/>
</p>

<p align="center"><b>ML & Data</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark" alt="PyTorch, scikit-learn"/>
  <br/>
  <img src="https://img.shields.io/badge/Ray-028CF0?style=for-the-badge&logo=ray&logoColor=white" alt="Ray"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark"/>
</p>

<p align="center"><b>Infrastructure & Backend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,kafka,linux,githubactions&theme=dark" alt="Docker, Kubernetes, AWS, Kafka, Linux, GitHub Actions"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=spring,django,flask,nodejs,postgres,redis&theme=dark" alt="Spring, Django, Flask, Node.js, PostgreSQL, Redis"/>
</p>

<p align="center"><b>Frontend & Games</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=react,vue,tailwind,unity&theme=dark" alt="React, Vue, Tailwind, Unity"/>
</p>

## 🐍 Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sramireddy2/sramireddy2/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sramireddy2/sramireddy2/output/github-snake.svg"/>
    <img alt="A snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/sramireddy2/sramireddy2/output/github-snake.svg"/>
  </picture>
</p>

<p align="center">
  <b>Let's talk about RL, ML infra, distributed systems or backend roles.</b><br/>
  <a href="mailto:sramireddy7@gatech.edu"><code>sramireddy7@gatech.edu</code></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F25F4C,50:2CB1BC,100:7F5AF0&height=120&section=footer" alt="" width="100%"/>
</p>

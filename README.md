<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF7A3D,100:3DD6C4&height=190&section=header&text=Sujit%20Wagh&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Data%20%26%20AI%20Engineer%20%C2%B7%20Kalyani%20Group&descSize=18&descAlignY=58" alt="Sujit Wagh" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=900&color=FF7A3D&center=true&vCenter=true&width=640&lines=I+build+self-hosted+data+platforms.;NiFi+%E2%86%92+PostgreSQL+%E2%86%92+Superset%2C+all+in+Docker.;Then+I+teach+them+to+answer+in+plain+English." alt="I build self-hosted data platforms" />
</p>

<p align="center">
  <a href="https://sujitdevport.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-FF7A3D?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/sujitwagh9"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/IamSujitWagh"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:sujitwagh1233@gmail.com"><img src="https://img.shields.io/badge/Email-3DD6C4?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://leetcode.com/u/sujitwagh9/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
</p>

<p align="center">
  Data & AI Engineer on the Data Platform team at the <b>Kalyani Group</b>, Pune.<br/>
  I joined as an AI/ML intern, took the group's data platform from research to production,<br/>
  and now run it full time. B.Tech IT, VIT Pune (CGPA 8.68).
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,java,js,ts,postgres,mysql,mongodb,redis,docker,nginx,grafana,prometheus,linux,azure,react,nextjs,nodejs,flask,git&perline=10" alt="Python, C++, Java, JavaScript, TypeScript, PostgreSQL, MySQL, MongoDB, Redis, Docker, Nginx, Grafana, Prometheus, Linux, Azure, React, Next.js, Node.js, Flask, Git" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Apache%20NiFi-728E9B?style=flat-square&logo=apachenifi&logoColor=white" alt="Apache NiFi" />
  <img src="https://img.shields.io/badge/Apache%20Superset-20A6C9?style=flat-square&logo=apachesuperset&logoColor=white" alt="Apache Superset" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/LLM%20agents-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="LLM agents" />
  <img src="https://img.shields.io/badge/MCP-111111?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
</p>

<p align="center">
  <a href="https://leetcode.com/u/sujitwagh9/"><img src="https://leetcard.jacoblin.cool/sujitwagh9?theme=dark&font=JetBrains%20Mono&ext=contest&border=0&radius=12" alt="LeetCode: problems solved and contest rating" /></a>
</p>

<details>
<summary><b>The platform I built</b> &nbsp;·&nbsp; click to expand</summary>
<br/>

Live in **5 production environments** across the group, replacing paid SaaS tools.

```mermaid
flowchart LR
  SRC[(Source systems)] --> NIFI

  subgraph PLATFORM [Data Platform on Docker]
    direction LR
    NIFI[Apache NiFi<br/>ingest + transform] --> PG[(PostgreSQL)] --> SUP[Apache Superset<br/>dashboards]
    PGA[pgAgent<br/>custom image] -. schedules .-> PG
  end

  SUP --> TEAMS([Business teams])
  PG -. in progress .-> P2D[Prompt to Dashboard<br/>LLM agent] -.-> TEAMS
  MON[Grafana + Prometheus] -. monitors .-> PLATFORM
  SEC[Nginx TLS + Azure AD SSO] -. secures .-> PLATFORM

  classDef core fill:#FF7A3D,stroke:#FF7A3D,color:#0B0D10
  classDef ops fill:#3DD6C4,stroke:#3DD6C4,color:#0B0D10
  class NIFI,PG,SUP core
  class MON,SEC,PGA ops
```

| | |
|---|---|
| **1.4 TB → 18 GB** | Archived IoT production data for a team that was running out of storage |
| **pgAgent in Docker** | Built the image myself; no official one existed |
| **Azure AD SSO** | OAuth 2.0 / OIDC sign-in for Superset, with users mapped to Superset roles |
| **Config Manager** | Generates each deployment's configuration from a few inputs |
| **Encrypted Compose** | A unique key per deployment, kept out of shell history |

</details>

<details>
<summary><b>Projects</b> &nbsp;·&nbsp; click to expand</summary>
<br/>

| Project | What it does | Stack |
|---|---|---|
| [**myportfolio**](https://github.com/sujitwagh9/myportfolio) | Portfolio with an AI assistant, job-fit analyzer and semantic search | Next.js, TypeScript, Gemini |
| [**Pneumonia Detection**](https://github.com/sujitwagh9/Pneumonia-Detection-and-Report-Generation) | Detects pneumonia from chest X-rays and writes a report, with heatmaps | Python, CNN, Flask |
| **Dark Store Network** | Plans dark-store placement with demand clustering and Voronoi maps | Next.js, Flask, MongoDB |
| [**CampusFound**](https://github.com/sujitwagh9/CampusFound) | Report, track and claim lost and found items on campus | JavaScript, Node.js |
| [**Anomaly Detector**](https://github.com/sujitwagh9/anamoly-detector) | Finds anomalies in time-series data | Python, ML |
| [**KrishiSetu**](https://github.com/sujitwagh9/KrishiSetu) | Connects farmers directly to the market | JavaScript |

</details>

<details>
<summary><b>Achievements</b> &nbsp;·&nbsp; click to expand</summary>
<br/>

| | |
|---|---|
| **Hackron'25** (Blinkit) | 2nd Runner-Up · ₹10,000 · Dark Store Network Projection System |
| **Vodafone Idea Tech Marathon** | Winner · ₹25,000 · threat-analysis dashboard built in 90 minutes |
| **Kalyani Group Hackathon** | Winner · one of the top 7 applicants selected for an internship |
| **LeetCode Weekly Contest 428** | Global rank 737 out of 24K+ |
| **Ratings** | LeetCode 1550 · GeeksforGeeks 3★ · CodeChef 2★ |

</details>

<details>
<summary><b>Timeline</b> &nbsp;·&nbsp; click to expand</summary>
<br/>

```mermaid
timeline
  2022 : Started B.Tech IT at VIT Pune
  2025 : Mar - 2nd Runner-Up at Hackron'25
       : Jul - AI/ML Intern at Kalyani Group
       : Data platform V1 goes live
  2026 : Jun - Graduated, CGPA 8.68
       : Jul - Data & AI Engineer at Kalyani Group
```

</details>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3DD6C4,100:FF7A3D&height=100&section=footer" alt="" />
</p>

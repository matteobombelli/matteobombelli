<h1 align="center">Hey, I'm Matteo</h1>

<p align="center">
  Computing Science student at SFU and Technical Analyst Intern at LineZero.<br/>
  I build backends and full-stack apps, and I enjoy the systems work that sits underneath them.
</p>

<p align="center">
  <a href="https://matteob.dev"><img src="https://img.shields.io/badge/Website-matteob.dev-1d4ed8?style=for-the-badge&logo=firefox&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/matteo-bombelli/"><img src="https://img.shields.io/badge/LinkedIn-matteo--bombelli-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:matteo.bombelli@gmail.com"><img src="https://img.shields.io/badge/Email-matteo.bombelli-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="./resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-374151?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume" /></a>
</p>

<p align="center"><b>Open to software engineering internships and 2027 new-grad roles.</b></p>

---

### About me

I'm in my B.A.Sc. in Computing Science at Simon Fraser University, graduating in April 2027. Most of what I build is backend or full-stack, but the part I like most is a layer down: getting a transport protocol to recover from dropped packets, or working out why a cache turns a slow endpoint fast.

Right now I'm a Technical Analyst Intern at LineZero, where I build retrieval-augmented chatbots and internal tooling, ship integrations, and review my teammates' pull requests. On the side I write backends, the occasional network protocol, and small machine learning projects, usually to understand how something works a level below where I'd normally stop.

### What I've been building

**🎵 WebTunes** &nbsp;·&nbsp; `Next.js` `TypeScript` `PostgreSQL` `AWS S3`
A self-hosted web music app. Each user uploads their own library to S3 and streams it in the browser through presigned URLs with HTTP range requests, so the server never proxies audio. Added full-text search (tsvector + GIN index) over title, artist, album, and lyrics, plus friend-based library sharing.

**🔗 URL Shortener & Analytics API** &nbsp;·&nbsp; `Spring Boot` `Java` `PostgreSQL` `Redis` `Nginx`
A REST shortening service using Base62 encoding for collision-resistant links, backed by Spring Data JPA and PostgreSQL. Hot URLs are cached in Redis to cut read latency, with documented REST contracts for reuse.

**📡 Pipelined Reliable Transfer Protocol (PRTP)** &nbsp;·&nbsp; `Python` `Wireshark`
A reliable transport protocol built over UDP with a three-way handshake, congestion and flow control, and pipelining driven by custom headers. Validated with Wireshark traces and a packet-loss fuzzer against a non-blocking-socket server.

**🃏 [Blackjack vs Agent](https://matteobombelli.github.io/blackjack-vs-ai)** &nbsp;·&nbsp; `R` `React` `TypeScript`
A reinforcement-learning Blackjack agent trained with a Monte Carlo simulation in R, improving win rate 15.3% over random play and converging to optimal basic strategy. Wrapped in an interactive React site with animations and sound so you can play against it.

> More projects live on [matteob.dev](https://matteob.dev).

### Tech I work with

**Languages**
&nbsp;
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599c?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276dc3?style=flat-square&logo=r&logoColor=white)

**Frameworks & Technologies**
&nbsp;
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61dafb)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6db33f?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-dc382d?style=flat-square&logo=redis&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white)

**Cloud & Tools**
&nbsp;
![AWS](https://img.shields.io/badge/AWS-232f3e?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078d4?style=flat-square&logo=microsoftazure&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-f05032?style=flat-square&logo=git&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

<p align="center">
  Want to chat? Find me at <a href="https://matteob.dev">matteob.dev</a> or <a href="https://www.linkedin.com/in/matteo-bombelli/">LinkedIn</a>, or grab my <a href="./resume.pdf">resume</a>.
</p>

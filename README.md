# Mani Mokshith Noonety

**Software Engineer | Systems Architect | San Jose, CA**

I build things that work at every layer of the stack -- from transistor-level CPU emulators to cloud-native distributed systems. My work sits at the intersection of systems programming, full-stack engineering, and applied AI.

Currently pursuing graduate studies at **San Jose State University** (Computer Engineering), where I focus on enterprise distributed systems, computer architecture, and scalable software design.

---

## Technical Toolkit

**Systems & Low-Level:** C, C++, x86/Custom ISA, CPU Microarchitecture, Memory-Mapped I/O

**Backend & Distributed Systems:** Java 17, Spring Boot, Python, Flask, REST APIs, Microservices, PostgreSQL, Redis, gRPC

**Frontend:** React 18, Redux Toolkit, Material-UI, Vite, JavaScript/TypeScript, HTML/CSS

**Cloud & Infrastructure:** AWS (Lambda, DynamoDB, S3, API Gateway), Serverless Architecture, Docker

**AI & Data:** Retrieval-Augmented Generation (RAG), Google Gemini API, Jupyter, Pandas, Scikit-learn

---

## Featured Projects

### [RAG System](https://github.com/mokshith245/RAG-system) &mdash; Python
A **Retrieval-Augmented Generation** pipeline that answers natural language questions grounded in document context. Combines vector-based document retrieval with large language model inference to produce accurate, source-backed responses -- reducing hallucination through context injection.

### [CPU Emulator](https://github.com/mokshith245/CPU) &mdash; C++
A fully functional **16-bit CPU emulator** built from scratch, featuring a custom RISC instruction set architecture with 25+ instructions, 8 general-purpose registers, a complete ALU with overflow/carry detection, and a three-bus system (Instruction, Info, Control). Includes a **two-pass assembler** that compiles custom assembly to machine code, an interactive **step-through debugger** for inspecting register/memory state at each cycle, and memory-mapped I/O for console interaction. Ships with working assembly programs (Fibonacci generator, Hello World, countdown timer).

> Also implemented a second variant in **C** &mdash; [SoftwareCPU](https://github.com/mokshith245/SoftwareCPU) &mdash; with a documented ISA spec and full CPU architecture reference.

### [Campus Marketplace](https://github.com/mokshith245/Campus_Marketplace) &mdash; Java / React
A production-grade **multi-tenant SaaS platform** enabling university students to buy and sell items within their campus community. Architected with **tenant-isolated databases** (one PostgreSQL instance per university), dynamic subdomain-based routing, and a master database for tenant orchestration. Backend runs on Spring Boot 3 with JWT auth, Redis caching, and AWS S3 for media storage. Frontend built with React 18, Redux Toolkit, and Material-UI. Integrated **Google Gemini API** for AI-powered intelligent product search. Features include real-time messaging, shopping cart/wishlist management, admin analytics dashboards, and email verification workflows.


---

## Open Source Contributions

Active contributor to established open-source projects in the Android/mobile ecosystem:

- [**OpenMRS Android Client**](https://github.com/openmrs/openmrs-contrib-android-client) &mdash; Medical records system serving healthcare providers globally
- [**FOSSASIA SUSI.AI**](https://github.com/fossasia/susi_android) &mdash; Open-source AI assistant (Kotlin)
- [**FOSSASIA Phimpme**](https://github.com/niccokunzmann/phimpme-android) &mdash; Photo sharing & camera app (Java)
- [**PSLab Android**](https://github.com/fossasia/pslab-android) &mdash; Pocket science lab for electronics experiments
- [**Open Food Facts**](https://github.com/openfoodfacts/openfoodfacts-androidapp) &mdash; Collaborative food products database

---

## Architecture & Design Philosophy

- **Depth over breadth:** I don't just use tools -- I build them. Writing CPU emulators taught me what happens beneath every abstraction I rely on daily.
- **Production-grade defaults:** Even academic projects get proper auth, caching layers, tenant isolation, and CI-ready structure.
- **Systems thinking:** Whether designing a three-bus CPU architecture or a multi-tenant SaaS backend, the approach is the same: define clear interfaces, isolate concerns, and make failure modes explicit.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mokshith245&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mokshith245&layout=compact&hide_border=true&langs_count=8" alt="Top Languages" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mokshith245&hide_border=true" alt="GitHub Streak"/>
</p>

---

<p align="center">
  <a href="mailto:manimokshith1@gmail.com">Email</a> &bull;
  <a href="https://www.linkedin.com/in/mokshith245">LinkedIn</a> &bull;
  <a href="https://github.com/mokshith245">GitHub</a>
</p>

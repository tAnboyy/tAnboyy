<p align="center">
  <img src="assets/thanmay-banner.svg" width="100%" alt="Thanmay Mohandas Das — AI systems, thoughtful interfaces, dependable backends. From context to reasoning to action." />
</p>

<p align="center">
  <a href="https://tanboyy.github.io"><img src="https://img.shields.io/badge/PORTFOLIO-C7F36B?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=0D1117" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/thanmay-m-das-676240193/"><img src="https://img.shields.io/badge/LINKEDIN-80D6FF?style=for-the-badge&amp;logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzBEMTExNyIgZD0iTTYgOGgtNHYxNGg0ek00IDJhMiAyIDAgMSAwIDAgNCAyIDIgMCAwIDAgMC00ek04IDhoNHYyaC4xYzEtMiAzLTIgNC0yIDQgMCA0IDMgNCA3djdoLTR2LTdjMC0yIDAtNC0yLTQtMiAwLTIgMi0yIDR2N0g4eiIvPjwvc3ZnPg==" alt="LinkedIn" /></a>
  <a href="mailto:mdasthanmay@gmail.com"><img src="https://img.shields.io/badge/LET'S_TALK-F0B88A?style=for-the-badge&amp;logo=gmail&amp;logoColor=0D1117" alt="Email Thanmay" /></a>
</p>

<p align="center">
  <b>M.S. Computer Science @ UNC Charlotte</b> · Charlotte, NC<br />
  Generative AI · Backend Engineering · Web &amp; Mobile
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=tAnboyy&amp;label=Profile+views&amp;color=80d6ff&amp;style=flat" alt="Profile views" />
</p>

## Hey, I'm Thanmay.

I build software around questions I keep coming back to: **Can an AI tutor remember where a student struggled? Can a workout adapt when the next machine is taken? Can a complex document become an answer someone can actually use?**

Those questions have taken me from **payment-service backend development at CloudSphere IT Labs** and **enterprise backend engineering at ACI Worldwide**, to **agentic learning research at UNC Charlotte**, to **RAG development at Arch MI**. Along the way, I've built campus-navigation tools, mobile apps, and systems for learning and fitness.

I enjoy connecting the whole system: the interface someone touches, the API behind it, the data it depends on, and the AI workflow that helps them take the next step.

> My favorite engineering problems live where AI reasoning meets application state, real constraints, and a useful user experience.

<p align="center">
  <a href="#selected-builds">Selected builds</a> &nbsp; / &nbsp;
  <a href="#the-rest-of-the-workbench">More projects</a> &nbsp; / &nbsp;
  <a href="#tools-i-reach-for">Tech stack</a>
</p>

## Selected builds

### 01 / CourseLab
**A shared home for AI-supported learning.**

CourseLab brings Socratic conversations, academic reflections, and adaptive tutoring into a common course-and-assignment workflow. My work connects the learning tools with the platform infrastructure needed to make them work together.

- **One entry point:** a FastAPI gateway coordinates authentication, course access, assignment configuration, and handoffs between learning services.
- **Grounded conversations:** hybrid retrieval combines dense vector search with PostgreSQL full-text search to bring course evidence into the tutoring flow.
- **Consistent learning context:** published assignments preserve immutable document and configuration snapshots, so later source edits do not silently change the activity.
- **Persistent learning journeys:** saved attempts and stateful workflows let students resume their work; Canvas LTI integration connects the platform to course identity and context.

`Python` `FastAPI` `React` `PostgreSQL / pgvector` `LangGraph` `Docker` `Canvas LTI`

**[Explore CourseLab →](https://github.com/tAnboyy/CourseLab)**

### 02 / Spotter
**A workout plan should survive a busy gym.**

Spotter is an equipment-aware workout companion built around a simple situation: you're ready for the next exercise, but the machine is taken. The project combines workout planning, set and rest tracking, and a conversational coaching interface.

- **State-aware coaching:** ElevenLabs integration uses structured tool calls to connect conversational intent to supported workout actions.
- **A shared source of truth:** a FastAPI workout engine validates actions and synchronizes session updates through WebSockets.
- **Equipment-aware flow:** Taken reports can defer an exercise or offer an approved alternative while keeping the workout state consistent.
- **Across interfaces:** an Expo / React Native experience, a browser watch panel, and a SwiftUI Apple Watch prototype explore different ways to interact during a workout.

*Built with a teammate. Web-first; live-provider and native acceptance checks are tracked separately in the repository.*

`TypeScript` `React Native / Expo` `Python` `FastAPI` `SQLite` `WebSockets` `ElevenLabs` `SwiftUI prototype`

**[Explore Spotter →](https://github.com/tAnboyy/spotter)**

### 03 / Reflections
**Helping students examine how they learn.**

Reflections uses guided AI conversations to support academic reflection. Professors configure the learning experience, while students work through topic-based conversations or connect milestone reflections to relevant historical experiences.

- **Configurable learning:** modules define topics, depth, and probing styles instead of relying on one generic chatbot prompt.
- **Stateful conversations:** LangGraph workflows and PostgreSQL checkpointing preserve conversational context.
- **Relevant past experiences:** sentence embeddings and similarity matching connect student reflections with historical challenges.
- **Reviewable outputs:** reflection evaluations and an analytics interface help instructors inspect the resulting work.

`Python` `FastAPI` `React / Vite` `LangGraph` `PostgreSQL` `Sentence Transformers`

**[Explore Reflections →](https://github.com/tAnboyy/reflections-app)**

## The rest of the workbench

<details>
<summary><b>Open the project shelf — navigation, commerce, productivity, and gym research</b></summary>

### CampusNav / NMAMIT Map

My campus-navigation work began with an Android app built with Java, Kotlin, Google Maps, and Firebase. The broader CampusNav work explores searchable places, a teacher directory, offline fallbacks, university-specific configuration, and a Spring Boot backend with a React administration interface.

**Focus:** making unfamiliar campuses easier to navigate, with useful information available even when connectivity is unreliable.

[Original NMAMIT Guide repository →](https://github.com/tAnboyy/NMAMIT-Guide)

### Cinnamon

A food-ordering project spanning a React Native customer app, Spring Boot API, restaurant administration, and a marketing site. The customer journey includes menu browsing, weekly meal plans, a shared cart, order history, and platform-specific checkout, with Redux Toolkit, Firebase / Firestore, and Stripe integration.

[Customer app →](https://github.com/tAnboyy/cinnamon_customer-app)

### Hour Tracker

An Android-first productivity app pairing hourly activity logs with a goal for the next hour. Local SQLite storage, notification actions, missed-hour backfilling, dashboard summaries, and CSV export keep the core workflow practical; optional Supabase synchronization connects it to a cloud account.

[Repository →](https://github.com/tAnboyy/hour-tracker-app)

### UREC Live & gym scheduling research

Connected-fitness work across a member app, Spring Boot services, and gym administration. A related Python / SimPy simulation workspace explores equipment contention, advisory scheduling, and what changes when people accept or decline recommendations.

**Research interest:** testing scheduling assumptions through reproducible experiments before drawing conclusions about a real gym.

### Incridea

Collaborated in a six-person team on an event platform using React, Node.js, Firebase, and Razorpay. Worked across the frontend, backend APIs, authentication, and payment integration.

</details>

## Tools I reach for

**Languages**

![Python](https://img.shields.io/badge/Python-161B22?style=for-the-badge&logo=python&logoColor=80D6FF) ![Java](https://img.shields.io/badge/Java-161B22?style=for-the-badge&logoColor=80D6FF) ![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=for-the-badge&logo=typescript&logoColor=80D6FF) ![JavaScript](https://img.shields.io/badge/JavaScript-161B22?style=for-the-badge&logo=javascript&logoColor=80D6FF) ![SQL](https://img.shields.io/badge/SQL-161B22?style=for-the-badge&logoColor=80D6FF) ![Kotlin](https://img.shields.io/badge/Kotlin-161B22?style=for-the-badge&logo=kotlin&logoColor=80D6FF)

**AI & retrieval**

![LangGraph](https://img.shields.io/badge/LangGraph-161B22?style=for-the-badge&logo=langgraph&logoColor=80D6FF) ![LangChain](https://img.shields.io/badge/LangChain-161B22?style=for-the-badge&logo=langchain&logoColor=80D6FF) ![OpenAI API](https://img.shields.io/badge/OpenAI%20API-161B22?style=for-the-badge&logoColor=80D6FF) ![pgvector](https://img.shields.io/badge/pgvector-161B22?style=for-the-badge&logo=postgresql&logoColor=80D6FF)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=for-the-badge&logo=fastapi&logoColor=80D6FF) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-161B22?style=for-the-badge&logo=springboot&logoColor=80D6FF) ![Node.js](https://img.shields.io/badge/Node.js-161B22?style=for-the-badge&logo=nodedotjs&logoColor=80D6FF) ![WebSockets](https://img.shields.io/badge/WebSockets-161B22?style=for-the-badge&logoColor=80D6FF)

**Web & mobile**

![React](https://img.shields.io/badge/React-161B22?style=for-the-badge&logo=react&logoColor=80D6FF) ![React Native](https://img.shields.io/badge/React%20Native-161B22?style=for-the-badge&logo=react&logoColor=80D6FF) ![Expo](https://img.shields.io/badge/Expo-161B22?style=for-the-badge&logo=expo&logoColor=80D6FF) ![Angular](https://img.shields.io/badge/Angular-161B22?style=for-the-badge&logo=angular&logoColor=80D6FF) ![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-161B22?style=for-the-badge&logo=redux&logoColor=80D6FF) ![SwiftUI](https://img.shields.io/badge/SwiftUI-161B22?style=for-the-badge&logo=swift&logoColor=80D6FF)

**Data & messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161B22?style=for-the-badge&logo=postgresql&logoColor=80D6FF) ![MongoDB](https://img.shields.io/badge/MongoDB-161B22?style=for-the-badge&logo=mongodb&logoColor=80D6FF) ![Redis](https://img.shields.io/badge/Redis-161B22?style=for-the-badge&logo=redis&logoColor=80D6FF) ![SQLite](https://img.shields.io/badge/SQLite-161B22?style=for-the-badge&logo=sqlite&logoColor=80D6FF) ![Firebase](https://img.shields.io/badge/Firebase-161B22?style=for-the-badge&logo=firebase&logoColor=80D6FF) ![Supabase](https://img.shields.io/badge/Supabase-161B22?style=for-the-badge&logo=supabase&logoColor=80D6FF) ![Kafka](https://img.shields.io/badge/Kafka-161B22?style=for-the-badge&logo=apachekafka&logoColor=80D6FF) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-161B22?style=for-the-badge&logo=rabbitmq&logoColor=80D6FF)

**Delivery & testing**

![Azure](https://img.shields.io/badge/Azure-161B22?style=for-the-badge&logoColor=80D6FF) ![Docker](https://img.shields.io/badge/Docker-161B22?style=for-the-badge&logo=docker&logoColor=80D6FF) ![Git](https://img.shields.io/badge/Git-161B22?style=for-the-badge&logo=git&logoColor=80D6FF) ![Postman](https://img.shields.io/badge/Postman-161B22?style=for-the-badge&logo=postman&logoColor=80D6FF) ![Linux](https://img.shields.io/badge/Linux-161B22?style=for-the-badge&logo=linux&logoColor=80D6FF) ![OpenShift](https://img.shields.io/badge/OpenShift-161B22?style=for-the-badge&logo=redhatopenshift&logoColor=80D6FF)

<details>
<summary>More tools & practices</summary>

Sentence Transformers · Hybrid Search · Reranking · MCP · LangSmith · RAGAS · DeepEval · Azure AI Evals · Spring Batch · REST · Oracle DB · Azure DevOps · CI/CD · VMware Tanzu · OAuth 2.0 · JWT · RBAC · Checkmarx · Black Duck · ELK Stack · PCI DSS

</details>

---

<p align="center">
  <b>Building around learning, movement, and everyday decisions.</b><br /><br />
  Interested in AI engineering, backend systems, or a thoughtful product idea?<br />
  <a href="mailto:mdasthanmay@gmail.com"><img src="https://img.shields.io/badge/Let's_talk-F0B88A?style=for-the-badge&amp;logo=gmail&amp;logoColor=0D1117" alt="Let's talk" /></a>
  <a href="https://tanboyy.github.io/"><img src="https://img.shields.io/badge/See_my_portfolio-C7F36B?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=0D1117" alt="See my portfolio" /></a>
  <a href="https://www.linkedin.com/in/thanmay-m-das-676240193/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-80D6FF?style=for-the-badge&amp;logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzBEMTExNyIgZD0iTTYgOGgtNHYxNGg0ek00IDJhMiAyIDAgMSAwIDAgNCAyIDIgMCAwIDAgMC00ek04IDhoNHYyaC4xYzEtMiAzLTIgNC0yIDQgMCA0IDMgNCA3djdoLTR2LTdjMC0yIDAtNC0yLTQtMiAwLTIgMi0yIDR2N0g4eiIvPjwvc3ZnPg==" alt="Connect on LinkedIn" /></a>
</p>

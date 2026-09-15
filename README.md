<h1 align="center">Muhammad Umer</h1>

<h3 align="center">Mobile &amp; Full Stack Engineer · Testing &amp; Safety Infrastructure for On-Device AI</h3>

<!-- Typing animation tagline -->
<p align="center">
  <a href="https://github.com/Umer9538">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=800&color=1F3A5F&center=true&vCenter=true&width=760&lines=Testing+%26+safety+infrastructure+for+on-device+AI.;Author+of+7+open-source+packages+%C2%B7+500%2B+tests+%C2%B7+3+languages.;5%2B+years+shipping+production+mobile+apps+with+native+depth.;Two+investor-acquired+AI+products%2C+delivered+end-to-end." alt="typing"/>
  </a>
</p>

<!-- Quick contact row -->
<p align="center">
  <a href="mailto:muhammadumer7574@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://linkedin.com/in/muhammadumer2521"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/Umer9538"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Faisalabad,_Pakistan-555555?style=for-the-badge" alt="Location"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Umer9538&label=Profile%20views&color=1F3A5F&style=flat-square" alt="profile views"/>
</p>

---

## About

Mobile App Developer with **5+ years** shipping production cross-platform apps in Flutter, React Native, and native Android/iOS (Kotlin, Java, Swift). I build AI into mobile products under real latency and offline constraints — live translation, speech-to-text, text-to-speech, LLM chatbots, and RAG assistants.

I'm also the author of a seven-package open-source testing and safety layer for on-device AI: roughly 500 tests across Swift, TypeScript, and Dart, including a published finding that Apple's on-device model failed parity with itself.

- **5+ years professional experience** across mobile-first delivery, AI integration, and full-stack backend
- Currently **Software Engineer, Mobile** at **Infinitiv.AI**, Lahore
- Author of **seven open-source packages** — ~500 tests across Swift, TypeScript, and Dart
- Delivered **two investor-acquired AI products** end-to-end as a contract developer at **DriftMeta**
- Promoted to **Full Stack Engineer** at Vireon Solutions after 4.5 years
- **BS Software Engineering**, **FAST National University of Computer &amp; Emerging Sciences**, Islamabad

---

## Currently

```yaml
Role:         Software Engineer, Mobile @ Infinitiv.AI
Open source:  Testing & safety layer for on-device AI (7 packages, ~500 tests)
Recent:       Published finding — Apple's on-device model failing parity with itself
Learning:     LLM eval methodology · statistical testing at scale
Open to:      AI safety / eval infrastructure · Mobile · Full Stack (remote / relocation)
Toolkit:      Claude, Cursor, Xcode, VS Code
```

---

## Open Source

### Testing &amp; Safety Layer for On-Device AI — 2026

Author of seven open-source packages (~500 tests across Swift, TypeScript, and Dart) providing regression gates, deterministic record/replay, PII redaction, and drift observability for on-device AI. Every claim below is verifiable in a public repository.

| Package | Purpose | Notable |
|---|---|---|
| **unswayed** *(Swift + npm)* | Statistical parity gate for AI model swaps | Wilson/Newcombe confidence intervals · Published finding: Apple's on-device model failing parity with itself (compliance dropping from 100% to 40%, 95% CI [−0.88, −0.03]) |
| **[underfoot](https://umer9538.github.io/underfoot)** | Public drift observatory for OS-bundled AI models | Live findings on Apple and Google AI silently drifting between OS builds |
| **vouch** *(pub.dev)* | CI regression gate for on-device LLMs | 85 tests · Hardened by 2 adversarial audit rounds |
| **llm_replay_eval** *(pub.dev)* | Deterministic record/replay for on-device LLMs | The "VCR" HTTP-based tools can't be — cassettes make LLM tests offline and CI-safe |
| **redact** *(pub.dev)* | On-device PII redaction around every LLM call | 164 tests · Zero dependencies · 15+ secret/PII detectors with checksum validation |
| **golden_lens** *(pub.dev)* | Agent-legible golden/visual tests | Machine-readable reports an AI coding agent can act on directly |

**Why this work exists:** LLMs are being shipped into products where quiet regressions have real consequences — a model swap that silently changes behaviour, an availability API that reports "available" while every generation fails, a guardrail layer that drifts between OS builds. The tooling to catch these problems doesn't fully exist yet. These packages are my attempt to build some of it.

---

## Experience

### Software Engineer, Mobile — Infinitiv.AI
*Lahore, PK · Hybrid · Aug 2025 – Present*

Architected and shipped end-to-end production mobile applications in Flutter and React Native, applying Clean Architecture, SOLID principles, and modern state management (Bloc, Provider, Riverpod) for modular, testable codebases. Engineered real-time features including live translation, speech-to-text, text-to-speech, BLE device communication, and WebSocket-based streaming. Optimised performance through efficient JSON parsing, image and network caching, lazy loading, and memory management, reducing cold-start time on low-end devices. Deployed supporting APIs on AWS EC2 with Docker and CI/CD pipelines.

### Mobile App Developer (6-Month Contract) — DriftMeta
*Islamabad, PK · Remote · May 2025 – Oct 2025*

Built and scaled two investor-acquired mobile-first products end-to-end, from ideation and prototyping through deployment and investor handoff.

### Mobile Application Developer → Full Stack Engineer — Vireon Solutions
*Islamabad, PK · Remote · Nov 2020 – Apr 2025 · Promoted 2024*

Joined as a junior developer during the first year of university and grew over 4.5 years across mobile-first delivery, AI feature integration, and full-stack backend work. Developed AI-driven mobile applications with Flutter and React Native, integrating NLP chat systems, speech recognition, text-to-speech, and recommendation engines using TensorFlow, PyTorch, and LangChain. Deployed mobile backends on AWS EC2 and Heroku with Docker and CI/CD pipelines.

---

## Selected Project Work

### AI Learning Platform — DriftMeta *(investor-acquired)* · 2025
*Flutter · Flask · LangChain · OpenAI API · WebRTC*

Cross-platform learning app generating courseware with LLMs, evaluating submitted code in real time, and adapting personalised learning paths — with a Flask and LangChain backend and WebRTC sessions wired into the Flutter client.

### In-App Semantic Search &amp; Contextual Chat — Vireon Solutions · 2023 – 2025
*FastAPI · Node.js · Redis · FAISS · ChromaDB · RAG*

RAG architectures with FAISS and ChromaDB powering in-app semantic search and contextual chat, served through mobile-facing FastAPI and Node.js APIs with Redis caching to hold response times under mobile network conditions.

### First Air Tag — NFC-Based Emergency Medical Platform · 2025 – 2026
*React Native · Expo · NFC · JWT · 2FA · Biometrics · Multi-Tenant RBAC*

Platform enabling first responders to read encrypted medical profiles by tapping NFC wristbands — offline, and without the app installed. JWT authentication with OTP and token resets, email verification, two-factor authentication, biometric login (Face ID / fingerprint), and multi-tenant RBAC across Individual, Organisation, and Admin accounts.

### Native BLE &amp; NFC Module Layer — Infinitiv.AI · 2025 – 2026
*Kotlin · Java · Swift · BLE · NFC · WebSockets · Background Services*

Native Android and iOS modules bridging BLE device communication, NFC, and background services into cross-platform Flutter and React Native apps, with WebSocket streaming for low-latency interaction.

### Mershed — AI-Powered Travel Companion · 2024
*Flutter · Gemini 1.5 Flash · Google Maps · Routes API · Nominatim · Overpass*

AI travel assistant generating personalised itineraries across five Saudi cities, plus a TravelGenie chatbot with offline-capable caching. Integrated mapping, transit, live hotel booking, and event APIs.

### BuildBuddy — Real-Time Construction Management Platform · 2024 – 2025
*Flutter (Android · iOS · Web) · Firebase · Cloud Functions · Stripe · Google Maps*

Cross-platform construction management app for homeowners, contractors, architects, and vendors to collaboratively track budgets, milestones, and progress. Automated milestone-budget allocation with instant deduction on completion, real-time multi-role synchronisation, Stripe payments, in-app messaging, weather forecasting, and SLA tracking.

### Maternity Care Chatbot — DriftMeta *(investor-acquired)* · 2025
*Flutter · Node.js · Firebase*

Consultancy chatbot for expecting mothers over a structured medical knowledge base, with real-time Q&amp;A and Firebase-backed sessions.

---

## Technical Skills

**Languages**

![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![NFC](https://img.shields.io/badge/NFC-1F3A5F?style=flat-square)
![Offline First](https://img.shields.io/badge/Offline--First-555555?style=flat-square)

**State Management &amp; Architecture**

![Bloc](https://img.shields.io/badge/Bloc-2496ED?style=flat-square)
![Riverpod](https://img.shields.io/badge/Riverpod-0175C2?style=flat-square)
![Provider](https://img.shields.io/badge/Provider-42A5F5?style=flat-square)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-1F3A5F?style=flat-square)
![SOLID](https://img.shields.io/badge/SOLID-1F3A5F?style=flat-square)
![MVVM](https://img.shields.io/badge/MVVM-1F3A5F?style=flat-square)

**Frontend &amp; Backend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-1F3A5F?style=flat-square)

**AI / ML &amp; On-Device AI**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FAISS_·_ChromaDB-blueviolet?style=flat-square)
![Apple Foundation Models](https://img.shields.io/badge/Apple_Foundation_Models-000000?style=flat-square&logo=apple&logoColor=white)
![On-Device LLMs](https://img.shields.io/badge/On--Device_LLMs-1F3A5F?style=flat-square)
![Speech](https://img.shields.io/badge/Speech--to--Text_·_TTS-1F3A5F?style=flat-square)

**Testing &amp; Evaluation**

![Statistical Testing](https://img.shields.io/badge/Statistical_Testing-Wilson%2FNewcombe_CIs-1F3A5F?style=flat-square)
![LLM Evals](https://img.shields.io/badge/LLM_Evals-Record%2FReplay-1F3A5F?style=flat-square)
![Golden Tests](https://img.shields.io/badge/Golden_Tests-1F3A5F?style=flat-square)
![CI Regression Gates](https://img.shields.io/badge/CI_Regression_Gates-1F3A5F?style=flat-square)
![Drift Observability](https://img.shields.io/badge/Drift_Observability-1F3A5F?style=flat-square)
![XCTest](https://img.shields.io/badge/XCTest-0F0F0F?style=flat-square&logo=swift&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

**Security &amp; Auth**

![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![2FA](https://img.shields.io/badge/2FA_·_OTP-1F3A5F?style=flat-square)
![Biometrics](https://img.shields.io/badge/Biometric_Auth-1F3A5F?style=flat-square)
![RBAC](https://img.shields.io/badge/Multi--Tenant_RBAC-1F3A5F?style=flat-square)
![PII Redaction](https://img.shields.io/badge/PII_Redaction-1F3A5F?style=flat-square)

**Databases &amp; Cloud**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat-square&logo=heroku&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Tools &amp; Integrations**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google_Maps_SDK-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black)

---

## How I Work

> **Trust the tests, not the vendor.** On-device AI models silently drift between OS builds. Availability APIs lie. If your only source of truth is a vendor's documentation, you're already wrong. Verify.
>
> **Ship over polish, but never below the bar.** Outcomes matter more than perfection. Ship the smallest thing that actually works, then iterate with real signal.
>
> **Own the whole loop.** From product conversation to architecture to deployment to the metric that proves it worked. Hand-offs are where things break.
>
> **AI as leverage, not a shortcut.** I use Claude and Cursor every day — for code review, refactoring, exploring trade-offs. The point is to ship better software faster, never to skip the thinking.
>
> **Real systems live in the real world.** Production code has to work on a low-end device, on a flaky connection, on an OS build that changed something silently overnight. Build for that, not the demo.

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Umer9538&show_icons=true&count_private=true&theme=default&hide_border=true&include_all_commits=true" alt="GitHub Stats" height="170"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Umer9538&theme=default&hide_border=true" alt="GitHub Streak" height="170"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Umer9538&layout=compact&theme=default&hide_border=true&langs_count=10" alt="Top Languages" height="170"/>
</p>

### Contribution Calendar

<p align="center">
  <img src="https://ghchart.rshah.org/1F3A5F/Umer9538" alt="Muhammad Umer's GitHub Contribution Chart"/>
</p>

---

## Other Projects

- **GroceryMate** *(Flutter, Firebase)* — Smart grocery list app with real-time sharing, barcode scanning, and speech-to-text input
- **HealthSync** *(Flutter, AI)* — Personal health tracker with Google Fit integration, reminders, chatbot, and telemedicine booking
- **AI Chatbot Assistant** *(Flutter, OpenAI API)* — Conversational AI assistant with context awareness and mobile integration
- **SecurePay** *(Flutter, Firebase, Stripe)* — Secure payment application with multi-factor authentication

---

## Education &amp; Achievements

**BS Software Engineering** — FAST National University of Computer &amp; Emerging Sciences, Islamabad

- **1st Place** — Software Sprint (2020)
- **1st Place** — DAIRA (2021)
- **3rd Place** — Cross-Platform Mobile App Hackathon, GIKI (2025)
- **Winner** — Speed Programming, NASCON (2024)
- **Dean's List** — Fall 2021, Spring 2022, Fall 2024 (top 10% of cohort)
- **Admin Head, FCAP** — Led 100+ members at the FAST Club of App Development &amp; Programming, across CS, AI, GenAI, and Data Science
- **Teaching Assistant** — Supported 600+ students across Programming Fundamentals, OOP, Data Structures, Algorithms, and Artificial Intelligence

---

## Get in Touch

Currently open to opportunities in **AI safety &amp; eval infrastructure**, **mobile engineering**, and **full-stack engineering**. Open to remote work and to relocating (New Zealand, Australia, EU, US).

If you're working on the reliability, safety, or evaluation of AI systems — especially on-device — I'd love to talk.

<p align="center">
  <a href="https://linkedin.com/in/muhammadumer2521"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:muhammadumer7574@gmail.com"><img src="https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

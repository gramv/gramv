# Goutham Vemula

**AI Engineer | LLM Application Developer**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

---

AI Engineer with 6+ years building production software, now focused on shipping LLM-powered applications. I design RAG pipelines, AI voice and chat agents, and tool-calling integrations using OpenAI, Anthropic Claude, and Google Gemini. Founder of [Vector Wrap LLC](https://github.com/Gramv) — an AI product studio building conversational and voice-AI agents for hospitality and retail.

---

## Currently Building — SommelierAI

An AI voice and chat agent platform for restaurants, built on top of Clover POS. Customers order through QR codes, phone calls, or the web — every order flows into one unified kitchen system.

```mermaid
flowchart LR
    M["Clover Menu"] --> AI["Restaurant AI"]
    AI --> QR["QR Table Ordering"]
    AI --> PH["AI Phone Ordering"]
    AI --> WEB["Website Ordering"]
    QR --> ORD["One Order Pipeline"]
    PH --> ORD
    WEB --> ORD
    ORD --> KDS["Kitchen Display"]
    KDS --> ST["Preparing \u2192 Ready \u2192 Served"]
    ST --> PAY["Payment & Tracking"]
```

**Key capabilities:**

- **AI Phone Ordering** — Voice agent answers calls, takes takeout orders, books reservations (Google Gemini Live + Twilio + Deepgram)
- **QR Table Ordering** — Guests scan, ask natural questions ("What's vegetarian?"), and order from their phone
- **Group Ordering** — Shared carts where friends order from their own devices, host reviews and submits
- **Kitchen Display System** — Color-coded tickets, station routing, course firing, 86 board
- **Menu Intelligence** — RAG-powered recommendations with hybrid (dense + keyword) search over wine/varietal knowledge base
- **Waiter Tools** — Real-time notifications for orders, check requests, food ready alerts
- **Reservations** — Capacity-aware booking with conflict detection
- **Bilingual** — Full English + Spanish across all channels

`4 pilot restaurants configured` · `Clover POS developer integration approved` · `Bilingual voice agents`

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_Live-4285F4?style=flat-square&logo=google&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Clover](https://img.shields.io/badge/Clover_POS-22B24C?style=flat-square)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)

---

## Featured Projects

### AI Document Intelligence Platform — Hotel Onboarding

Built for LakeCrest. Digitized paper-based hotel employee onboarding with AI-powered document processing, automating federal forms (I-9, W-4) and cutting per-employee admin time from hours to minutes.

`50,000+ LOC` · `245+ API endpoints` · `40+ database tables` · `Production on AWS`

- OCR + LLM pipeline auto-extracts and validates data from uploaded IDs (driver's license, passport, SSN card)
- LLM-powered field auto-fill, validation, and bilingual (EN/ES) support across 16-step onboarding portal
- Field-level encryption for PII (SSN, bank details), Secrets Manager, token-based auth, full audit logging
- AWS: ECS Fargate, RDS PostgreSQL, S3 with KMS, ALB, CloudWatch (9 alarms), Terraform IaC

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

---

### OTCMed Assist — AI Medical Assessment

AI symptom-assessment app with Groq LLM integration. Dynamic age-specific questionnaire, AI-powered visual symptom detection from images, and personalized safety-checked medication guidance with generated medical reports.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

---

### Flyerbot — Restaurant Content Generator

AI-powered content and image generator for restaurant events, promotions, and marketing materials.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

### Store Management System — Retail Platform

Full-stack Flask + PostgreSQL retail platform with multi-role authentication, automated sales reconciliation, dual supplier-ordering workflows, and Chart.js analytics dashboard.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

---

## Tech Stack

**AI & LLMs**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D4A054?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=for-the-badge)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Infrastructure & Data**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Gramv&show_icons=true&theme=dark&title_color=D4A054&icon_color=D4A054&border_color=D4A054&hide_border=false" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gramv&layout=compact&theme=dark&title_color=D4A054&border_color=D4A054&hide_border=false" alt="Top Languages" />
</p>

---

<p align="center">
  <a href="https://www.linkedin.com/in/goutham-vemula-766a5a1">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:vgoutamram@gmail.com">
    <img src="https://img.shields.io/badge/Email-D4A054?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Gramv">
    <img src="https://img.shields.io/badge/GitHub-Gramv-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p># Goutham Vemula


**Full-Stack Engineer | AI Products for Hospitality**


![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)


---


I build AI-powered products that solve real operational problems in the restaurant and hospitality industry. Currently focused on [SommelierAI](https://sommelierai.com) — a multi-channel restaurant platform that turns a Clover POS into an AI-driven ordering and operations system.


---


## Currently Building — SommelierAI


A single AI operating layer around Clover POS. Customers order through QR codes, phone calls, or the web — every order flows into one unified kitchen system.


```mermaid
flowchart LR
    M["Clover Menu"] --> AI["Restaurant AI"]
    AI --> QR["QR Table Ordering"]
    AI --> PH["AI Phone Ordering"]
    AI --> WEB["Website Ordering"]
    QR --> ORD["One Order Pipeline"]
    PH --> ORD
    WEB --> ORD
    ORD --> KDS["Kitchen Display"]
    KDS --> ST["Preparing → Ready → Served"]
    ST --> PAY["Payment & Tracking"]
```


**What it does:**


- **AI Phone Ordering** — Voice agent "Jamie" answers calls, takes takeout orders, books reservations via Twilio + Deepgram
- **QR Table Ordering** — Guests scan, browse, ask questions ("What is vegetarian?"), and order from their phone
- **Group Ordering** — DoorDash-style shared carts where friends order from their own devices
- **Kitchen Display System** — Color-coded tickets, station routing, course firing, 86 board
- **Waiter Tools** — Real-time notifications for new orders, check requests, food ready alerts
- **Menu Intelligence** — AI-generated dietary tags, allergen detection, food & wine pairings, upsell suggestions
- **Reservations** — Capacity-aware booking with automatic conflict detection
- **Bilingual** — Full English + Spanish support across all channels


![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Clover](https://img.shields.io/badge/Clover_POS-22B24C?style=flat-square)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)


---


## Featured Projects


### Hotel Employee Onboarding System


Enterprise-grade digital onboarding platform for the hospitality industry. Replaces paper-based I-9, W-4, and benefits enrollment with a mobile-first, bilingual digital experience.


`50,000+ LOC` · `245+ API endpoints` · `40+ database tables` · `Production on AWS`


- QR code recruitment → 7-step job application → 16-step onboarding portal → sequential manager approval# Goutham Vemula

**Full-Stack Engineer | AI Products for Hospitality**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

I build AI-powered products that solve real operational problems in the restaurant and hospitality industry. Currently focused on [SommelierAI](https://sommelierai.com) — a multi-channel restaurant platform that turns a Clover POS into an AI-driven ordering and operations system.

---

## Currently Building — SommelierAI

A single AI operating layer around Clover POS. Customers order through QR codes, phone calls, or the web — every order flows into one unified kitchen system.

```mermaid
flowchart LR
    M["Clover Menu"] --> AI["Restaurant AI"]
    AI --> QR["QR Table Ordering"]
    AI --> PH["AI Phone Ordering"]
    AI --> WEB["Website Ordering"]
    QR --> ORD["One Order Pipeline"]
    PH --> ORD
    WEB --> ORD
    ORD --> KDS["Kitchen Display"]
    KDS --> ST["Preparing → Ready → Served"]
    ST --> PAY["Payment & Tracking"]
```

**What it does:**

- **AI Phone Ordering** — Voice agent "Jamie" answers calls, takes takeout orders, books reservations via Twilio + Deepgram
- **QR Table Ordering** — Guests scan, browse, ask questions ("What is vegetarian?"), and order from their phone
- **Group Ordering** — DoorDash-style shared carts where friends order from their own devices
- **Kitchen Display System** — Color-coded tickets, station routing, course firing, 86 board
- **Waiter Tools** — Real-time notifications for new orders, check requests, food ready alerts
- **Menu Intelligence** — AI-generated dietary tags, allergen detection, food & wine pairings, upsell suggestions
- **Reservations** — Capacity-aware booking with automatic conflict detection
- **Bilingual** — Full English + Spanish support across all channels

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Clover](https://img.shields.io/badge/Clover_POS-22B24C?style=flat-square)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)

---

## Featured Projects

### Hotel Employee Onboarding System

Enterprise-grade digital onboarding platform for the hospitality industry. Replaces paper-based I-9, W-4, and benefits enrollment with a mobile-first, bilingual digital experience.

`50,000+ LOC` · `245+ API endpoints` · `40+ database tables` · `~$92/mo AWS cost`

- QR code recruitment → 7-step job application → 16-step onboarding portal → sequential manager approval
- Federal form compliance (I-9 with 3-day deadline tracking, W-4) with digital signatures
- OCR document processing, field-level encryption (SSN, bank accounts)
- Full AWS infrastructure: ECS Fargate, RDS PostgreSQL, S3, CloudWatch, ALB, Terraform IaC

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

---

### Flyerbot

AI-powered content and image generator for restaurant events, promotions, and marketing materials.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

### MedAssist

AI companion for safe, personalized over-the-counter medication guidance.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

---

## Tech Stack

**Languages & Frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**AI & Voice**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=for-the-badge&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Gramv&show_icons=true&theme=dark&title_color=D4A054&icon_color=D4A054&border_color=D4A054&hide_border=false" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gramv&layout=compact&theme=dark&title_color=D4A054&border_color=D4A054&hide_border=false" alt="Top Languages" />
</p>

---

<p align="center">
  <a href="mailto:gvemula@mail.yu.edu">
    <img src="https://img.shields.io/badge/Email-gvemula%40mail.yu.edu-D4A054?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Gramv">
    <img src="https://img.shields.io/badge/GitHub-Gramv-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

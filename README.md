# Goutham Vemula


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

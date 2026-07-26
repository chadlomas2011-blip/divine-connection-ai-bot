# divine-connection-ai-bot
"AI-powered concierge chatbot for NLP coaching and hypnotherapy practice, built with Botpress, Durable, and HubSpot."
# Divine Connection — AI Lead Concierge & CRM Integration

An intelligent multi-path chatbot built for a life coaching and hypnotherapy practice (**Divine Care Connection**). The bot qualifies inbound visitors, captures lead attributes, routes conversation flows based on intent, and automatically syncs lead profiles with HubSpot CRM.

---

## 🌟 Key Features

* **Intent Routing:** Automatically distinguishes between **Sales** (pricing, booking) and **Marketing** (advice, tips) user intents.
* **Lead Qualification:** Captures core fields (`user.name`, `user.email`, `user.intent`, `user.pain_point`) in real-time.
* **Seamless CRM Sync:** Directly pushes qualified leads into **HubSpot CRM** with intent notes attached.
* **Embed Integration:** Deployed seamlessly onto a **Durable AI** web platform.

---

## 🏗️ Architecture & Stack

| Layer | Tool | Purpose |
| --- | --- | --- |
| **Bot Engine** | Botpress | Handles NLU, intent extraction, and state variables |
| **Web Host** | Durable AI | Hosts the live frontend site and embedded chat widget |
| **CRM Backend** | HubSpot | Stores qualified contact records and triggers alerts |

---

## 🧠 System Prompt & Routing Rules

The core routing logic utilizes the following prompt instructions:

> "I want Divine Connection to act as a smart concierge...
> 1. Collect user.name, user.email, user.intent, user.pain_point.
> 2. Route Sales queries toward session bookings.
> 3. Route Marketing queries toward value-driven content."

---

## 📱 Live Demo

* **Live Site:** [www.divinecareconnection.com]
* **Bot Status:** Live / Active

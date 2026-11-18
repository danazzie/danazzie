# Danagul Azimzhanova

I build AI agents and full-stack products. The four repositories below are the ones to open: each has a setup, an architecture, and a straight account of what the code does.

Kazakhstan · [LinkedIn](https://www.linkedin.com/in/danagul-azimzhanova-infosystems/) · dakamaka95@gmail.com

## Featured work

### [Almaty Table](https://github.com/danazzie/almaty-table-ai-avatar)

A restaurant guide for Almaty you can talk to by text, voice, or photo. Two custom MCP servers collect live listings from 2GIS and deals from Chocolife. GPT-4o-mini calls those tools, and the answer can come back as speech in a cloned voice and a lip-synced avatar. Scrapes are cached, paid steps are behind flags, and a failed server does not take down the others.

### [HireMind](https://github.com/danazzie/agenthire-ai-hackathon)

A PayPal sandbox settlement layer for work done by agents and people. Buyer and seller each authorize a hold. A test compiled before the holds, and hashed onto both orders, decides the outcome: pass pays the seller, fail pays the buyer. The screen, the API, and a recorded sandbox run are in the repo. The web app responds at [hire-mind-web.onrender.com](https://hire-mind-web.onrender.com).

### [Movie Assistant](https://github.com/danazzie/llm-movie-assistant)

A local movie agent. Llama 3.1 runs through Ollama, LangChain tools call the OMDb API, and a summary buffer keeps the conversation inside a token budget. Genre and rating lookups are documented as samples, because OMDb search matches titles. Twenty unit tests run without a key or a model.

### [AICademy](https://github.com/danazzie/AICademy)

An AI course marketplace. A Spring Boot service holds a curated catalog and ranks six courses from role, experience, interests, and goals. The React UI adds search, category and price filters, and eight career paths that re-rank the same catalog in the browser. Ranking rules are in the README, including the profile fields the score does not use yet.

## Also on this account

| Repository | What it is |
|---|---|
| [ElderlyCareApp](https://github.com/danazzie/ElderlyCareApp) | A product note for a family care coordinator. The application is not in the repository. |
| [AICademy-Frontend](https://github.com/danazzie/AICademy-Frontend) | The AICademy interface packaged with a static file server. The full stack is [AICademy](https://github.com/danazzie/AICademy). |
| [Mayan-EDMS](https://github.com/danazzie/Mayan-EDMS), [github-recitation](https://github.com/danazzie/github-recitation), [github-setup](https://github.com/danazzie/github-setup) | Course forks from CMU 17-313 (2022). The products are upstream. My commits are a small content edit, a zero-handling fix, and the Git setup exercise. |
| [openlibrary](https://github.com/danazzie/openlibrary) | A 2022 fork of [internetarchive/openlibrary](https://github.com/internetarchive/openlibrary). Upstream project. |
| [iq_game_edge](https://github.com/danazzie/iq_game_edge) | The first repository on this account (2020): a one-line Python hello-world. |

## Stack in the featured repos

| | |
|---|---|
| Agents | LangChain tool calling, MCP over stdio, Claude agents, local Llama 3.1 through Ollama |
| Languages | Python, Java 17, Kotlin, JavaScript |
| Services | Spring Boot 3, Postgres, Flyway, React, Vite, Gradio |
| External systems | PayPal Orders and Payouts (sandbox), OMDb, OpenAI, 2GIS, Chocolife, fal.ai |

Coursework in software engineering: CMU 17-313, Foundations of Software Engineering (2022). The course forks above are that work.

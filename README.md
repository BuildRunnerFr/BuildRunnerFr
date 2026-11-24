<p align="right">🇬🇧 English · <a href="./README.fr.md">🇫🇷 Français</a></p>

<h1 align="center">Hey, I'm Ethan Blombou 👋</h1>

<p align="center">
  <a href="https://github.com/BuildRunnerFr">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=7DC42A&center=true&vCenter=true&width=640&lines=Agentic+AI+%C3%97+Cybersecurity;Building+agents+that+check+things+for+real;3+hackathons+in+a+month+(and+counting)" alt="Agentic AI × Cybersecurity"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ethan-blombou"><img src="https://img.shields.io/badge/LinkedIn-ethan--blombou-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ethancte@gmail.com"><img src="https://img.shields.io/badge/Email-ethancte%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/📍-Paris%20·%20Brest-1f2937?style=flat" alt="Paris · Brest"/>
</p>

Engineering student at **IMT Atlantique** (Computer Science, Networks & Telecoms) and **cybersecurity apprentice at Société Générale**, in the Group CIO Office.
I come from networks and cyber, and I'm moving deep into **agentic AI, ML and data science**. My favourite projects sit right where the two meet: AI agents that check whether systems are really as secure as people say.

I like stepping out of my comfort zone: new domain, new stack, 24 hours, let's ship it. That's why I keep signing up for hackathons.

```python
class Ethan:
    school    = "IMT Atlantique — Master of Engineering, apprenticeship (2025–2028)"
    work      = "Société Générale — cybersecurity apprentice, Group CIO Office"
    into      = ["agentic AI", "machine learning", "data science", "cybersecurity"]
    crush     = "quant finance (stochastic processes class got me)"
    languages = {"French": "native", "English": "C1", "Spanish": "B1"}
    off_duty  = ["CTFs on Root-Me / TryHackMe / Hack The Box", "football", "chess"]
    chess_elo = 1250  # the only benchmark I'm not optimizing (yet)

    def workflow(self):
        return "I design and decide, coding agents handle the tedious parts, I review and ship."
```

---

## 🚀 What I've built

### 🔺 [TRIAD](https://github.com/BuildRunnerFr/triad) — adversarial NIS2 cyber audit
*Hackathon Deloitte × Google Cloud · team project* · [**Live demo →**](https://triad-311153381291.europe-west9.run.app)

Four AI agents cross-check **what the IT department says**, **what it wrote**, and **what is actually configured** in its cloud. Every contradiction becomes a sourced finding tied to the NIS2 article, and the case file is sealed with a SHA-256 hash chain that can be verified offline.
The idea comes straight from my day job: in a cyber audit, the risk hides in the gap between policy and reality.

**My part:** development and deployment on Google Cloud
- 4 AI agents orchestrated with **Google ADK** and **Gemini on Vertex AI**
- read-only probes analysing the GCP configuration: IAM, firewall, Cloud Storage, backups, Cloud KMS, log retention
- **FastAPI** backend on **Cloud Run**, infrastructure as code with **Terraform**

### 🏆 [European AI Championship 2026 — team Epi84](https://github.com/BuildRunnerFr/epi84-european-ai-championship-2026)
*Paris, 21–22 Nov 2026 · 3 AI-security challenges · 22 hours · one 4-GPU node · team project*

| Challenge | Public score | My part |
|---|:-:|:-:|
| 🔍 Locate an invisible watermark in images | **0.762** mIoU | ✅ with [@Xelapte](https://github.com/Xelapte) |
| 🧬 Tell which API endpoints serve the same model | **0.85** | teammates |
| 🧹 Make a model *forget* 3,500 images (machine unlearning) | **0.324** | ✅ |

The watermark trick: we used the official watermarking tool to generate our own labelled examples, so we had unlimited ground truth, then trained a segmentation network on it.
Fun fact: this was my **first ever ML competition**.

### ✅ [Attest](https://github.com/BuildRunnerFr/attest) — the DORA compliance auditor that tests instead of reading
*Meta Global AI Developer Hackathon · Nov 2026 · solo project*

An AI agent that audits a bank's systems against DORA: it tests them read-only, seals and masks the evidence, routes fixes for approval, re-tests and writes the report.
Benchmark on 8 fictitious banks: **56/56 checks correct on every run, 0 false findings, prompt injection caught 7/7.**

`Python` `Muse Spark 1.3` `SAM 3.1` `GitHub Actions`

### 💶 [Clair](https://github.com/BuildRunnerFr/clair) — personal finance tracker
Next.js + Supabase (row-level security), bank sync via the TrueLayer API, automatic transaction categorization (rules first, then an LLM).

`Next.js` `TypeScript` `Supabase` `OpenAI`

<details>
<summary><b>More projects</b></summary>
<br/>

- **📡 Line quality monitoring & anomaly detection** (2025) — time-series analysis of ADSL/VDSL2 line metrics, statistical detection of electromagnetic interference patterns, automated alerting. `Python`
- **🎬 Automated video production pipeline** (2026) — end-to-end multi-API automation. `Claude API` `Whisper` `FFmpeg`
- **🛡️ Secure network infrastructure** — segmented architecture with automated attack-simulation playbooks. `Active Directory` `pfSense` `Suricata` `Splunk / Elastic` `Caldera`
- **🐢 Sea turtle conservation tools** (internship, Malaysia, 2026) — a Progressive Web App replacing paper field forms, plus a captive portal collecting island visitor surveys for the research team.

</details>

---

## 🧭 The path so far

| When | Where | What |
|---|---|---|
| 2022–2025 | 🎓 IUT Vélizy | Bachelor's in Networks & Telecoms, cybersecurity major |
| 2024 | 🇧🇬 Technical University of Sofia | Erasmus+ semester |
| 2024–2025 | 📶 Free (Iliad Group) | Apprentice telecom works supervisor: field ops, subcontractor teams, client reporting |
| 2025– | 🎓 IMT Atlantique | Master of Engineering, Computer Science, Networks & Telecoms |
| 2025– | 🏦 Société Générale | Cybersecurity apprentice: Python automation cross-checking access controls across 3 data sources, weekly reporting to ~100 tech leads worldwide, a third-party audit framework shared across European banks |
| 2026 | 🇲🇾 SEATRU, Universiti Malaysia Terengganu | Software engineering intern: sea turtle conservation |

---

## 🛠️ Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20ADK-4285F4?style=flat&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini%20·%20Vertex%20AI-8E75B2?style=flat&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
</p>

**AI & data:** agentic AI (Google ADK, LLM orchestration) · ML (segmentation, machine unlearning) · pandas / NumPy · statistics, probability, signal processing
**Cyber:** compliance (NIS2, DORA) · cloud security · SOC / SIEM (Splunk, Elastic) · IDS (Suricata) · firewalls (pfSense, Stormshield) · Active Directory
**Also:** C · C++ · Java · Bash · Git / GitLab

---

## 🔭 Right now

- 🤖 At work: an **AI agent that answers natural-language questions by cross-referencing internal frameworks**, so people find the right answer in seconds instead of digging through documents.
- 🎧 Next up: the **Deezer hackathon**, Paris, 28–29 Nov.
- ♟️ Trying to get past 1250 Elo. Progress is slower than my GPU jobs.

<p align="center"><i>Into agentic AI, ML or data science? Let's talk, build something, or team up for the next hackathon.</i></p>

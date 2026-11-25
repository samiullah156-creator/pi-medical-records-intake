<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=HIPAA-Aware%20Medical%20Records%20Intake%20for%20PI%20Law%20Firms&fontSize=25&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Secure%20records%20automation&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="HIPAA-Aware Medical Records Intake for PI Law Firms" />

**A secure intake system for personal injury firms that checks consent, encrypts medical records, writes an AI summary and logs every access.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Secure%20records%20automation-9533fa?style=flat-square" alt="Secure records automation" />
  <img src="https://img.shields.io/badge/Python-231f20?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/Encrypted%20storage-231f20?style=flat-square" alt="Encrypted storage" />
  <img src="https://img.shields.io/badge/Claude-231f20?style=flat-square" alt="Claude" />
  <img src="https://img.shields.io/badge/OpenAI-231f20?style=flat-square" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Audit%20logging-231f20?style=flat-square" alt="Audit logging" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![HIPAA-aware PI medical records intake workflow in n8n: consent check, file encryption, encrypted storage, AI summary, audit log and team alert.](assets/cover.webp)

## Overview

Personal injury cases depend on medical records, which must be collected and handled with strict privacy. Lexvaxa built a secure records intake app in Python with HIPAA requirements in mind, orchestrated with n8n. A secure form checks consent and authorization before any file is stored, records are encrypted with restricted access, an AI model summarises treatment, providers and dates for the case team, and every access is written to an audit log. Screens shown use sample data, so no client records are exposed.

## The challenge

Medical records arrived by email and fax, were hard to track and had to be handled under strict privacy rules.

## The solution

A Python and n8n workflow: consent validation, AES-256 encryption, encrypted storage, an AI records summary, role-based access, audit logging and a case team alert.

## Key features

- Secure intake form with consent and authorization check
- Files encrypted at rest with AES-256
- Role-based access to case files
- AI summary of treatment, providers and dates
- Full audit log of every access
- No record content in execution logs
- Case team notified when records are ready

## Results

- Medical records are collected safely and ready for case review sooner

## Tech stack

![Python](https://img.shields.io/badge/Python-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![Encrypted storage](https://img.shields.io/badge/Encrypted%20storage-1d1726?style=for-the-badge) ![Claude](https://img.shields.io/badge/Claude-1d1726?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/OpenAI-1d1726?style=for-the-badge) ![Audit logging](https://img.shields.io/badge/Audit%20logging-1d1726?style=for-the-badge) ![Secure forms](https://img.shields.io/badge/Secure%20forms-1d1726?style=for-the-badge)

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/pi-medical-records-intake

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />

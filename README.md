# Awesome-Chiropractic-Software

## Top Chiropractic Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Chiropractic EHR, Practice Management, SOAP Charting & Billing*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Chiropractic Software**. These tools help chiropractors manage patient records, schedule appointments, document SOAP notes, process insurance claims, and handle billing for cash and insurance-based practices.



**Examples** include ChiroTouch, Jane App, Genesis Chiropractic Software, Platinum System, ClinicMind, EZBIS, Office Ally, PracticeHub, Cliniko, and InTouch EMR (the category leaders).



**Open-source emphasis**: Chiropractic software is a **commercially dominated category** with no production-ready open-source chiropractic-specific EHR/PM platform. The open-source ecosystem provides **local-first patient journals** (ChiroCard), **general clinic management systems** (Imhotep Smart Clinic), and **legacy medical records systems** (OpenClinic). This section documents these focused solutions honestly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ChiroTouch](https://www.chirotouch.com/)**

  Chiropractic EHR and practice management platform trusted by **12,500+ practices**. Features **Rheo AI Scribe** for SOAP notes (saves up to 92% documentation time), integrated billing with claim scrubbing and ERA auto-posting, scheduling with natural language appointment creation, and CT Pay embedded payments . Three tiers: Start, Grow, and Scale.



- **[Jane App](https://jane.app/)**

  Clinic management platform built for chiropractic pace. Features **AI Scribe** for draft chart notes, customizable peer-built charting templates, digital intake with consent forms completed before arrival, billing codes carried over from chart notes, and automated reminders . Supports multi-discipline practices (DCs, LMTs, PTs) under one account.



- **[Genesis Chiropractic Software](https://genesischiropracticsoftware.com/)**

  Cloud-based, ONC-certified chiropractic EHR. Provides SOAP notes, travel cards, X-ray tracking, outcome measurement, and integrated billing/financials . Long-standing vendor with users reporting 15+ years of continuous use.



- **[Platinum System](https://www.platinumsystem.com/)**

  Chiropractic EHR designed for speed and ease of use. Features electronic check-in with health cards, automated arrival lists, one-screen patient EHR (X-rays, SOAP history, spinal levels, future appointments), fast SOAP notes with macros, and one-tap checkout . Doctor-centric and patient-friendly.



- **[ClinicMind](https://www.clinicmind.com/chiropractic)**

  Chiropractic practice software built for growth. Features **AI SOAP notes** that learn provider style, multi-location operations with centralized scheduling and collections visibility, **full-service credentialing** (providers billing in 3-6 weeks), and automated patient engagement . Recognized as G2 Leader for 15 consecutive quarters.



- **[EZBIS](https://ezbis.com/)**

  Chiropractic software since 1980. Provides patient accounting and billing, collection tools, scheduling, EHR, and patient self-check-in . Highly customizable with macros for almost every situation. Features ICD-10 codes, body charts, and dictation.



- **[Office Ally (Practice Mate)](https://www.officeally.com/)**

  Practice management software focused on revenue cycle management, reporting, billing, and streamlined booking . Features claims management, customizable forms, HIPAA compliance, and SMS messaging.



- **[PracticeHub](https://www.practicehub.io/)**

  All-in-one clinic management platform built specifically for chiropractors. Covers scheduling, clinical notes, integrated billing, memberships, patient communications (SMS/email), online bookings, patient app, reporting, and 40+ integrations . 30-day free trial, no contracts. Startup Scheme offers up to 90% off for new clinics.



- **[Cliniko](https://www.cliniko.com/)**

  Streamlined patient management system. User-friendly for appointment bookings, clinical notes, billing, and administration tasks. Easy to learn and teach to new employees .



- **[InTouch EMR](https://intouchemr.com/)**

  Integrated cloud-based EMR and practice management solution. Provides real-time eligibility verification, appointment reminders, customizable note templates, and medical billing . HIPAA compliant and ONC Certified. iPad app for mobile access.



## Open-Source GitHub Projects



### Patient-First Bodywork Journal



- **[ChiroCard](https://github.com/ehukaimedia/chirocard)**

  **Local-first, no-account bodywork passport (PWA).** **Core philosophy**: "Patient is the Database" — all health records, history, and preferences live on the patient's device. No cloud, no accounts, no lock-in . **Features**: Bodywork Passport (carry body history on own device); **Smart Charting** (interactive body map for logging complaints, adjustments, and treatment notes); Session History (permanent local record); Care Team list; Clinic Search (OpenStreetMap-powered); PDF-ready session reports; Calendar export; Journal; **Own Your Data** (export full record to JSON anytime) . **Tech stack**: React 19, TypeScript, Vite 7, Dexie.js (IndexedDB), Capacitor 8 for mobile . **Roadmap**: Practitioner QR handoff for stateless kiosk charting. **MIT License** (per repo context) .



### General Clinic Management Systems



- **[Imhotep Smart Clinic](https://github.com/Imhotep-Tech/imhotep_smart_clinic)**

  **Modern medical clinic management system built with Django and TailwindCSS.** **Features**: Digital medical records, smart appointment scheduling, prescription management, practice analytics, PWA support, Google OAuth . **Tech stack**: Django 4.2+, PostgreSQL 12+ (or SQLite for dev), TailwindCSS 3.0+, Alpine.js, WeasyPrint for PDF generation, Docker deployment . **27 stars, 5 forks**. Can be adapted for chiropractic workflows with custom templates.



- **[OpenClinic (jact)](https://github.com/jact/openclinic)**

  **Easy-to-use open-source medical records system written in PHP.** **39 stars, 65 forks** . **Features**: Medical records management (patient administration, social data, clinic history, problem reports), admin options (config settings, theme editor, staff members, system users, database dumps, log statistics) . **Multilingual**: English, Spanish, Dutch, Traditional Chinese. **GPL License**. Last updated October 2019. Suitable as a foundation for a lightweight chiropractic patient records system.



- **[OpenClinic (llamasearchai)](https://github.com/llamasearchai/OpenClinic)**

  **Advanced healthcare AI clinical decision support platform with OpenAI Agents.** **Features**: Clinical decision support (symptom analysis, drug interactions, guidelines, risk assessment, differential diagnosis), NLP processing (entity extraction, summarization), patient management, privacy/de-identification, FHIR integration . **Tech stack**: Python 3.11+, FastAPI, PostgreSQL, Redis, Next.js/React frontend, Docker . **MIT License**. **Note**: AI-focused CDS platform, not a traditional EHR — can complement a chiropractic practice management system .



### Additional Strong Open-Source Options



- **Patient Journal**: **ChiroCard** (local-first, patient-owned, bodywork passport) .

- **Clinic Management**: **Imhotep Smart Clinic** (Django, modern stack, adaptable) .

- **Medical Records**: **OpenClinic** (PHP, GPL, multilingual, legacy) .

- **Clinical Decision Support**: **OpenClinic (llamasearchai)** (AI agents, FHIR, MIT) .



**Frameworks for building custom systems**: Combine **Imhotep Smart Clinic** as the core clinic management platform, **OpenClinic** for patient record management, and **OpenClinic (llamasearchai)** for AI-powered clinical decision support. For patient-facing charting, **ChiroCard** offers a local-first bodywork passport model. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Chiropractic software handles sensitive patient health data; ensure compliance with HIPAA, PHI protection requirements, and applicable state regulations.

- **Open-source reality**: **No production-ready open-source chiropractic-specific EHR/PM platform exists**. The open-source ecosystem provides **patient-first journals** (ChiroCard, local-first PWA) , **general clinic management systems** (Imhotep Smart Clinic, Django) , **legacy medical records systems** (OpenClinic, PHP/GPL) , and **AI clinical decision support** (OpenClinic llamasearchai) . However, **commercial platforms** (ChiroTouch, Jane App, Genesis, Platinum, ClinicMind) provide **chiropractic-specific SOAP templates, insurance billing workflows, and practice growth tools** that open-source alternatives cannot match without significant customization. The open-source path is most viable for **patient-owned journals, lightweight record systems, or organizations with strong Django/PHP development capacity**.



---



**Made for chiropractors, clinic managers, practice owners, and healthcare developers.**

Let's make chiropractic software more open, transparent, and patient-centered.

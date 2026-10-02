# Mark Alvin Cadangin

### Software Development Technologies · West Visayas State University

I am a 3rd-year BSIT student from Leon, Iloilo, Philippines, majoring in Software Development Technologies. I build full-stack web applications, database architectures, and connected hardware projects to solve operational problems.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Live_Portfolio-markcadangin.me-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white)](https://markcadangin.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mark_Alvin_Cadangin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mark-alvin-cadangin)
[![Email](https://img.shields.io/badge/Email-markcadangin%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:markcadangin@gmail.com)

<br/>

| Field | Detail |
| :--- | :--- |
| **Degree** | 3rd-Year BSIT — Major in Software Development Technologies |
| **University** | West Visayas State University (2024 – Present) |
| **Scholarship** | DOST-SEI Scholar · Batch 2024 (Department of Science and Technology) |
| **Academic Honors** | CICT Parangal Gold Medalist (1st Year) · Silver Medalist (2nd Year) |
| **Location** | Leon, Iloilo, Philippines |
| **Status** | Open to Full-Stack Software Engineering internships & technical collaborations |
| **Portfolio** | [markcadangin.me](https://markcadangin.me) |

</div>

---

## Featured Engineering Projects

### <a href="https://github.com/markalvincadangin/smart-water-pump-controller"><img src="assets/smartflow.png" width="32" height="32" align="absmiddle" alt="SmartFlow logo" /></a> [SmartFlow — Residential IoT Water-Pump Controller](https://github.com/markalvincadangin/smart-water-pump-controller)

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/markalvincadangin/smart-water-pump-controller)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=android&logoColor=white)
![RS-485](https://img.shields.io/badge/RS--485-Wired_Link-4B5563?style=flat-square)
![Firebase](https://img.shields.io/badge/Firebase_RTDB-FFCA28?style=flat-square&logo=firebase&logoColor=black)

> A residential deep-well pump and water-tank automation system designed, built, and installed in Leon, Iloilo to prevent motor dry-run burnouts and eliminate daily manual monitoring. An operating hardware installation at one residential site.

- **Two-Node Wired Architecture**: An ESP32 master at the pump and an ESP8266 node at the elevated 660L tank communicate over a 40-meter CAT6 RS-485 link with CRC validation to eliminate motor electrical noise.
- **Local Firmware Safety Limits**: All critical shutdown logic (15-second dry-run lockout, 45-minute continuous run ceiling, and communication heartbeat loss) runs directly on the ESP32 with an industrial CJX2 contactor and snubber circuits, ensuring safe shutdown even when Wi-Fi is disconnected.
- **Native Android App**: Built with Kotlin and Jetpack Compose for Bluetooth setup, real-time tank level telemetry, manual motor override, and operational history.

---

### <a href="https://github.com/markalvincadangin/CONVERA"><img src="assets/convera.png" width="32" height="32" align="absmiddle" alt="CONVERA logo" /></a> [CONVERA — Research & Project Proposal Validation Platform](https://github.com/markalvincadangin/CONVERA)

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/markalvincadangin/CONVERA)
![Next.js 15](https://img.shields.io/badge/Next.js_15.2-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI_0.115-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python 3.12](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite WAL](https://img.shields.io/badge/SQLite_WAL_38_Tables-003B57?style=flat-square&logo=sqlite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

> A full-stack research engineering tool helping student researchers and developers organize problem interviews, scholarly citations, and technical requirements into structured proposals before writing code.

- **Dual Validation Workflows**: Guides project concepts through two pathways: a 7-phase startup discovery process (Mom Test customer interviews, problem screening, MVP scoping) and an 8-stage academic research framework (literature grounding, gap analysis, DSR artifact formulation).
- **Deterministic Evaluation**: Ranks problem opportunities using explicit mathematical formulas and rubric criteria rather than generative LLM prompts, verified by 338 automated backend tests.
- **Evidence Traceability & Tool Integrations**: Visualizes linkage from research papers and customer interview notes down to concrete software requirements. Exports directly to Notion, Zotero (BibTeX / CSL-JSON), and GitHub Issues.

---

### <a href="https://github.com/markalvincadangin/havenstay"><img src="assets/havenstay.svg" width="32" height="32" align="absmiddle" alt="HavenStay logo" /></a> [HavenStay BHMS — Bed-Level Property Management Platform](https://github.com/markalvincadangin/havenstay)

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/markalvincadangin/havenstay)
[![Live Demo](https://img.shields.io/badge/Demo-havenstay.markcadangin.me-008080?style=flat-square&logo=googlechrome&logoColor=white)](https://havenstay.markcadangin.me)
![Next.js 16](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Laravel 13](https://img.shields.io/badge/Laravel_13-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL 8.4](https://img.shields.io/badge/MySQL_8.4_Primary--Replica-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

> Information Management coursework prototype modeled on student boarding houses near universities, designed around individual bed-space vacancies, shared utility billing, and database-level auditability.

- **Bed-Level Occupancy & Billing**: Tracks individual bed reservations, security deposits, and prorated utility calculations across shared electric and water sub-meters.
- **45 MySQL Database Triggers**: Automatically records before-and-after snapshots directly in the database whenever room assignments or balances mutate, ensuring audit trails cannot be bypassed by application-level bugs.
- **Primary-Replica Topology**: Separates daily transactional writes from monthly billing reports using MySQL 8.4 replication orchestrated with Docker Compose.

---

### <a href="https://github.com/markalvincadangin/laundry-shop-management-system"><img src="assets/faith-laundry.png" width="32" height="32" align="absmiddle" alt="Faith Laundry Shop logo" /></a> [Faith Laundry Shop LMS — Business Management & Order Tracking](https://github.com/markalvincadangin/laundry-shop-management-system)

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/markalvincadangin/laundry-shop-management-system)
[![Live Demo](https://img.shields.io/badge/Demo-laundry.markcadangin.me-0284C7?style=flat-square&logo=googlechrome&logoColor=white)](https://laundry.markcadangin.me)
![Next.js 15](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Spring Boot 3.3](https://img.shields.io/badge/Spring_Boot_3.3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Java 21](https://img.shields.io/badge/Java_21_LTS-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PostgreSQL 16](https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-289_Passed-success?style=flat-square)

> A Systems Analysis and Design capstone based on the daily operations of Faith Laundry Shop in Iloilo, replacing handwritten notebooks with automated intake pricing, live receipt QR tracking, and offline counter resilience.

- **Weight-Based Pricing & Snapshotting**: Computes load counts from intake weight (`⌈weight ÷ 8kg⌉`) and freezes pricing rules at transaction creation so future catalog adjustments never alter historical receipts.
- **Zero-Login Public QR Tracking**: Customers scan the QR code printed on their thermal receipt to inspect live order progress (Received → Washing → Drying → Folding → Ready for Pickup) without downloading an application or creating an account.
- **Offline-First Desktop Deployment**: Packaged with Inno Setup to automatically install PostgreSQL and run the application as a background Windows service on the shop counter PC.
- **289 Automated Tests**: 199 backend tests (JUnit 5 + Testcontainers against PostgreSQL) and 90 frontend unit/component tests (Vitest + React Testing Library).

---

### <a href="https://github.com/markalvincadangin/triagesense"><img src="assets/triagesense.png" width="32" height="32" align="absmiddle" alt="TriageSense logo" /></a> [TriageSense — Emergency Department Intake & Triage Support](https://github.com/markalvincadangin/triagesense)

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/markalvincadangin/triagesense)
[![Interactive Demo](https://img.shields.io/badge/Demo-GitHub_Pages-22C55E?style=flat-square&logo=githubpages&logoColor=white)](https://markalvincadangin.github.io/triagesense/)
![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide_Icons-F56565?style=flat-square)

> An academic prototype for CIT 213 (Human-Computer Interaction 2), modeled on clinical intake workflows at West Visayas State University Medical Center (WVSUMC) to reduce emergency room intake delays.

- **Dual-Viewport Architecture**: Built two purpose-designed interfaces: a 5-step self-service kiosk with regional dialect support, an anatomical symptom body map, and numeric pain rating for walk-in patients, paired with a widescreen workstation for triage nurses.
- **Nurse-Controlled ESI Assessment**: Staff workstation featuring a live intake queue, nurse-controlled Emergency Severity Index (ESI) scoring, and simulated vitals telemetry (pulse, SpO2).
- **Human-Factors Design**: Tailored high-contrast touch targets and translated dialect cues to accommodate varying patient literacy levels in emergency situations.

---

## Technical Competencies

<div align="center">

<img src="https://skillicons.dev/icons?i=kotlin,py,ts,js,java,cpp,php&perline=7" alt="Languages" />
<br/>
<sub><b>Core Languages</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=nextjs,react,vite,tailwind,html,css&perline=6" alt="Frontend" />
<br/>
<sub><b>Frontend Architecture</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=spring,laravel,fastapi,nodejs&perline=4" alt="Backend" />
<br/>
<sub><b>Backend Frameworks & APIs</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=mysql,postgresql,sqlite,firebase,docker&perline=5" alt="Database & DevOps" />
<br/>
<sub><b>Database Engines & Containerization</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=arduino,linux,git,github,postman,figma&perline=6" alt="Hardware & Tooling" />
<br/>
<sub><b>Hardware, Platforms & Tooling</b></sub>

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=markalvincadangin&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=markalvincadangin&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## Contact & Profiles

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markcadangin.me-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white)](https://markcadangin.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mark_Alvin_Cadangin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mark-alvin-cadangin)
[![Email](https://img.shields.io/badge/Email-markcadangin%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:markcadangin@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-markalvincadangin-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/markalvincadangin)

</div>

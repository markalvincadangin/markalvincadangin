# Mark Alvin Cadangin
### Software Development Technologies · West Visayas State University

I am a 3rd-year BSIT student from Leon, Iloilo, Philippines, majoring in Software Development Technologies. I build full-stack web applications and connected hardware projects to solve everyday operational problems.

<div align="center">

| **Degree** | 3rd-Year BSIT — Major in Software Development Technologies |
|:---|:---|
| **University** | West Visayas State University (2024 – Present) |
| **Scholarship** | DOST-SEI Scholar · Batch 2024 (Department of Science and Technology) |
| **Academic Honors** | CICT Parangal Gold Medalist (1st Year) · Silver Medalist (2nd Year) |
| **Location** | Leon, Iloilo, Philippines |
| **Currently** | Open to Full-Stack Software Engineering internships & collaborations |
| **Email** | markcadangin@gmail.com |

</div>

---

## Featured Projects

### <a href="https://github.com/markalvincadangin/smart-water-pump-controller"><img src="assets/smartflow.png" width="34" height="34" align="absmiddle" alt="SmartFlow logo" /></a> [SmartFlow — Residential IoT Water-Pump Controller](https://github.com/markalvincadangin/smart-water-pump-controller)

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_RTDB-FFCA28?style=flat-square&logo=firebase&logoColor=black)

> A residential deep-well pump and water-tank controller I designed, built, and installed in Leon, Iloilo to prevent motor burnouts and eliminate daily manual monitoring. It is an operating prototype at one residential site, not a commercial product.

- **Two-node wired architecture** — An ESP32 master at the pump and an ESP8266 node at the elevated 660L tank communicate over a 40-meter CAT6 RS-485 link with CRC validation to eliminate motor electrical interference.
- **Local firmware safety limits** — All critical shutdown logic (15-second dry-run lockout, 45-minute continuous run ceiling, and communication heartbeat loss) runs directly on the ESP32 with an industrial CJX2 contactor, ensuring the pump shuts down safely even if Wi-Fi drops.
- **Native Android app** — Built with Kotlin and Jetpack Compose for Bluetooth setup, real-time tank level monitoring, manual override, and telemetry history.

---

### <a href="https://github.com/markalvincadangin/CONVERA"><img src="assets/convera.png" width="34" height="34" align="absmiddle" alt="CONVERA logo" /></a> [CONVERA — Research & Project Proposal Validation Platform](https://github.com/markalvincadangin/CONVERA)

[Repository](https://github.com/markalvincadangin/CONVERA)

![Next.js 15](https://img.shields.io/badge/Next.js_15.2-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI_0.115-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python 3.12](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite WAL](https://img.shields.io/badge/SQLite_WAL_38_Tables-003B57?style=flat-square&logo=sqlite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

> An ongoing personal project that helps student developers and researchers organize problem interviews, scholarly citations, and requirements into structured proposals before writing code.

- **Dual validation workflows** — Guides project ideas through two structured paths: a 7-phase process for startups (problem screening, Mom Test customer interviews, MVP scope check) and an 8-stage process for academic computing research (literature grounding, gap analysis, DSR artifact formulation).
- **Interactive evidence graph** — Visualizes traceability from research papers and customer interview notes down to concrete software requirements.
- **Tool integrations** — Exports validated proposals and citations directly to Notion, Zotero (BibTeX and CSL-JSON), and GitHub Issues.
- **Deterministic scoring** — Ranks problem opportunities using explicit mathematical formulas and rubric criteria rather than unpredictable LLM prompts, backed by 338 automated backend tests.

---

### <a href="https://github.com/markalvincadangin/havenstay"><img src="assets/havenstay.svg" width="34" height="34" align="absmiddle" alt="HavenStay logo" /></a> [HavenStay BHMS — Bed-Level Property Management Platform](https://github.com/markalvincadangin/havenstay)

[Repository](https://github.com/markalvincadangin/havenstay) · [Live demo](https://havenstay-theta.vercel.app)

![Next.js 16](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Laravel 13](https://img.shields.io/badge/Laravel_13-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL 8.4](https://img.shields.io/badge/MySQL_8.4_Primary--Replica-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

> A coursework prototype for boarding houses near universities, designed around individual bed-space vacancies, shared utility billing, and database-level auditability.

- **Bed-level occupancy and billing** — Tracks individual bed reservations, security deposits, and prorated utility calculations across shared electric and water sub-meters.
- **45 MySQL audit triggers** — Automatically log before-and-after snapshots directly in the database whenever room assignments or balances change, so audit logs cannot be bypassed by application bugs.
- **Primary-replica database setup** — Separates daily transactional writes from monthly billing reports using MySQL 8.4 replication orchestrated with Docker Compose.

---

### <a href="https://github.com/markalvincadangin/laundry-shop-management-system"><img src="assets/faith-laundry.png" width="34" height="34" align="absmiddle" alt="Faith Laundry Shop logo" /></a> [Faith Laundry Shop — Management System Prototype](https://github.com/markalvincadangin/laundry-shop-management-system)

[Repository](https://github.com/markalvincadangin/laundry-shop-management-system) · [Live demo](https://laundry-shop-management-system.vercel.app)

![Next.js 15](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Spring Boot 3.5](https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

> A coursework capstone based on the daily operations of Faith Laundry Shop in Iloilo, replacing handwritten logbooks with order intake automation and live customer tracking.

- **Weight-based pricing with price snapshots** — Automatically calculates order totals by weight and service tier, saving fixed pricing snapshots at order creation so future rate updates never alter historical receipts.
- **QR receipt customer tracking** — Customers scan the QR code printed on their thermal paper receipt to check their laundry status on a public web page with zero login required.
- **Offline-first Windows installer** — Uses Inno Setup to automatically install PostgreSQL and run the application as a background Windows service on the shop counter PC.

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=kotlin,py,ts,js,java,cpp,php&perline=7" />
<br/>
<sub><b>Languages</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,html,css&perline=5" />
<br/>
<sub><b>Frontend</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=fastapi,spring,laravel,nodejs&perline=4" />
<br/>
<sub><b>Backend</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=mysql,postgresql,firebase,docker&perline=4" />
<br/>
<sub><b>Database & DevOps</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=arduino,linux,git,github,postman,figma&perline=6" />
<br/>
<sub><b>Tools & Platforms</b></sub>

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=markalvincadangin&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=markalvincadangin&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-markcadangin%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:markcadangin@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mark_Alvin_Cadangin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mark-alvin-cadangin)

</div>

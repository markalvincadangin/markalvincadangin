<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Mark%20Alvin%20Cadangin&fontSize=48&fontColor=fff&animation=twinkling&fontAlignY=36&desc=BSIT%20Student%20Developer%20%7C%20Full-Stack%20and%20IoT&descSize=18&descAlignY=58&descAlign=50" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&random=false&width=650&lines=Building+full-stack+and+IoT+projects;Kotlin+%7C+Next.js+%7C+Laravel+%7C+Spring+Boot;Currently+learning+Python%2C+AI%2C+and+ML" alt="Typing SVG" />

</div>

---

<div align="center">

| **Degree** | 3rd-Year BSIT — Major in Software Technology |
|:---|:---|
| **University** | West Visayas State University |
| **Scholarship** | DOST-SEI Scholar · Batch 2024 |
| **Currently** | Learning Python, AI, and ML · Open to internships & freelance collaborations |
| **Email** | markcadangin@gmail.com |

</div>

---

## Featured Projects

### <a href="https://github.com/markalvincadangin/smart-water-pump-controller"><img src="https://raw.githubusercontent.com/markalvincadangin/smart-water-pump-controller/main/app/src/main/res/drawable/app_logo.png" width="34" height="34" align="absmiddle" alt="SmartFlow logo" /></a> [SmartFlow — Field-Deployed IoT Water-Pump Controller](https://github.com/markalvincadangin/smart-water-pump-controller)

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_RTDB-FFCA28?style=flat-square&logo=firebase&logoColor=black)

> A field-deployed residential deep-well pump and water-tank controller I designed, built, and installed in Iloilo, Philippines. It is an operating prototype, not a commercially certified controller.

- **Two-node controller** — An ESP32 master and ESP8266 tank node exchange framed telemetry over an approximately 40 m RS-485 link with CRC validation and freshness checks.
- **Local safety gates** — Hardware protection, firmware lockouts, dry-run detection, emergency stop, and maximum-runtime controls keep shutdown decisions local when cloud connectivity is unavailable.
- **Native Android client** — Kotlin and Jetpack Compose provide BLE provisioning, real-time telemetry, AUTO/MANUAL/COUNTDOWN control, diagnostics, and activity history through Firebase services.

---

### <a href="https://github.com/markalvincadangin/havenstay"><img src="https://raw.githubusercontent.com/markalvincadangin/havenstay/master/frontend/public/logo.svg" width="34" height="34" align="absmiddle" alt="HavenStay logo" /></a> [HavenStay BHMS — Bed-Level Property Management Platform](https://github.com/markalvincadangin/havenstay)

![Next.js 16](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Laravel 13](https://img.shields.io/badge/Laravel_13-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL 8.4](https://img.shields.io/badge/MySQL_8.4_Primary--Replica-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

> A personal coursework prototype for boarding houses and shared residences, designed around bed-level occupancy, contract lifecycles, metered utilities, and database-level auditability.

- **Bed-level occupancy engine** — Atomic reservation states and prorated utility rollover calculation across shared meter configurations.
- **45 forensic database triggers** — Tamper-resistant, immutable before/after JSON state diffs that run independently of application code — zero-trust at the database layer.
- **Read/write database topology** — MySQL 8.4 primary-replica replication, idempotency protection for mutations, and Docker Compose-based local orchestration.

---

### <a href="https://github.com/markalvincadangin/laundry-shop-management-system"><img src="https://raw.githubusercontent.com/markalvincadangin/laundry-shop-management-system/main/frontend/public/assets/app-icon/app-icon.png" width="34" height="34" align="absmiddle" alt="Faith Laundry Shop logo" /></a> [Faith Laundry Shop — Laundry Management System Prototype](https://github.com/markalvincadangin/laundry-shop-management-system)

![Next.js 15](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Spring Boot 3.5](https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

> A personal coursework prototype that models a real laundry workflow with order automation, reporting, and customer-facing tracking.

- **Custom dynamic pricing engine** — Computes laundry loads by weight, applies configurable service rates, and price-snapshots each order at creation for historical integrity.
- **QR-code customer portal** — Customers scan the QR on their thermal receipt and see live order status on a public Vercel portal. No login required.
- **Offline-first Windows installer** — Inno Setup provisions PostgreSQL, configures a WinSW background service, and writes application configuration without requiring developer tools on the target machine.

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=kotlin,ts,js,java,php,cpp&perline=6" />
<br/>
<sub><b>Languages</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,html,css&perline=5" />
<br/>
<sub><b>Frontend</b></sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=spring,laravel,nodejs&perline=3" />
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

## GitHub Activity

<div align="center">

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=markalvincadangin&theme=tokyo-night&hide_border=true&area=true" alt="GitHub contribution activity graph" />

</div>

---

## Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-markcadangin%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:markcadangin@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mark_Alvin_Cadangin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mark-alvin-cadangin)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />

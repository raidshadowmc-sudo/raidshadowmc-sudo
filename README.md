diff --git a/README.md b/README.md
index e61f108f1441879f13d8dd27aea35101fb7ca498..40e9d8bdf4df8cc7f6a71a2fd671f27dd41d2b3a 100644
--- a/README.md
+++ b/README.md
@@ -1,112 +1,117 @@
 <div align="center">
 
-<img src="https://capsule-render.vercel.app/api?type=waving&color=0A0A0A&height=110&section=header"/>
+<img src="https://capsule-render.vercel.app/api?type=waving&color=0A0A0A&height=120&section=header&text=ASTERION&fontColor=C9A84C&fontSize=38&animation=fadeIn" />
 
 # ASTERION
-### discord automation architecture
+### Discord Automation Architecture
 
-<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=15&pause=2000&color=C9A84C&center=true&vCenter=true&width=600&lines=%3E+booting+ASTERION+core...;%3E+loading+modules...;%3E+system+status:+nominal." />
+<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=15&pause=2000&color=C9A84C&center=true&vCenter=true&width=680&lines=%3E+initializing+asterion+core...;%3E+loading+economy+and+event+modules...;%3E+monitoring+status%3A+nominal+%E2%9C%93" />
 
 <br>
 
 <img src="https://img.shields.io/badge/STATUS-LIVE-C9A84C?style=for-the-badge&labelColor=0A0A0A"/>
-<img src="https://img.shields.io/badge/ARCHITECT-lisonly.dia-C9A84C?style=for-the-badge&labelColor=0A0A0A"/>
-<img src="https://img.shields.io/badge/SYSTEM-ASTERION-C9A84C?style=for-the-badge&labelColor=0A0A0A"/>
+<img src="https://img.shields.io/badge/RUNTIME-Python-C9A84C?style=for-the-badge&labelColor=0A0A0A"/>
+<img src="https://img.shields.io/badge/PLATFORM-Discord_API-C9A84C?style=for-the-badge&labelColor=0A0A0A"/>
 
 <br><br>
 
-<img src="https://media.tenor.com/BvRa4cJxJXcAAAAi/anime-computer.gif" width="90"/>
+> **ASTERION** — модульная система автоматизации Discord‑сообществ: экономика, ивенты, партнерства и наблюдение за активностью в одной архитектуре.
 
 </div>
 
 ---
 
-# ▣ SYSTEM STACK
+## ✦ Почему ASTERION
 
-<div align="center">
-
-<img src="https://skillicons.dev/icons?i=py,sqlite,html,css,js,discord,oracle,linux&theme=dark"/>
-
-</div>
+- ⚙️ **Модульная структура** — каждый блок отвечает за отдельный домен.
+- 📡 **Наблюдаемость** — логирование действий и телеметрия состояния.
+- 🧩 **Расширяемость** — легко добавлять новые сценарии автоматизации.
+- ☁️ **Инфраструктурная готовность** — изначально спроектирован под облачное размещение.
 
 ---
 
-# ▣ ASTERION ARCHITECTURE
+## ✦ Технологический стек
 
 <div align="center">
+  <img src="https://skillicons.dev/icons?i=py,sqlite,html,css,js,linux&theme=dark"/>
+</div>
 
+<div align="center">
 
-┌───────────────────────────────────────────────┐
-│ ASTERION CORE │
-├───────────────────────────────────────────────┤
-│ Economy System │ Currency · Loot │
-│ Event Engine │ Dynamic server events │
-│ Partner Manager │ Access control │
-│ Activity Monitor │ Logging & telemetry │
-├───────────────────────────────────────────────┤
-│ Runtime: Python │
-│ Storage: SQLite │
-│ Platform: Discord API │
-│ Infrastructure: Oracle Cloud │
-└───────────────────────────────────────────────┘
-
+| Layer | Stack |
+|---|---|
+| Core Runtime | **Python** |
+| Data Storage | **SQLite** |
+| Integration | **Discord API** |
+| Infrastructure | **Oracle Cloud / Linux** |
 
 </div>
 
 ---
 
-# ▣ ACTIVE MODULES
+## ✦ Архитектура системы
+
+```text
+┌────────────────────────────────────────────────────────────┐
+│                        ASTERION CORE                       │
+├────────────────────────────────────────────────────────────┤
+│ AsterionEconomy  → currency, loot, trading                │
+│ AsterionEvents   → dynamic server events                  │
+│ AsterionPartners → partnership access control             │
+│ AsterionMonitor  → logs, analytics, activity tracking     │
+├────────────────────────────────────────────────────────────┤
+│ Runtime: Python · Storage: SQLite · Platform: Discord API │
+└────────────────────────────────────────────────────────────┘
+```
+
+---
+
+## ✦ Активные модули
 
 <div align="center">
 
-| MODULE | FUNCTION | STATUS |
-|------|------|------|
-| **AsterionEconomy** | Currency · Loot · Trading | 🟢 ONLINE |
-| **AsterionEvents** | Dynamic server events | 🟢 ONLINE |
-| **AsterionPartners** | Partnership access control | 🟢 ONLINE |
-| **AsterionMonitor** | Logs · Activity tracking | 🟢 ONLINE |
+| Module | Назначение | Status |
+|---|---|---|
+| **AsterionEconomy** | Валюта, награды, трейд | 🟢 ONLINE |
+| **AsterionEvents** | Динамические ивенты сервера | 🟢 ONLINE |
+| **AsterionPartners** | Управление партнерским доступом | 🟢 ONLINE |
+| **AsterionMonitor** | Логи, метрики, активность | 🟢 ONLINE |
 
 </div>
 
 ---
 
-# ▣ SYSTEM TELEMETRY
+## ✦ System telemetry
 
 <div align="center">
-
-<img src="https://github-readme-stats.vercel.app/api?username=raidshadowmc-sudo&show_icons=true&hide_border=true&bg_color=0A0A0A&title_color=C9A84C&text_color=AAAAAA&icon_color=C9A84C&theme=dark" width="48%" />
-
-<img src="https://github-readme-streak-stats.herokuapp.com/?user=raidshadowmc-sudo&hide_border=true&background=0A0A0A&fire=C9A84C&ring=C9A84C&currStreakLabel=C9A84C&sideLabels=AAAAAA&dates=555555&sideNums=FFFFFF" width="48%" />
-
+  <img src="https://github-readme-stats.vercel.app/api?username=raidshadowmc-sudo&show_icons=true&hide_border=true&bg_color=0A0A0A&title_color=C9A84C&text_color=AAAAAA&icon_color=C9A84C&theme=dark" width="48%" />
+  <img src="https://github-readme-streak-stats.herokuapp.com/?user=raidshadowmc-sudo&hide_border=true&background=0A0A0A&fire=C9A84C&ring=C9A84C&currStreakLabel=C9A84C&sideLabels=AAAAAA&dates=555555&sideNums=FFFFFF" width="48%" />
 </div>
 
 ---
 
-# ▣ NETWORK ACCESS
+## ✦ Network access
 
 <div align="center">
 
 <a href="https://discord.com/users/lisonly.dia.">
-<img src="https://img.shields.io/badge/Discord-lisonly.dia-C9A84C?style=for-the-badge&logo=discord&logoColor=white&labelColor=0A0A0A"/>
+  <img src="https://img.shields.io/badge/Discord-lisonly.dia-C9A84C?style=for-the-badge&logo=discord&logoColor=white&labelColor=0A0A0A"/>
 </a>
 
 <a href="https://asteriondoc.netlify.app/">
-<img src="https://img.shields.io/badge/Docs-Asterion-C9A84C?style=for-the-badge&logo=netlify&logoColor=white&labelColor=0A0A0A"/>
+  <img src="https://img.shields.io/badge/Docs-Asterion-C9A84C?style=for-the-badge&logo=netlify&logoColor=white&labelColor=0A0A0A"/>
 </a>
 
 </div>
 
 ---
 
 <div align="center">
 
+### ASTERION SYSTEM // READY
 
-ASTERION SYSTEM
-discord automation framework
-
-system ready
-
+*Design for scale. Automate with precision. Keep communities alive.*
 
-<img src="https://capsule-render.vercel.app/api?type=waving&color=0A0A0A&height=110&section=footer"/>
+<img src="https://capsule-render.vercel.app/api?type=waving&color=0A0A0A&height=120&section=footer" />
 
 </div>

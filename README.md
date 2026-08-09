# Hi, I’m Samuel Ngiri 👋  `@ngir0003`

Information Technology graduate and hands-on builder. I design, build and run my own software and production infrastructure end-to-end — **Rust** systems, **Python** data & ML pipelines, security tooling, and the occasional game. I reach for **Rust** by preference: its memory and concurrency guarantees kill whole classes of bugs at compile time, it’s fast on modest hardware, and one codebase ships native binaries across platforms.

## 👀 What I do
- 🦀 **Systems in Rust** — Axum/Tokio services, single-binary deploys, `systemd`.
- 🐍 **Python** — data engineering, ETL pipelines, web scraping, machine learning.
- 🔐 **Cybersecurity** — applied vulnerability analysis, TLS, Argon2id, TOTP/2FA, hardening (HSTS/CSP, path-traversal/LFI, SPF/DKIM/DMARC).
- 🖥️ **Self-hosting & Linux** — reverse proxies, mail, encrypted VPN mesh, RAID, backups.
- 🎮 **Game dev** — Unity / C#.

## 🛠️ Tech stack

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

![Axum](https://img.shields.io/badge/Axum-000000?style=for-the-badge&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-463C57?style=for-the-badge&logo=rust&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)

**Also:** probabilistic ML, ETL & data engineering, database modelling, CAT6A networking, virtualisation & Docker Compose.

## 🚀 Projects

**Public**
| Project | About |
|---------|-------|
| 🔓 [**Heartbleed_Demo**](https://github.com/ngir0003/Heartbleed_Demo) | Interactive **CVE-2014-0160** teaching lab — 3 Docker containers (Flask app behind stunnel/OpenSSL 1.0.1f, attacker console leaking memory & session cookies, explainer dashboard). x86-64 & ARM64. |
| 📈 [**solana-trader**](https://github.com/ngir0003/solana-trader) | Python framework for the **Jupiter v6** DEX aggregator — RPC management, retry/backoff, env-based config. |
| 🕸️ [**webScraping**](https://github.com/ngir0003/webScraping) + [**telegram_bot**](https://github.com/ngir0003/telegram_bot) | Modular Python pipeline: scrape dynamic sites → normalise into SQLite → download assets, with structured logging; a companion Telegram bot publishes formatted updates. |
| 🎮 [**Terranean Assault**](https://github.com/MightyAttacker/Terranean-Assault) | Team-built **Unity/C#** game — gameplay programming, mechanics, iterative playtesting. |
| 🪙 [**monero-playground**](https://github.com/ngir0003/monero-playground) | Experiments with `monero-wallet-rpc` for building Monero apps. |

**Self-hosted Rust infrastructure** *(personal, ~40k LOC across four services)*
- **High-throughput content archive** (Axum/Tokio, ~22k LOC) — layered compression pipeline hitting **90.1% reduction** (3.2 TB → 325 GB, 8.5M objects), 20.1M-record SQLite via `sqlx`, adaptive worker pool, 30-language neural machine translation (CTranslate2/NLLB).
- **Transaction & settlement system** (Axum, ~11k LOC) — 2FA partner-API login, ledger reconciliation, RBAC + audit log, delivered as a PWA.
- **Video ingest → HLS streaming** (Axum + FFmpeg) — unattended capture → multi-bitrate HLS ladder, WebSocket live state, JWT + TOTP admin.
- **Single-binary ops dashboard** + **scheduled host-maintenance daemon** (Rust, `systemd`, embedded assets, HTTP Digest auth).

## 🌱 Currently learning
- **TryHackMe** — Cyber Security 101 path (Linux fundamentals, offensive/defensive intros).
- **Hack The Box Academy** — 10 modules (Linux, networking, web requests, Windows).
- **OverTheWire Bandit** — completed. Continuing to deepen Rust and systems programming.

## 💞 Open to collaborating on
Web scraping & data pipelines • system automation (Python / Bash / Rust) • virtual machine & low-level system simulation • distributed systems • security tooling.

## 📫 Reach me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samuel-ngiri-2278672aa/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:samuelngiri9@gmail.com)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=ngir0003&show_icons=true&count_private=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ngir0003&layout=compact&hide_border=true&langs_count=8)

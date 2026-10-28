# Hi, I'm Sebastián Dinator 👋

**Full-stack & cybersecurity engineer** building useful, secure software.

[![Website](https://img.shields.io/badge/sebadinator.com-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://sebadinator.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sebadinator/)
[![Email](https://img.shields.io/badge/seba@sebadinator.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:seba@sebadinator.com)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/sevd41)

📍 Santiago, Chile · 🗣️ Spanish (native), English (C2) · He/Him

---

## About me

I'm a Computer Science Engineer with a Master of Science in Engineering (IT) from Universidad Adolfo Ibáñez. I work across full-stack development and cybersecurity, and I like each one to make the other better: I build products with a security-first mindset, and I build the tools used to teach security.

- 💼 **Currently:** Full-Stack Development Engineer at **[Klap](https://www.klap.cl)**, building financial services and back office with Java, Spring Boot and Angular.
- 🗓️ **Side project:** designed, built and shipped **[SyncDisp](https://syncdisp.com)** end to end, a free group-scheduling app running entirely on Cloudflare's free plan.
- 🛡️ **Security:** founded the Cybersecurity Lab at UAI Viña del Mar, wrote labs and CTF challenges for the IT Security courses, and took **2nd place at Hack.Ing CTF 2024**.
- 🌱 Always learning something. If you have a project or an interesting problem, let's talk.

---

## Featured work

### 🗓️ [SyncDisp](https://syncdisp.com) — find the day everyone can make

A free web app for groups to agree on dates. Someone creates an event, shares the link, and everyone marks *Can*, *Maybe* or *Can't*. A heat map shows the best day and who can't make it. No sign-up required.

- **Stack:** TypeScript, React 19, Tailwind, Hono, Cloudflare Workers and D1. A single Worker serves the app and the API, all within the free plan.
- **Privacy by design:** credential links keep their key in the URL fragment (never reaches logs); only SHA-256 hashes are stored.
- **Optional accounts:** passkeys (WebAuthn) or Google via OAuth 2.0 with state + PKCE; sensitive actions require a recent session.
- **Hardened:** Turnstile, per-IP rate limits, strict CSP with no inline scripts, HMAC-signed challenges, and anti-spoofing for look-alike names.
- **Tested:** Vitest inside the Workers runtime and Playwright across six viewports (320 px → 1920 px) with a real passkey. Spanish and English, with dark mode.

### 🧪 [LabCentral](https://github.com/Seva41/LabCentral) — security course platform

`Flask` · `Next.js` · `Tailwind` · `Docker`

A launcher for labs and CTF challenges used in UAI's security courses. Each exercise runs in its own isolated container per student, with team work, quizzes, scoring, admin tools and proxy routing, orchestrated with Docker Compose.

### 🚩 CTF challenges for UAI's IT Security course

| Challenge | Topics |
|-----------|--------|
| [CTF_SSH](https://github.com/Seva41/CTF_SSH) | SSH, sniffing, code execution, firewall (iptables) |
| [CTF_Injection](https://github.com/Seva41/CTF_Injection) | SQL injection, XSS, cryptography, session-cookie hijacking |
| [CTF_Cards](https://github.com/Seva41/CTF_Cards) | SQL injection, XSS, hashing and ciphers |
| [CTF_UAI_2025](https://github.com/Seva41/CTF_UAI_2025) | Challenges for the UAI 2025 CTF Hackathon (Viña del Mar) |

### 🌍 Open source contributions

- **[YouTube No Translation](https://github.com/YouG-o/YouTube-No-Translation/pulls?q=is%3Apr+author%3ASeva41+is%3Amerged)** (1.2k+ ⭐): four merged contributions, including Safari support, the Xcode project and the Spanish translation.
- **[Pi-hole](https://github.com/pi-hole/pi-hole/pull/5806)**: clearer error message when a blocklist uses an invalid protocol.

---

## Tech stack

| Area | Technologies |
|------|--------------|
| **Languages** | TypeScript, JavaScript, Java, Python, C, C++, Bash, SQL, R |
| **Frontend** | React, Next.js, Angular, Tailwind CSS |
| **Backend** | Spring Boot, Node.js, Hono, Flask, Django |
| **Cloud & infra** | Cloudflare (Workers, D1, Turnstile), AWS (Lambda, S3, Aurora, ECS), Docker, GitHub Actions, Linux |
| **Databases** | PostgreSQL, MySQL, SQLite, MongoDB |
| **Identity** | Passkeys (WebAuthn), OAuth 2.0 + PKCE, signed sessions and challenges |
| **Security** | Pentesting, vulnerability analysis, secure development, DevSecOps · Metasploit, Burp Suite, Nmap, Wireshark |
| **Testing** | Vitest, Playwright |

---

## Experience

| Role | Organization | Period |
|------|--------------|--------|
| Full-Stack Development Engineer | Klap | Jun 2025 – present |
| Creator | SyncDisp (own project) | 2026 |
| Frontend Developer | Aware.Tools | Apr – May 2025 |
| Full-Stack Developer | Faculty of Engineering and Sciences, UAI | Feb – Apr 2025 |
| Student Ambassador | CENIA (National Center for Artificial Intelligence) | Aug 2024 – Jan 2025 |
| Founder & Manager | UAI Cybersecurity Lab | May – Nov 2024 |
| Teaching Assistant | Universidad Adolfo Ibáñez | 2022 – 2025 |

<details>
<summary>Details</summary>

- **Klap:** financial services and back office with Java, Spring Boot and Angular.
- **Aware.Tools:** responsive interfaces with React, Python and .NET in a Scrum team; research support on Fondecyt/FONDEF projects.
- **UAI, Faculty of Engineering:** internal web apps for the cybersecurity courses with Flask, Next.js, SQLite and Docker.
- **CENIA:** outreach, events and work with researchers at Chile's National Center for Artificial Intelligence.
- **UAI Cybersecurity Lab:** set up the lab at the Viña del Mar campus, offering research and training for undergraduate, master's and PhD students.
- **Teaching Assistant:** IT Security, Advanced Networks, Programming, Data Network Security, and OS & Database Security (undergraduate and master's).
- **UAI Bioengineering (2019 – 2022):** remote communication systems and real-time climate databases with Universidad Austral de Chile and ONEMI; GIS work with Chilean census data.

</details>

---

## Education & certifications

- 🎓 **M.Sc. in Engineering, Information Technologies** — Universidad Adolfo Ibáñez
- 🎓 **Computer Science Engineer** — Universidad Adolfo Ibáñez
- 📜 EF SET English, C2 · IBM Z Xplore (Concepts, Advanced) · RESTful APIs with Java and Spring Boot (Udemy)

## Recognition

- 🥈 **2nd place, Hack.Ing CTF 2024**, Latin America's largest university cybersecurity competition, organized by Security UC at Pontificia Universidad Católica de Chile.

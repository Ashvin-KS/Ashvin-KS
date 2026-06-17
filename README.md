```
╔═══════════════════════════════════════════════════════════════════════════════════════════════════════╗
║                                                                                                       ║
║     █████╗  ██████╗██╗  ██╗██╗   ██╗██╗███╗   ██╗    ██████╗ ███████╗                                 ║
║    ██╔══██╗██╔════╝██║  ██║██║   ██║██║████╗  ██║    ██╔══██╗██╔════╝                                 ║
║    ███████║███████╗███████║██║   ██║██║██╔██╗ ██║    ██████╔╝███████╗                                 ║
║    ██╔══██║╚════██║██╔══██║╚██╗ ██╔╝██║██║╚██╗██║    ██╔══██╗╚════██║                                 ║
║    ██║  ██║███████║██║  ██║ ╚████╔╝ ██║██║ ╚████║    ██║  ██║███████║                                 ║
║    ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝  ╚═══╝  ╚═╝╚═╝  ╚═══╝    ╚═╝  ╚═╝╚══════╝                                 ║
║                                                                                                       ║
║    [System] Booting AshvinOS v3.5.2-LTS...                                                            ║
║    [System] Initializing microkernels... [ OK ]                                                       ║
║    [System] Mounting local-first workspace... [ OK ]                                                  ║
║    [System] Establishing secure terminal session... [ OK ]                                            ║
║                                                                                                       ║
╚═══════════════════════════════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![Portfolio](https://img.shields.io/badge/→_portfolio-ashvin--ks.github.io-58a6ff?style=flat-square&labelColor=0d1117)](https://ashvin-ks.github.io/portfolio/)&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/→_email-ashvinksg@gmail.com-58a6ff?style=flat-square&labelColor=0d1117)](mailto:ashvinksg@gmail.com)&nbsp;&nbsp;
[![Repos](https://img.shields.io/badge/→_repos-51_repositories-58a6ff?style=flat-square&labelColor=0d1117)](https://github.com/Ashvin-KS?tab=repositories)

<br/>

`B.Tech CS @ VIT Chennai` · `CGPA 9.38` · `Open to internships 2026`

</div>

---

### `> tmux attach-session -t ashvin-terminal`

<table>
<tr>
<td width="50%" valign="top">

```yaml
# ╭──────────────────────────────────────────╮
# │  PANEL 0: SYSTEM METRICS                 │
# ╰──────────────────────────────────────────╯
$ status-monitor --live

[HOST]      VIT-Chennai-Node-4
[KERNEL]    Ashvin-LTS-x86_64
[SHELL]     zsh (Tauri-integrated)
[UPTIME]    19 years, 2 followers

[RESOURCE ALLOCATION]
CPU ░░░░░░░░░░░░░░░░░░░░░░ [9.38/10.0 CGPA]
RAM ██████████████████░░░░ [88% Full-Stack]
GPU ██████████████████████ [NVIDIA NIM & CUDA]

[RUNNING TASKS]
● dsc-daemon.service      [ RUNNING ] (Flagship)
● checkora-engine.elf     [ STANDBY ] (Chess AI)
● gsoc-org-finder.bin     [ STABLE  ] (GSoC 2026)
● intent-flow-rust.bin    [ ACTIVE  ] (Starred)
● enterprise-rag.service  [ STANDBY ] (FastAPI)
● slop-guardian-app.sys   [ IDLE    ] (GitHub App)
```

</td>
<td width="50%" valign="top">

```toml
# ╭──────────────────────────────────────────╮
# │  PANEL 1: TECH_STACK.TOML                │
# ╰──────────────────────────────────────────╯
$ cat ~/.config/environment.toml

[languages]
active = ["TypeScript", "Rust", "Python", "C++"]
legacy = ["Dart", "JavaScript"]

[frontend]
core    = "React"
shell   = "Tauri (Local-First Desktop)"
bundler = "Vite"
style   = "Tailwind CSS"

[backend]
stack     = ["Node.js", "FastAPI", "Django", "Flask"]
datastore = ["PostgreSQL", "Redis"]

[ai_ml]
acceleration = ["CUDA", "PyTorch"]
inference    = "NVIDIA NIM"
libraries    = ["HuggingFace", "OpenCV"]

[ops]
runtime = ["Docker", "GitHub Actions"]
deploy  = ["Vercel", "Render"]
```

</td>
</tr>
</table>

---

### `> tail -n 8 /var/log/ashvin-os.log`

```log
[2026-06-17 07:42:01] [INFO] [DSC-Engine] Tauri IPC channel bound successfully.
[2026-06-17 07:42:05] [INFO] [DSC-Engine] Loading local filesystem vector DB (privacy first).
[2026-06-17 07:43:12] [OK]   [NVIDIA-NIM] Connected to local Llama-3-8B-Instruct endpoint.
[2026-06-17 07:44:00] [OK]   [CUDA-Python] CUDA compiler initialized on GPU 0.
[2026-06-17 07:45:18] [INFO] [Checkora] Chess engine ready (Depth: 18, minimax thread pools active).
[2026-06-17 07:46:22] [WARN] [Slop-Guardian] High volume of AI slop detected in PR queue. Initiating block routine.
[2026-06-17 07:47:01] [INFO] No LinkedIn account detected by choice. This terminal acts as verified source.
[2026-06-17 07:47:35] [READY] Ashvin K S is open to engineering internships for 2026.
```

---

### `> ls -la ~/projects/shipped/`

```
drwxr-xr-x  ashvin  staff  1.2K  🏆 DSC (Desktop Shell Commander)
  └─ Tauri + React + Rust IPC desktop environment. Connects local file systems to NVIDIA NIM.
     Privacy-first desktop AI assistant keeping all user data completely on-device.
     → Repo: https://github.com/Ashvin-KS/DSC

drwxr-xr-x  ashvin  staff   512B ♟ Checkora
  └─ Chess platform featuring C++ minimax + alpha-beta pruning engine.
     → Repo: https://github.com/Ashvin-KS/Checkora  |  Live: https://checkora.vercel.app

drwxr-xr-x  ashvin  staff   512B 🔍 GSoC Org Finder
  └─ High-performance filter interface for all 184 GSoC 2026 partner organizations.
     → Repo: https://github.com/Ashvin-KS/GSoC-Org-Finder-  |  Live: https://findmygsoc.vercel.app

drwxr-xr-x  ashvin  staff   256B ⚡ intent-flow  [⭐ Starred]
  └─ Intent-driven workflow orchestration engine written entirely in pure Rust.
     → Repo: https://github.com/Ashvin-KS/intent-flow

drwxr-xr-x  ashvin  staff   512B 🧠 EnterpriseRAG-AI
  └─ Enterprise observability RAG pipeline featuring FastAPI, Redis, semantic search & tracing.
     → Repo: https://github.com/Ashvin-KS/EnterpriseRAG-AI

drwxr-xr-x  ashvin  staff   512B 📅 DailyForge
  └─ Productive MERN calendar tool with automatic layout overlap protection.
     → Repo: https://github.com/Ashvin-KS/DailyForge  |  Live: https://dailyforge-frontend-lhjq.onrender.com

drwxr-xr-x  ashvin  staff   256B 🤖 ai-slop-guardian
  └─ Proactive GitHub App detecting and flagging low-quality AI comments and issues.
     → Repo: https://github.com/Ashvin-KS/ai-slop-guardian
```

<details>
<summary><b>📦 ~/projects/archived/</b> (8 secondary projects)</summary>
<br/>

```
├── 🎵 Musicplayer        -> YT-sourced streaming app (React, Flask)
├── 🔧 arnio              -> C++ accelerated python data-quality toolkit
├── 🧭 pathfinder-ai      -> AI Career guidance app (mock interviews)
├── 📊 devtrack           -> Dev dashboard tracking commit metrics
├── 📝 Draftdeckai        -> Document automation toolkit
├── 🔄 pdfToPng           -> Zero-storage secure converter engine
├── 📚 EduAid             -> Interactive educational quiz generator
└── 💪 calisthenics-app   -> Local fitness workout track framework
```

> Links: [Musicplayer](https://github.com/Ashvin-KS/Musicplayer) · [arnio](https://github.com/Ashvin-KS/arnio) · [pathfinder-ai](https://github.com/Ashvin-KS/pathfinder-ai) · [devtrack](https://github.com/Ashvin-KS/devtrack) · [Draftdeckai](https://github.com/Ashvin-KS/Draftdeckai) · [pdfToPng](https://github.com/Ashvin-KS/pdfToPng) · [EduAid](https://github.com/Ashvin-KS/EduAid) · [calisthenics-app](https://github.com/Ashvin-KS/calisthenics-app)

</details>

---

### `> gpg --decrypt credentials.asc`

```
[✓] NVIDIA DLI        Building RAG Agents with LLMs (Verified)
                      → https://learn.nvidia.com/certificates?id=49ve03VPTzutzfy7COFhig
[✓] NVIDIA DLI        Fundamentals of CUDA Python (Verified)
                      → https://learn.nvidia.com/certificates?id=dIwwBtNGRF6Dc3syAF245g
[✓] DeepLearning.AI   Machine Learning Specialization (Verified)
                      → https://coursera.org/share/eb7c8afa8d746ddd582941a6d05e8a49
[✓] U. Helsinki       Full Stack Open (Verified)
                      → https://studies.cs.helsinki.fi/stats/api/certificate/fullstackopen/en/5346d975a83dfbc30160335374fc4985
[✓] Postman           API Fundamentals Student Expert (Verified)
                      → https://badges.parchment.com/public/assertions/kvMPTAfHTDmzAoSNblvaSA?identity__email=ashvinksg%40gmail.com
[✓] Google Cloud      Cloud Learning Paths (Verified)
                      → https://www.skills.google/public_profiles/33a2ea85-10bf-4245-b2fa-0ee4af814133
```

---

### `> systemctl status experience.service`

```
● experience.service - Professional Developer Record
     Loaded: loaded (/etc/systemd/system/experience.service; enabled)
     Active: active (running) since Oct 2024

  - Microsoft Innovations Club (VIT Chennai)
    Role: Full-Stack Developer [2024 - Present]
    Status: Active core member, shipping production grade code.

  - AOSSIE (GSSoC Contributor)
    Role: Open Source Contributor [2026 - Present]
    Status: Staged commits on PictoPy (Object detection, local face clustering).
```

---

### `> neofetch`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Ashvin-KS&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=c9d1d9&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub Stats" />
&nbsp;&nbsp;
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ashvin-KS&layout=donut-vertical&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top Languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Ashvin-KS&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=3fb950&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ashvin-KS&theme=github-dark&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=3fb950&area=true&area_color=58a6ff" alt="Activity Graph" width="95%" />

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ashvin-KS/Ashvin-KS/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ashvin-KS/Ashvin-KS/output/github-snake.svg" />
  <img alt="Snake eating contributions" src="https://raw.githubusercontent.com/Ashvin-KS/Ashvin-KS/output/github-snake.svg" />
</picture>

</div>

---

```
╔═══════════════════════════════════════════════════════════════════════════════╗
║                                                                               ║
║   ashvin@github:~$ echo "Closing session."                                   ║
║   Closing session. Connection terminated.                                     ║
║                                                                               ║
║   ashvin@github:~$ █                                                         ║
║                                                                               ║
╚═══════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">
<img src="https://komarev.com/ghpvc/?username=Ashvin-KS&style=flat-square&color=58a6ff&label=visitors" alt="Profile Views" />
</div>

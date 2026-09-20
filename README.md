# Marc van de Crommert

Full-stack developer in Vorstenbosch, Netherlands. I build Laravel platforms, and I optimise the way software gets built: **AI agents take the repetition**, **humans keep the judgment**.

By day I do R&D and custom development at [KJ Software](https://kjsoftware.nl). My main track is internal AI optimisation, making our own development route faster and more reliable, next to AI implementations for clients and security work. That code is private, so what you find here is the open part: side projects in Laravel and Filament, built with the same conventions.

---

## Projects

### AimTrack · [github](https://github.com/Marcvdc/AimTrack) · [aimtrack.nl](https://aimtrack.nl) · MIT
Self-hosted shooting logbook for sports shooters. Session logging in 30 seconds, an AI reflection per session, per-weapon trends, and CSV/PDF exports for your own club administration. The AI proposes, the shooter decides.  
Laravel 12, Filament 5, Livewire 3, PHP 8.4, queued AI jobs, Docker. Self-hosted or NL cloud. In active development.

### MotoTrax · [github](https://github.com/Marcvdc/mototrax)
Community platform for motorcycle riders: GPX route sharing, maintenance logs, social feed, AI-generated trip suggestions, versioned REST API with rate limiting. NL/Benelux first.  
Laravel 13, Filament 5, PHP 8.3, Docker, seeded demo environment.

### Monthli · [github](https://github.com/Marcvdc/Monthli) · Apache-2.0 · stopped July 2026
Privacy-first portfolio tracker (DEGIRO CSV import, monthly performance reports). Stopped for good after market research, and that research is in the repo: who does it better, for how much, and why building on would have been a waste. The code stays public as a Laravel reference: Laravel 12, Filament 4, PostgreSQL 16, Redis + Horizon, PHPStan, GitHub Actions CI.

### Internal AI tooling and R&D · private
My main track at KJ Software: an agent-driven route from ticket to pull request, automated code review, RAG-based knowledge retrieval and decision support, plus security work and AI implementations for clients. Those repos stay closed, but the principle is in everything above: transparent, overridable, and nothing merges without a human.

---

## Stack

**Backend** · PHP 8.3+, Laravel, Filament, Livewire, REST APIs  
**Frontend** · Blade, Alpine.js, Tailwind CSS  
**AI/LLM** · Claude, OpenAI, Gemini, Qwen · RAG (Qdrant) · local inference · agent workflows in Claude Code  
**Infra** · Docker, GitHub Actions, Linux, nginx, systemd, Proxmox  
**Data** · PostgreSQL, MSSQL, Redis, vector databases  

10+ years in PHP and infrastructure, Laravel and Filament as daily drivers, working with AI tooling since 2022.

---

## How I work

Every change runs the same route: plan, build with tests, lint, review against the conventions, pull request, then an independent adversarial check. A human merges, always.

Most AI tooling is built to replace human decisions. I think that is the wrong goal. Good AI-assisted software surfaces the right information at the right time, keeps an audit trail, explains its reasoning, and hands off gracefully. Expert knowledge becomes accessible without removing the expert.

> Good AI tooling makes the expert faster. It never makes the expert optional.

Code should be readable by whoever inherits it six months from now, including the AI parts.

---

📫 Everything here is hobby work in my own time. Professionally I work at [KJ Software](https://kjsoftware.nl), so that is where work enquiries go. Always happy to talk Laravel, agent workflows and self-hosted AI.

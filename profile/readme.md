# Rendiff – Zero‑Config Modern Video Pipeline Media APIs for FFmpeg

> **Production-grade media processing & intelligence – one `docker compose up` away.**

<p align="center">
  <a href="https://github.com/rendiffdev"><img alt="GitHub Org" src="https://img.shields.io/badge/GitHub-rendiffdev-181717?logo=github&style=for-the-badge"></a>
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge"></a>
  <a href="https://github.com/sponsors/rendiffdev"><img alt="GitHub Sponsors" src="https://img.shields.io/badge/Sponsor-❤-ff69b4?style=for-the-badge"></a>
</p>

---

**Rendiff** is an open‑source initiative that turns battle‑tested FFmpeg & FFprobe command lines into modern, self‑hosted micro‑services.  No vendor lock‑in, no hidden quotas – just pure, programmable media power anyone can run on‑prem or in the cloud.


| Project | Where It Fits | What It Does | Language | Repo |
|---------|--------------|--------------|----------|------|
| **FFmpeg API** | **“Do” layer** | Encode · Transcode · Package · Upscale | Python / FastAPI | [`rendiffdev/ffmpeg-api`](https://github.com/rendiffdev/ffmpeg-api) |
| **FFprobe API** | **“Know” layer** | Inspect · Validate · Score · Compare | Go / Gin | [`rendiffdev/ffprobe-api`](https://github.com/rendiffdev/ffprobe-api) |

Use them separately or chain them: probe ➜ decide ➜ encode ➜ probe again ➜ ship.

---

## 🚀 Why Rendiff?
- **Zero‑Config:** Launch everything with a single `docker compose up` – TLS, metrics & auth baked‑in.
- **Full FFmpeg Surface:** Every flag you know still works, now behind a clean JSON schema.
- **Async & Observable:** Job queue, SSE/WebSocket progress, Prometheus − Grafana dashboards.
- **GenAI Inside:** Multiple Local  LLMs  for natural‑language Q&A on media stats with OpenRouter fallback.
- **Polyglot & Composable:** Treat FFmpeg like any micro‑service and plug it into Python, Node, Rust…

> **Bottom line:** Stop copy‑pasting commands. Start shipping video features faster.Self managed, Opensource and no vendor lock.

---

## 🌄 Vision • Mission • Goal
| | |
|---|---|
| **Vision** | A world where shipping video at scale is as easy as calling a REST endpoint. |
| **Mission** | Deliver studio‑grade media processing & intelligence to every developer through open, self‑hosted APIs. |


---

## 🗺️ 2025 Roadmap (H2)

| Quarter | FFmpeg API | FFprobe API | Platform / DevOps | Community |
|---------|------------|-------------|-------------------|-----------|
| **Q3 2025** | v0.9 **Job‑Runner Stabilisation**  → resilient retries, pause/resume, priority queues<br>Preset Library (H.264, H.265, AV1, HLS ladders) | v0.7 **Streaming Manifest Linting** (HLS/DASH) & structural diff<br>Frame‑accurate timeline export | **Unified Auth Service** (JWT & API‑Key quotas)<br>Multi‑arch Docker images (x86_64 & arm64) | Weekly “Crash‑the‑Code” test sessions; RFC for Contributor Covenant |
| **Q4 2025** | **v1.0 GA** – semver freeze, backwards‑compat CLI<br>GPU auto‑tuner for NVENC & AMF | **v1.0 GA** – schema freeze, “probe once, trust forever” checksums | Helm Chart + Operator for k8s<br>First cut of **Kimi‑2 Local LLM** integration | Plugin SDK αlpha with sample **AV1 Film‑Grain Filter**; Launch docs.rendiff.dev with tutorials |
| **Continuous** | Bug‑bash Fridays, security patches within 48h | Auto‑publish SBOM & supply‑chain scan results | GitHub Actions → full SBOM, Docker SBOM<br>Digital Ocean & GitHub GPU grants programme | Monthly community showcase on rendiff.dev |

> **Reality‑check:** Dates represent achievable stretch goals assuming current volunteer velocity; PRs & sponsors accelerate everything.

---

---

## 🧑‍💻 How to Contribute (a.k.a. YOU should totally help!)
We are a **global OSS effort**—and we need all hands on deck:

| 🛠️ Need | Examples |
|---------|-----------|
| **Core Dev** | Go, Python, TypeScript, Rust, CUDA, WASM |
| **DevOps** | Docker, k8s, Helm, GitHub Actions, IaC lovers |
| **Media Gurus** | Transcoding edge‑cases, HDR, AV1, 360°, broadcast quirks |
| **Docs & DX** | Tutorials, recipe books, sample repos, logo/UX polish |
| **Bug‑Bashers** | Reproduce, minimize, fix → high‑five PR |



Every PR and ⭐ pushes open video tooling forward.

---

## 💪 Sponsors & Backers
Running nightly encoding farms, quality‑metrics sweeps and AI models costs 💸 & ⚡.  We gratefully accept:

| What We Need | Why | How to Help |
|--------------|-----|------------|
| **GPU Hours (RTX 4090 / A100 / MI300)** | Scale regression tests, Real‑ESRGAN upscaling, Local LLMs fine‑tuning | Donate cloud credits or lend bare‑metal time |
| **Object Storage** | Host terabytes of sample assets & automated artifacts | S3‑compatible buckets / CDN credits |
| **CI Minutes** | Run multi‑arch builds (x86, ARM, wasm) | GitHub Actions or Drone runners |
| ** SaaS  Tool Subs ** | To use  various SaaS tools to manage and maintain the projects.

> ** Backers** get logo placement  on website, projects and social mediashout outs, and bragging rights for backing the next‑gen video toolkit.

---

## 🙏 Special Thanks
Rendiff stands **on the shoulders of giants**, first and foremost **[FFmpeg](https://ffmpeg.org)** – the Swiss‑Army knife of video.  This project would not exist without the passionate maintainers and contributors who keep FFmpeg blazing‑fast and cutting‑edge.  ❤️  If you use Rendiff, please consider supporting the FFmpeg project directly.

---

## 📨 Contact
- **Website:** <https://rendiff.dev>
- **Email:** <dev@rendiff.dev>
- **X / Twitter:** [@rendifdev](https://x.com/rendifdev)

---

## ⚖️ License
MIT – free for personal, commercial, or unicorn ventures.  Spread the word, give credit, and help make video easier.

---

> **“FFmpeg APIs that just work.”** – That single promise keeps us shipping; we’re thrilled to have you along for the ride.

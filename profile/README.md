<div align="center">
  <a href="https://ilmora.co.id" target="_blank">
    <img src="https://raw.githubusercontent.com/ilmorahq/.github/main/assets/logo.png" alt="Ilmora Logo" width="260">
  </a>

  <br/><br/>

  <p align="center">
    <strong>Real-time AI voice and visual tutor on an infinite whiteboard.</strong>
  </p>

  <p align="center">
    <a href="https://ilmora.co.id"><img src="https://img.shields.io/badge/Website-ilmora.co.id-blue?style=flat-square" alt="Website"></a>
    <a href="https://ilmora.co.id"><img src="https://img.shields.io/badge/Platform-Live-success?style=flat-square" alt="Platform Live"></a>
    <a href="https://ilmora.co.id"><img src="https://img.shields.io/badge/Company-PT%20Ilmora%20Digital%20Innovation-slate?style=flat-square" alt="Entity"></a>
  </p>

  <p align="center">
    <a href="https://ilmora.co.id">Website</a> •
    <a href="https://ilmora.co.id">Platform</a> •
    <a href="#developer-platform-paas">Developer API</a> •
    <a href="https://www.linkedin.com/company/ilmorastartup">LinkedIn</a> •
    <a href="https://instagram.com/ilmorahq">Instagram</a> •
    <a href="mailto:admin@ilmora.co.id">Contact</a>
  </p>
</div>

---

### What is Ilmora?

[Ilmora](https://ilmora.co.id) is an AI tutoring platform designed to make personalized 1-on-1 private tutoring accessible and interactive. Rather than passive pre-recorded videos or text-only chatbots, Ilmora combines real-time conversational voice with a dynamic whiteboard engine that writes formulas, plots diagrams, and adapts to how each student learns.

- **Real-Time & Interruptible Voice** — Speak naturally. Students can interrupt mid-explanation to ask questions or clarify steps, just like working with a physical tutor.
- **Smart Whiteboard Engine** — Ingests learning materials (PDFs, slides, images), extracts formulas and diagrams, and plots visual reasoning steps directly on an infinite canvas.
- **Synchronized Audio & Canvas** — Visual strokes, diagrams, and step-by-step highlights are synchronized with the AI tutor's voice using Web Audio and GSAP.
- **Learning DNA** — Tracks confusion points, question interruptions, and comprehension pace across sessions to adapt the curriculum and pacing dynamically.

---

### Architecture Overview

```
[ Student Input: Voice / Documents ]
                │
                ▼
┌─────────────────────────────────────────────────────────┐
│                   ILMORA DUAL-CORE ENGINE               │
│                                                         │
│  ├─ Document Spatial Ingestion (PDF / PPT / Images)     │
│  ├─ Contextual Coordinate Mapper (Virtual Coordinate)   │
│  ├─ Multimodal Pedagogical Reasoner                     │
│  └─ Learning DNA State Graph (Adaptive Memory)          │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│               NEURAL AUDIO-VISUAL SYNC LAYER            │
│       Web Audio API  ◄── Precision Sync ──►  GSAP       │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
[ Interactive Client: Live Voice + Dynamic Whiteboard Canvas ]
```

---

### Developer Platform (PaaS)

Ilmora also provides a **Visual Reasoning Engine API** for schools, EdTech startups, and AI builders:

- **Spatial Document Ingestion**: Parse educational materials into machine-readable coordinate layers.
- **Stroke & Speech Streaming**: Stream synchronized vector strokes and synthetic voice over WebSockets/WebRTC.
- **Stateful Memory Graph**: Store and query learner-specific pedagogical trajectories.

For API access and enterprise integration inquiries, reach out via [admin@ilmora.co.id](mailto:admin@ilmora.co.id).

---

### Tech Stack

- **Frontend & Canvas**: TypeScript, Next.js, Canvas API, GSAP (GreenSock), Tailwind CSS
- **Audio & Realtime**: Web Audio API, WebRTC, Duplex WebSocket Streaming
- **Vision & Extraction**: Document Spatial Parser, Formula OCR, Vector Asset Generator
- **Backend & Memory**: Python, Cloud-native microservices, Redis

---

### Contact & Community

- **Website**: [ilmora.co.id](https://ilmora.co.id)
- **Company**: PT Ilmora Digital Innovation
- **Email**: [admin@ilmora.co.id](mailto:admin@ilmora.co.id)
- **LinkedIn**: [Ilmora](https://www.linkedin.com/company/ilmorastartup)
- **Instagram**: [@ilmorahq](https://instagram.com/ilmorahq)
- **GitHub**: [@ilmorahq](https://github.com/ilmorahq)

<br/>

<div align="center">
  <sub>© PT Ilmora Digital Innovation</sub>
</div>

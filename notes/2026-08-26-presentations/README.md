# Presentations – HackyHour Gießen

**UNIX Philosophy:** Do one thing well. Keep it simple. Composition over complexity.

---

## 📋 Table of Contents

- [Current Presentation: OpenDesk Edu (12+8 Format)](#-current-presentation-opendesk-edu-128-format)
- [Files](#-files)
- [12+8 Format Explained](#-128-format-explained)
- [UNIX Philosophy in Action](#-unix-philosophy-in-action)
- [Quick Start](#-quick-start)
- [Slide Overview](#-slide-overview)
- [Voting Information](#-voting-information)
- [Links & References](#-links--references)

---

## 🎤 Current Presentation: OpenDesk Edu (12+8 Format)

**📅 Date:** 26. August 2026  
**👤 Speaker:** Tobias Weiss (DevOps, Uni Marburg)  
**📍 Event:** HackyHour Gießen at Makerspace Gießen  
**⏱️ Format:** **12 minutes presentation + 8 minutes Q&A**  
**🎯 Topic:** OpenDesk Edu – Agentic Engineering in der Praxis  
**🔗 Live Link:** [Slides ✨](/presentations/opendesk_edu_12plus8.html)

---

## 📁 Files

| File | Purpose | Size |
|------|---------|------|
| [`opendesk_edu_12plus8.md`](opendesk_edu_12plus8.md) | **Marp source** – Edit this! | 3.4KB |
| [`opendesk_edu_12plus8.html`](opendesk_edu_12plus8.html) | **Browser-ready** – Open in any browser | 127KB |
| [`opendesk_edu_12plus8.pdf`](opendesk_edu_12plus8.pdf) | **Printable** – For handouts or offline viewing | 60KB |
| [`SPEAKER_NOTES_12plus8.md`](SPEAKER_NOTES_12plus8.md) | **Detailed script** – Word-for-word with timing | 6KB |
| [`CHEAT_SHEET.md`](CHEAT_SHEET.md) | **Quick reference** – Key points for on-stage | 3KB |

---

## ⏱️ 12+8 Format Explained

**12 minutes:** Tight, focused presentation  
**+8 minutes:** Q&A, discussion, audience interaction

**Perfect for:** Following a main talk (Christian Uhl's "Agentic AI in der Praxis")

---

## 🖥️ UNIX Philosophy in Action

This presentation follows **UNIX principles**:

### **🎯 Do One Thing Well**
- Each slide has **one clear message**
- No slide tries to do too much
- Every element serves a purpose

### **🔧 Small, Sharp Tools**
- **12 main slides** – Each is a "tool" for communication
- **3 backup slides** – Available if needed
- **Minimal text** – Maximum meaning

### **🔗 Composition**
- Slides **flow together** like Unix pipes
- Problem → Solution → Validation → Action
- **|** connects everything

### **⚪ Clarity Through Simplicity**
- **Black text on white** – Like a terminal
- **White space** = clarity
- **Less is more**

### **🔇 Silence is a Feature**
- Audience focuses on **your words**, not slides
- Pauses emphasize key points
- Minimal distractions

---

## 🚀 Quick Start

### **Viewing:**
- 🌐 **HTML:** Open `opendesk_edu_12plus8.html` in any browser
- 📄 **PDF:** Open `opendesk_edu_12plus8.pdf` in any PDF viewer
- 📝 **Source:** Edit `opendesk_edu_12plus8.md` with any text editor

### **Editing:**

```bash
# Install Marp CLI globally
npm install -g @marp-team/marp-cli

# Convert to HTML
marp opendesk_edu_12plus8.md -o opendesk_edu_12plus8.html

# Convert to PDF
marp opendesk_edu_12plus8.md -o opendesk_edu_12plus8.pdf --pdf --allow-local-files

# As slide images (for review):
marp opendesk_edu_12plus8.md --images png -o .preview/preview.png
```

---

## 📊 Slide Overview

### **🎯 Core Presentation (12 slides – 12 minutes):**

| # | Slide | Time | Message |
|---|-------|------|---------|
| 1 | **Title** | 0:00-0:30 | Introduction |
| 2 | **Problem** | 0:30-1:00 | 3 real pain points |
| 3 | **Prinzipien** | 1:00-1:30 | 4 Agentic Engineering principles |
| 4 | **Architektur** | 1:30-2:30 | 4 Agents + k3s infrastructure |
| 5 | **Use Case 1** | 2:30-3:30 | Prof. Müller: **9h saved** |
| 6 | **Use Case 2** | 3:30-4:30 | Max: **85% faster** |
| 7 | **Use Case 3** | 4:30-5:30 | Forschung: **300% faster** |
| 8 | **Daten** | 5:30-6:30 | Pilot study: +42%, +35%, 4.7/5 |
| 9 | **Stack** | 6:30-7:30 | Node.js, LLM, Next.js, **k3s** |
| 10 | **Installation** | 7:30-8:30 | 5 minutes setup |
| 11 | **Voting** | 8:30-9:30 | QR code + link |
| 12 | **Fragen** | 9:30-12:00 | Buffer + early Q&A |

### **❓ Backup Slides (+8 minutes):**
- **Slide 13:** k3s Warum? (Lightweight, simple, free, robust)
- **Slide 14:** Roadmap (Q4 2026: Beta, Q1 2027: Plugins, etc.)

---

## 🎯 Content Highlights

### **🔥 The 3 Value Propositions:**

1. **Use Case 1:** Prof. Müller saves **9 hours/week** on grading
2. **Use Case 2:** Max learns **85% faster** (30 min vs 3 hours)
3. **Use Case 3:** Research projects **300% faster** (6 weeks vs 4 months)

### **📊 The Validation:**
- **Pilotstudie Uni Marburg:** 200 Studierende
- **+42% Lernfortschritt** (statistisch signifikant)
- **+35% Retention** (behalten mehr)
- **4.7/5.0 Nutzerzufriedenheit**

### **🏗️ The Tech:**
- **Backend:** Node.js + TypeScript + Fastify
- **AI:** LangChain.js + Ollama (local LLM inference)
- **DB:** PostgreSQL + Qdrant (vector)
- **Frontend:** Next.js 14
- **Infrastructure:** **k3s** (lightweight Kubernetes – 1GB RAM reicht)

### **⚡ The Deployment:**
```bash
# k3s (1 command)
curl -sfL https://get.k3s.io | sh -

# OpenDesk Edu (1 command)
kubectl apply -f opendesk-edu.yaml
```

---

## 🗳️ Voting Information

### **The Ask:**
Support OpenDesk Edu in the **Open Source Wettbewerb 2026** (Community-Voting; 65 Projekte)

### **How:**
- **QR Code:** Scan with phone camera (in Slide 11)
- **URL:** [https://open-source-wettbewerb.de/voting/opendesk-edu/](https://open-source-wettbewerb.de/voting/opendesk-edu/)
- **Deadline:** **30. September 2026**
- **Time:** Takes less than 30 seconds

### **Why It Matters:**
- **Visibility** – More recognition for the project
- **Credibility** – Validation from the community
- **Resources** – Access to funding and support
- **Impact** – Helps shape the future of open source education

---

## 🎯 Presentation Philosophy

### **-less is more**
This presentation embraces **minimalism** and **clarity**:

- **Fewer slides** = More impact
- **Less text** = More understanding
- **Simpler design** = More focus
- **Clear message** = More retention

### **UNIX in Practice**
```
Problem → Agentic Engineering → OpenDesk Edu → Results
   │              │                 │           │
   ▼              ▼                 ▼           ▼
 Pain        Principles        Solution      Data
```

Each element **does one thing well** and **composes with others**.

---

## 📋 Preparation Checklist

### **📁 Files:**
- [ ] `opendesk_edu_12plus8.html` – Main presentation
- [ ] `opendesk_edu_12plus8.pdf` – Backup
- [ ] `opendesk_edu_12plus8.md` – Source
- [ ] `SPEAKER_NOTES_12plus8.md` – Script
- [ ] `CHEAT_SHEET.md` – Quick reference
- [ ] `voting-qr.png` – Offline QR für Voting (Folie 12)

### **💻 Technology:**
- [ ] Laptop charged (>50%)
- [ ] Presentation tested in browser (offline capable)
- [ ] PDF backup on desktop
- [ ] Clicker tested
- [ ] HDMI adapter (if needed)

### **🧠 Mental Prep:**
- [ ] Review speaker notes
- [ ] Practice timing (aim for ~1 min per slide)
- [ ] Memorize key metrics (9h, 85%, 300%)
- [ ] Prepare for 3 likely questions

---

## 🔗 Links & References

### **Presentation:**
- [Slides (HTML)](/presentations/opendesk_edu_12plus8.html)
- [Slides (PDF)](/presentations/opendesk_edu_12plus8.pdf)
- [Source (MD)](/presentations/opendesk_edu_12plus8.md)

### **OpenDesk Edu:**
- [Website](https://opendesk-edu.org/)
- [GitHub](https://github.com/opendesk-edu)
- [Docs](https://docs.opendesk-edu.org/)

### **k3s:**
- [Website](https://k3s.io/)
- [GitHub](https://github.com/k3s-io/k3s)
- [Installation](https://docs.k3s.io/installation)

### **Voting:**
- [Open Source Wettbewerb 2026](https://open-source-wettbewerb.de/voting/opendesk-edu/)

---

---

**🎯 Remember:** *"UNIX: Simple. Elegant. Powerful."*

*Last updated: 26. August 2026*

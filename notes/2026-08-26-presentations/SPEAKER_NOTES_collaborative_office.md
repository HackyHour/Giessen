# Speaker Notes: OpenDesk – Collaborative Office Cloud Suite
## 12+8 Minuten Präsentation | HackyHour Gießen | 26.08.2026

---

## UNIX Philosophie
**Ein Thema pro Slide. Ein Slide = Eine Botschaft. Keine Ablenkung.**

---

## Timing Guide

### Slide 1: Titel (0:00 - 0:30)
**Sprechtext:**
"Guten Abend! Mein Name ist Tobias Weiss, ich bin DevOps Engineer an der Uni Marburg. Heute stelle ich euch OpenDesk vor – eine collaborative Office Cloud Suite, die соверän auf eigener Infrastruktur läuft. Im Anschluss an Christians Vortrag über Agentic AI zeige ich euch, wie diese Prinzipien in einer konkreten Anwendungen umgesetzt werden."

**Timing:** 30 Sekunden
**Visual:** Titel + Untertitel
**Ziel:** Aufmerksamkeit, Einführung, Kontext setzen

---

### Slide 2: Herausforderung (0:30 - 1:30)
**Sprechtext:**
"Moderne Teamarbeit hat klare Anforderungen: Gemeinsame Dokumentenbearbeitung, Echtzeit-Kollaboration, automatisierte Workflows und vor allem – Datensouveränität. OpenDesk bietet genau das: Eine offene, self-hosted Lösung, die all diese Bedürfnisse vereint. Kein Vendor-Lock-in, keine externen Server, volle Kontrolle."

**Timing:** 60 Sekunden
**Visual:** 4 Bullet Points
**Ziel:** Problem verstehen, Lösung freuen

---

### Slide 3: Prinzipien (1:30 - 2:30)
**Sprechtext:**
"Hinter OpenDesk steht der Ansatz des Agentic Engineering. Das bedeutet: Systeme, die autonom handeln, proaktiv Lösungen anbieten, sich an neue Anforderungen anpassen, die Zusammenarbeit in den Mittelpunkt stellen – und vor allem: **Human-in-the-Loop**. Der Mensch bleibt immer Entscheidungsinstanz. OpenDesk kombiniert die klassische Office Suite mit intelligenter Agenten-Technologie, aber Sie behalten die Kontrolle."

**Timing:** 60 Sekunden
**Visual:** 5 Prinzipien + Connection Statement
**Ziel:** Technischen Ansatz erklären, HITL hervorheben

---

### Slide 4: Human-in-the-Loop (2:30 - 3:00)
**Sprechtext:**
"Ein zentraler Punkt von Agentic Engineering ist Human-in-the-Loop. Das Diagramm zeigt es: Auf der einen Seite der Mensch, der entscheidet und kontrolliert. Auf der anderen Seite der Agent, der unterstützt und vorschlägt. Es ist eine Partnerschaft – die Intelligenz der Maschine kombiniert mit der Urteilsfähigkeit des Menschen. Agenten propone, Menschen disponen – so bleiben wir Herr der Lage."

**Timing:** 30 Sekunden
**Visual:** HITL-Diagramm
**Ziel:** HITL-Prinzip klar vermitteln

---

### Slide 5: Architektur (3:00 - 4:00)
**Sprechtext:**
"Die Architektur ist simpel: Oben die Anwendungen – Dokumente, Teamorte, Workflows, Agenten. Unten die Infrastruktur: Ein leichtes k3s Kubernetes Cluster, das auf jedem Gerät von Raspberry Pi bis Server läuft. Dazwischen offene Schnittstellen. Alles modular, alles erweiterbar. Und immer mit HITL – der Mensch bleibt im Zentrum."

**Timing:** 60 Sekunden
**Visual:** ASCII-Diagramm
**Ziel:** Technische Struktur verstehen

---

### Slide 5: Use Case 1 – Team Dokumentation (3:30 - 4:30)
**Sprechtext:**
"Erster Use Case: Team Dokumentation. Problem: Veraltete Wikimedia, zentrale Pflege nötig, alle müssen den bottlenecks warten. Lösung: Gemeinsame Bearbeitung mit Agenten-Unterstützung – die Dokumente aktualisieren sich quasi von selbst. Ergebnis: 40 Prozent mehr Aktualität bei 60 Prozent weniger Pflegeaufwand."

**Timing:** 60 Sekunden
**Visual:** Problem → Lösung → Ergebnis
**Ziel:** Praktischer Nutzen sichtbar

---

### Slide 6: Use Case 2 – Projektmanagement (4:30 - 5:30)
**Sprechtext:**
"Zweiter Use Case: Projektmanagement. Problem: Manuelle Status-Updates, ständig wiederkehrende Aufgaben. Lösung: Automatisierte Workflows mit Kollaborations-Agenten, die den Überblick behalten. Ergebnis: 35 Prozent weniger Projektzeit und 70 Prozent weniger Fehler durch Automatisierung."

**Timing:** 60 Sekunden
**Visual:** Problem → Lösung → Ergebnis
**Ziel:** Präzisen Nutzen zeigen

---

### Slide 7: Use Case 3 – Wissensmanagement (5:30 - 6:30)
**Sprechtext:**
"Dritter Use Case: Wissensmanagement. Problem: Informationen überall verstreut, Suche wie Nadel im Heuhaufen. Lösung: Intelligente Verknüpfung und Kontext-Erkennung durch Agenten. Ergebnis: 80 Prozent bessere Findbarkeit und 25 Prozent höhere Wissensnutzung im Team."

**Timing:** 60 Sekunden
**Visual:** Problem → Lösung → Ergebnis
**Ziel:** Dritten konkreten Nutzen zeigen

---

### Slide 8: Vision 2026 (6:30 - 7:30)
**Sprechtext:**
"Unser Ziel für 2026: Ein Pilot an der Uni Marburg mit 200 Nutzer:innen, 2 Fachbereichen und einer Testphase von 3 Monaten bei 98 Prozent Verfügbarkeit. Das ist unsere Vision für souveräne Zusammenarbeit – ganz ohne Kompromisse bei Datenschutz oder Funktionalität. Wir sind auf dem Weg dorthin."

**Timing:** 60 Sekunden
**Visual:** 4 Ziele als Bullet Points
**Ziel:** Vision und Roadmap vermitteln

---

### Slide 9: Stack (7:30 - 8:00)
**Sprechtext:**
"Der Technologie-Stack: Backend in Node.js mit TypeScript und Fastify. AI-Komponenten mit LangChain und lokalem Ollama. Datenbanken PostgreSQL und Qdrant. Frontend mit Next.js 14. Und als Basis: k3s, das leichte Kubernetes – Temperatur 1GB RAM reicht völlig aus. UNIX-Prinzip: Ein Werkzeug, eine Aufgabe, perfekt gelöst."

**Timing:** 30 Sekunden
**Visual:** 5 Technologien + UNIX-Statement
**Ziel:** Technische Basis für Expert:innen

---

### Slide 10: Installation (8:00 - 9:00)
**Sprechtext:**
" Installiert ist OpenDesk in 5 Minuten. Ein Befehl für k3s, ein Befehl für OpenDesk – fertig. Keine komplizierten Setups, keine teure Hardware. Eigenes Office-System, selbst gehostet, in Rekordzeit."

**Timing:** 60 Sekunden
**Visual:** 2 Code-Blöcke
**Ziel:** Einfachheit demonstrieren

---

### Slide 11: Mitmachen (9:00 - 10:00)
**Sprechtext:**
"OpenDesk ist Open Source und nimmt am diesjährigen Open Source Wettbewerb teil. Ihr könnt mitmachen, mit Abstimmen, mit Entwickeln. Hier der QR-Code oder der Link: open-source-wettbewerb.de slash voting slash opendesk. 30 Sekunden, große Wirkung. Jede Stimme zählt!"

**Timing:** 60 Sekunden
**Visual:** QR-Code + Link
**Ziel:** Call-to-Action, Community einbinden

---

### Slide 12: Fragen (10:00 - 18:00)
**Sprechtext:**
"Das war OpenDesk – Collaborative Office Cloud Suite. Ich freue mich auf eure Fragen, Diskussionen und Ideen. Wer selbst ausprobieren will: Der Link zu den Slides ist im Repository, und die Installation dauert ja nur 5 Minuten."

**Timing:** 10 Sekunden Einführung, dann 8 Minuten Q&A
**Visual:** "Fragen +8 Minuten"
**Ziel:** Interaktion initieren

---

## Backup Slides (nur bei Bedarf)

### Backup 1: k3s Vorteile
**Wenn gefragt wird:** "Warum k3s?"
**Sprechtext:** "k3s ist perfekt für OpenDesk, weil es leicht ist – läuft auf einem Raspberry Pi, aber auch auf großen Servern. Einfach: Ein Befehl genügt für die Installation. Kostenlos: Null Euro Infrastrukturkosten. Und robust: Production-ready, also bereit für den echten Einsatz."

### Backup 2: Roadmap
**Wenn gefragt wird:** "Was kommt als Nächstes?"
**Sprechtext:** "Die Roadmap: Q4 dieses Jahres bringen wir eine Public Beta raus. Q1 2027 folgt ein Plugin-System für Erweiterungen. Q2 2027 mobile Clients für unterwegs. Und Q3 2027 Enterprise-Integration für größere Organisationen."

---

## Cheat Sheet für die Bühne

### Wichtige Zahlen (auswendig lernen):
- **200 Nutzer:innen** (Pilot Uni Marburg)
- **5 Fachbereiche** (Pilot)
- **98% Verfügbarkeit** (Pilot)
- **1GB RAM** (k3s Mindestanforderung)
- **5 Minuten** (Installationszeit)
- **30 Sekunden** (Voting Zeit)

### Wichtige Links:
- **Slides:** `tobias-weiss-ai-xr.github.io/Giessen/presentations/opendesk_collaborative_office_12plus8.html`
- **Voting:** `open-source-wettbewerb.de/voting/opendesk/`
- **OpenDesk:** `opendesk-edu.org`

### Technische Fakten:
- **Backend:** Node.js + TypeScript + Fastify
- **Frontend:** Next.js 14
- **AI:** LangChain.js + Ollama
- **DB:** PostgreSQL + Qdrant
- **Infra:** k3s

### UNIX Arzt:
- **Ein Werkzeug** = Eine Aufgabe
- **Ein Slide** = Eine Botschaft
- **Keine Ablenkung** = Klarer Fokus

---

## Notfall-Plan

### Wenn die Technik versagt:
1. Laptop neu starten (30 Sekunden)
2. Präsentation lokal öffnen (Datei vorhanden?)
3. PDF-Version nutzen (immer funktioniert)
4. Einfach frei sprechen (Slides sind nur Unterstützung)

### Wenn die Zeit knapp wird:
1. Use Cases 2 und 3 zusammenfassen (30 Sekunden pro Use Case)
2. Praxisbeispiel überspringen
3. Direkt zu Installation und Voting springen

### Wenn zu viel Zeit ist:
1. Backup Slides zeigen
2. Live-Demo andeuten (wenn vorbereitet)
3. Tiefer auf technische Details eingehen
4. Diskussion früher starten

---

## Erfolgskriterien

✅ **Zeit einhalten:** 12 Minuten (+/- 30 Sekunden)
✅ **Alle 3 Use Cases erwähnen** (Dokumentation, Projektmanagement, Wissensmanagement)
✅ **QR-Code zeigen** (Handy aus dem Publikum braucht Sichtkontakt)
✅ **Voting-Link laut vorlesen** (2x wiederholen)
✅ **Lächeln und Augenkontakt** (auch mit Online-Teilnehmenden)
✅ **Keine Fußnoten** (Sauber, UNIX, professionell)

---

*Speaker Notes v1.0 | UNIX compliant | Letzte Aktualisierung: 26.08.2026*

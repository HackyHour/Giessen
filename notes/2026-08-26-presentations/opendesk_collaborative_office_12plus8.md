---
marp: true
theme: default
paginate: false
style: |
  section {
    font-family: 'Helvetica Neue', Arial, sans-serif;
    font-size: 32px;
    line-height: 1.4;
  }
  h1 { font-size: 48px; color: #000; }
  h2 { font-size: 36px; color: #000; }
  h3 { font-size: 30px; color: #000; }
  img { background: transparent !important; max-width: 100%; height: auto; }
  .diagram { text-align: center; margin: 20px 0; }
  pre { background: transparent !important; border: none !important; padding: 0 !important; font-family: monospace; font-size: 24px; line-height: 1.2; }
  /* Hide all footers */
  section::after { display: none !important; }
  footer { display: none !important; }
  [class*="footer"] { display: none !important; }
---

# OpenDesk Edu
## Collaborative Office Cloud Suite

Tobias Weiss | DevOps Engineer, Uni Marburg

**Souveräne Zusammenarbeit mit offener Technologie – auf eigener Infrastruktur**

---

# Herausforderung

**Moderne Teamarbeit braucht:**
- Gemeinsame Dokumentenbearbeitung
- Echtzeit-Kollaboration
- Automatisierte Workflows
- Datensouveränität

**OpenDesk Edu bietet all das – offen und self-hosted.**

---

# Prinzipien

**Agentic Engineering:**
1. **Autonomie** – Systeme handeln selbstständig
2. **Proaktivität** – Lösungen werden vorweggenommen
3. **Reaktivität** – Anpassung an neue Anforderungen
4. **Sozialität** – Zusammenarbeit im Fokus
5. **Human-in-the-Loop** – Mensch bleibt Entscheidungsinstanz

**Kollaborative Office Suite trifft auf intelligente Agenten – mit menschlicher Kontrolle.**

---

# Human-in-the-Loop

<div class="diagram">

```
   +--------+       kontrolliert       +----------+
   | Mensch | ---------------------> |   Agent  |
   | Entscheid|                       | Schlägt |
   +--------+ <---------------------- +----------+
       unterstützt
```

</div>

**Agenten unterstützen – Menschen entscheiden.**

---

# Architektur

<div class="diagram">

```
   +------------------+
   |  OpenDesk Edu    |
   +--------+---------+
            |
   +--------v---------+     +------------------+
   |    Dokumente     |<--->|   Team Orte      |
   +------------------+     +------------------+
   |   Workflows      |<--->|    Agenten       |
   +--------+---------+     +--------+---------+
            |                          |
            +----------+-------------+------v--+
                       |     k3s Cluster      |
                       +----------+-------------+
                                  |
                         +--------+---------+
                         | Sovereign Cloud Stack |
                         +------------------+
```

</div>

**Einfach. Offene Schnittstellen. Self-Hosted.**

---

# Use Case 1

**Team Dokumentation**

Problem: Veraltete Wikimedia, zentrale Pflege nötig

Lösung: Gemeinsame Bearbeitung mit **Agenten-Unterstützung + HITL**

*Mensch validiert, Agent schlägt vor.*

---

# Use Case 2

**Projektmanagement**

Problem: Manuelle Status-Updates, wiederkehrende Aufgaben

Lösung: Automatisierte Workflows mit **Kollaborations-Agenten + HITL**

*Mensch entscheidet, Agent empfiehlt.*

---

# Use Case 3

**Wissensmanagement**

Problem: Verstreute Informationen, schwierige Suche

Lösung: Intelligente Verknüpfung mit **Kontext-Erkennung + HITL**

*Mensch bewertet, Agent verknüpft.*

---

# Vision 2026

**Pilot Uni Marburg (Ziel):**

- 200 Nutzer:innen
- 2 Fachbereiche
- 3 Monate Testphase
- 98% Verfügbarkeit

**Souveräne Zusammenarbeit – ohne Kompromisse.**

---

# Stack

<div class="diagram">

```
+------------------+
|  OpenDesk Edu    |
+--------+---------+
         |
+------------------+     +------------------+     +------------------+
|   OpenCloud      |     |      SOGo        |     |   OpenProject    |
|  (Dokumente)     |     | (E-Mail & Group) |     |  (Projektmgmt)   |
+--------+---------+     +--------+---------+     +--------+---------+
         |                     |                     |
+--------+---------+     +--------+---------+     +--------+---------+
|   Matrix/Element |     |    Keycloak      |     |      SCS         |
|  (Chat & Kollab) |     | (Identity & Auth)|     |(Sovereign Cloud) |
+--------+---------+     +--------+---------+     +-------+--------+
         |                     |                        |
+--------+---------+     +------------------------+--------+---------+
|   Galera Cluster |     |      PostgreSQL        |        |   Redis  |
|   (MariaDB)      |     |   (OpenProject DB)      |        | (Cache)  |
+--------+---------+     +------------------------+        +---------+
         |                     |                        |
         +---------------------+------------------------+
                                  |
                         +--------+---------+
                         |   k3s Cluster    |
                         | (Kubernetes)     |
                         +------------------+
```

</div>

**OpenCloud, SOGo, OpenProject, Matrix/Element, Keycloak, Galera DB, PostgreSQL, Redis auf k3s.**

---

# Installation

```bash
# k3s (1 Befehl)
curl -sfL https://get.k3s.io | sh -

# OpenDesk Edu auf Sovereign Cloud Stack (1 Befehl)
kubectl apply -f opendesk-scs.yaml
```

**5 Minuten. Eigenes Office auf k3s. Fertig.**

---

# Mitmachen

**Open Source Wettbewerb 2026**

<div class="diagram">
<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://open-source-wettbewerb.de/voting/opendesk-edu/" alt="QR Code" width="200" />
</div>

Link: [open-source-wettbewerb.de/voting/opendesk-edu/](https://open-source-wettbewerb.de/voting/opendesk-edu/)

**30 Sekunden. Offene Zukunft unterstützen.**

---

# Fragen
## +8 Minuten

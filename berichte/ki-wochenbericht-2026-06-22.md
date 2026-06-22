# KI-Wochenbericht: 15.-22. Juni 2026

Erstellt: 22. Juni 2026

---

## 1. KI-Tools für KMU im DACH-Raum

- Keine relevanten Neuveröffentlichungen im DACH-Segment in den letzten 7 Tagen. Laufende Tools (DATEV KI, Neuroflash) laufen ohne größere Feature-Sprünge weiter.
- Laut aktueller DIHK-Umfrage nutzen 38% der deutschen KMU KI aktiv; der DMB/Salesforce-Index nennt 51%. Die Einstiegshürde sinkt, aber konkrete Implementierungen fehlen vielen noch.
- Für Buchhaltungs-Automatisierung bleibt DATEV KI der DACH-Standard; Neuroflash (deutschsprachig, DSGVO-konform, deutsche Server) für Content-Erstellung.

## 2. n8n / Make / Zapier

- **n8n** (diese Woche): Bugfix "Preserve structuredContent in MCP-Nodes" behebt KI-Agent-Endlosschleifen - direkt relevant für stabile KMU-Produktivworkflows.
- **n8n Human-in-the-Loop (HITL)**: Kritische KI-Aktionen (E-Mails senden, Datensätze löschen) lassen sich jetzt manuell freigeben. Gutes Verkaufsargument für risikoaverse Kunden.
- **Make AI Agents**: Seit Anfang 2026 in General Availability (kein Beta mehr). Einfachster Einstieg für KMU ohne Entwickler.
- **Zapier MCP**: Verbindet Claude/ChatGPT direkt mit 9.000+ Apps ohne Code. Interessant für Kunden, die bereits Zapier nutzen.

## 3. Lokale Modelle (Ollama / Apple Silicon)

- **Ollama v0.30.10** (17. Juni): Bringt "Command A" und "North"-Modelle auf Apple Silicon via MLX-Engine; llama.cpp auf Build 9672 aktualisiert.
- **MiniMax M3** (neu in Ollama): Open-Weight, 1-Million-Token-Kontext, native Bild- und Video-Analyse, 59% auf SWE-Bench Pro. Sehr interessant für lokale Dokumenten-Workflows unter DSGVO.
- Wichtige Einschränkung: MLX-Beschleunigung (~112 Tokens/s) gilt nur ab 32 GB RAM. Macs mit 8/16 GB laufen weiterhin über den alten Metal-Pfad ohne Geschwindigkeitsvorteil.
- Empfehlung für 16-GB-Macs: Qwen 3 27B (Q4) oder gpt-oss:20b bleiben die erste Wahl.

## 4. DSGVO / EU AI Act

- **Digital Omnibus (Mai 2026) verschiebt Hochrisiko-Fristen**: HR-, Biometrie- und Bildungsanwendungen greifen jetzt ab Dezember 2027 statt August 2026.
- **Nicht verschoben - dringend: Art. 4 KI-Kompetenznachweispflicht** gilt weiterhin ab **2. August 2026** (in 6 Wochen). Mitarbeiterdokumentation muss bis dahin stehen.
- Kennzeichnungspflicht für KI-generierte Inhalte auf 2. Dezember 2026 verschoben.
- KMU-Erleichterungen ausgeweitet auf "Small Mid-Caps" bis 200 Mio. Euro Jahresumsatz: reduzierte technische Dokumentation bei Hochrisiko-Systemen erlaubt.

## 5. Förderprogramme NRW / Bund

- **NRW MID-Gutscheine** (laufend): MID-Digitalisierung bis 15.000 €, MID-Innovation bis 48.000 € - kein neuer Call diese Woche, aber weiterhin offen.
- **ZIM (Bund)**: Neu ab 2026 - bis zu 35% der Kosten für externe KI-Experten ansetzbar. Themenoffen, nicht rückzahlbar. Stabile Bewilligungsquote.
- **Zukunftszentrum KI NRW**: Bietet kostenlose Förderberatung für KMU an - guter erster Schritt für Kunden ohne Fördererfahrung.

## 6. Verkaufbare Anwendungsfälle

**Use Case 1: Angebotsprozess-Automatisierung im Handwerk**
Branche: Sanitär/Elektro/Bau. Stack: n8n + LLM. Eingehende E-Mail-Anfragen werden automatisch ausgelesen, ein Angebotsdraft erstellt und per HITL zur Freigabe vorgelegt. Aufwand: 3-5 Tage. ROI: 4-6 Monate. Förderfähig über MID-Digitalisierung.

**Use Case 2: Lokaler Dokumenten-Chat für Kanzleien**
Branche: Steuerberatung, Versicherungen, Kanzleien. Stack: Ollama + MiniMax M3 lokal auf Mac Studio (M2 Ultra, min. 32 GB). Mitarbeitende stellen Fragen an interne PDFs und Verträge, kein Datenabfluss nach außen. Aufwand: 5-8 Tage. DSGVO-konform by Design.

---

## Das solltest du dir genauer anschauen

1. **Art. 4 EU AI Act - Frist 2. August 2026**: Noch 6 Wochen. Kunden ohne Mitarbeiterdokumentation jetzt ansprechen. Vorlage: [Skill-Sprinters KMU-Entlastung](https://skill-sprinters.de/blog/compliance/eu-ai-act-omnibus-kmu-entlastung-2026/)

2. **MiniMax M3 in Ollama testen**: Open-Weight mit 1-Millionen-Token-Kontext und Bildanalyse lokal auf Apple Silicon. Wer ein Mac Studio mit 32+ GB betreibt, sollte das als neuen Standard für datenschutzkritische KMU-Projekte testen. Einrichtungszeit: ca. 1 Stunde.

---

## Quellen

- [Ollama v0.30.10 Versionshistorie - Local AI Master](https://localaimaster.com/blog/ollama-version-history)
- [Ollama June 2026 Update - Prompt Quorum](https://www.promptquorum.com/local-llms/top-open-source-models-ollama)
- [EU AI Act Digital Omnibus für den Mittelstand - allbytes.de](https://www.allbytes.de/blog/eu-ai-act-digital-omnibus-kmu/)
- [Digital Omnibus beschlossen - ScaleWise](https://www.scalewise-ai.de/blog/2026-05-digital-omnibus-einigung-eu-ai-act-fristen)
- [EU AI Act KMU-Entlastung - Skill-Sprinters](https://skill-sprinters.de/blog/compliance/eu-ai-act-omnibus-kmu-entlastung-2026/)
- [n8n Release Notes Juni 2026 - Releasebot](https://releasebot.io/updates/n8n)
- [n8n 2026 Updates - Softomate Solutions](https://www.softomatesolutions.com/blog/n8n-updates-2026-whats-new/)
- [Make vs Zapier vs n8n 2026 - Automation Labs](https://medium.com/@automation.labs/zapier-vs-make-vs-n8n-in-2026-where-ai-agents-actually-fit-1edbbeff85f3)
- [KI-Förderung KMU 2026 - hypescale](https://hypescale.com/de/blog/ki-foerderung-kmu-2026-programme-zuschuesse)
- [Zukunftszentrum KI NRW - Förderberatung](https://www.zukunftszentrum-ki.nrw/angebote/foerderberatung/)

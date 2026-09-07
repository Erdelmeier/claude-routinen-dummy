# KI-Wochenbericht -- 7. September 2026

Recherchezeitraum: 31. August -- 7. September 2026

---

## 1. Neue KI-Tools für KMU im DACH-Raum

- Keine neuen Tools mit echtem DACH-Marktstart diese Woche. Der Markt ist gesättigt mit Toolverzeichnissen (KI-Syndikat listet 234 Tools für Unternehmen, Stand August 2026), aber neue Releases landen meist erst nach Wochen in den DACH-Distributionskanälen.
- 38% der deutschen KMU nutzen laut Bitkom Digital Index 2025 bereits regelmäßig KI-Tools -- die Basisnachfrage ist da. Das Gespräch verschiebt sich von "Sollen wir KI einsetzen?" zu "Welches Tool passt, und wie schützen wir die Daten?".
- Bewertung: Kein Handlungsbedarf diese Woche. Bestehende Empfehlungen (Brevo, Neuroflash, Claude/ChatGPT) bleiben gültig.

## 2. n8n, Make, Zapier: neue AI-Nodes und Integrationen

- **n8n MCP-Support (produktionsreif):** n8n kann jetzt als MCP-Client externe KI-Systeme wie Claude Desktop aufrufen und umgekehrt selbst als MCP-Server auftreten. Workflows werden so für KI-Agents zu aufrufbaren Tools. Das ist die stärkste Architekturänderung seit dem AI-Agent-Node: KMU-Daten bleiben on-premise, die KI-Schnittstelle ist standardisiert.
- **Notion-Node v3:** Migriert auf Notion API 2026-03-11. Neue Funktionen: Datenbanksuche über Datenquellen, Markdown-Support für Seitenoperationen, JSON-Blöcke, Dateidownloads. Wer Notion als Wissensbasis für Kunden betreibt, sollte auf v3 updaten.
- **n8n wächst auf über 1.000 Integrationen** (35+ neue native Knoten in 2026). Zapier bleibt mit 8.000+ die breitere Bibliothek, aber n8n schlägt bei Datenschutz und Self-Hosting.
- Bewertung: MCP-native n8n ist jetzt das überzeugendste Argument für lokale KI-Agents bei datenschutzsensiblen KMU-Kunden.

## 3. Lokale Modelle: Ollama und Apple Silicon

- **Apple Mac-Hardware-Refresh (25. August, Lieferung ab 22. September):** Mac mini M6, Mac Studio M5 Max und M5 Ultra angekündigt. Der M5 Ultra bietet bis zu 512 GB Unified Memory -- genug für Llama 3.3 405B auf Consumer-Hardware, erstmals ohne Serverfarm.
- **Ollama 0.19 (MLX-Preview):** Auf Apple Silicon ca. 1,6x schnellere Prompt-Verarbeitung und nahezu 2x schnellere Tokenausgabe gegenüber dem alten Metal-Backend. Aktuell noch auf Qwen3.5 beschränkt, Erweiterung auf weitere Modelle angekündigt.
- **Empfohlene Modelle nach RAM:** 16 GB -> Phi-4 oder Llama 3.2 8B; 64 GB -> Qwen 34B; 128 GB -> Llama 70B. Alle getestet auf M5, gut übertragbar auf M2/M3 mit kleinerem Durchsatz.
- Bewertung: Für Kanzleien, Arztpraxen oder Steuerberater, die keine Cloud-Datenverarbeitung wollen, wird lokale KI auf Apple-Hardware jetzt konkret empfehlenswert -- die Leistung reicht für produktive Workflows.

## 4. DSGVO / EU AI Act

- **Cyber Resilience Act -- Meldepflichten ab September 2026:** Hersteller von Produkten mit digitalen Elementen müssen aktiv ausgenutzte Schwachstellen innerhalb von 24 Stunden an ENISA melden. Betrifft KMU, die Software oder Hardware mit Netzwerkanschluss verkaufen -- nicht nur KI-Produkte.
- **Art. 50 AI Act (Transparenz) gilt seit 2. August:** Chatbots und KI-generierte Inhalte müssen als solche erkennbar sein. Das ist jetzt Pflicht, nicht mehr nur Best Practice. Wer KI-generierten Newsletter-Content oder einen Webseiten-Chatbot einsetzt, muss das kennzeichnen.
- **Digital Omnibus (seit 27. Juli in Kraft):** Hochrisiko-Fristen für HR- und Bildungssysteme auf Dezember 2027 verschoben. KMU-Sonderregelungen gelten jetzt auch für Unternehmen bis 750 Mitarbeitende (vorher: bis 249 MA). Regulatorische Sandboxes auf EU-Ebene werden ausgebaut.
- Bewertung: Die Transparenzpflicht ist jetzt die dringlichste offene Hausaufgabe für die meisten KMU-Kunden. Ein Quick-Audit der KI-Touchpoints ist sofort verkaufbar.

## 5. Förderprogramme: NRW, Bund, EU

- **NRW.BANK.Impuls KI (läuft seit 17. August):** Zuschüsse bis 25.000 EUR, 50% Förderquote. Modul A: Beratungsleistungen zur KI-Vorbereitung. Modul B: Testprojekte mit Software und Infrastruktur. Das Budget des ersten Jahres (3 Mio. EUR) kann schnell aufgebraucht sein -- Kunden jetzt ansprechen.
- **MID-Programm NRW (laufend):** Digitalisierungsgutscheine bis 15.000 EUR, kombinierbar mit Impuls KI.
- **ZIM (Bund, laufend):** Bis 310.500 EUR ohne Rückzahlung für themenoffene KI-Entwicklungsprojekte -- Goldstandard für ambitioniertere Vorhaben.
- Keine neuen Ausschreibungen diese Woche. Anlaufstelle für kostenlose Erstorientierung bleibt das Zukunftszentrum KI NRW.

## 6. Konkrete Anwendungsfälle

**Use Case 1: Lead-Qualifizierung mit n8n**
Branche: Marketing-Agenturen, Vertriebsteams, alle KMU mit Leadlisten. Ein Praxisbeispiel: 250.000 Leads automatisiert auf die Top 1% gefiltert -- Kosten unter 10 EUR/Monat für die Automatisierung. Toolstack: n8n plus CRM plus LLM-Node. Aufwand für Nachbau: 1-2 Projekttage. ROI innerhalb eines Monats bei mittlerer Leadqualität.

**Use Case 2: Transparenzpflicht-Audit (Art. 50 AI Act)**
Branche: alle KMU mit Website, Newsletter oder Kundenservice-Tools. Du prüfst, welche KI-Touchpoints ein Kunde bereits einsetzt (Chatbot, generierter Content, automatisierte Antworten) und ob diese korrekt als KI gekennzeichnet sind. Aufwand: halber Tag pro Kunde. Ergebnis: Muster-Disclosure-Texte und Checkliste für laufenden Betrieb. Jetzt besonders gut zu verkaufen, weil die Pflicht seit 6 Wochen gilt und viele Kunden das noch nicht umgesetzt haben.

---

## Das solltest du dir genauer anschauen

1. **n8n als MCP-Server:** Baue einen Demo-Workflow, der Claude Desktop als Frontend nutzt und auf Kundendaten zugreift (z.B. Notion-Wissensbasis plus CRM-Suche). Das ist das stärkste Argument für "KI ohne Cloud-Daten" -- besonders gegenüber datenschutzsensiblen Kunden. Aufwand für den Demo: ein halber Tag.

2. **NRW.BANK.Impuls KI -- jetzt Kunden ansprechen:** Modul A fördert genau das, was du lieferst: Beratung zur KI-Vorbereitung. Bei einem 25.000-EUR-Projekt übernimmt die NRW.BANK 12.500 EUR. Das Budget kann schnell weg sein -- geh aktiv auf 2-3 geeignete Bestandskunden zu.

---

## Quellen

- [n8n Docs: Changelog 2.x](https://docs.n8n.io/changelog/release-notes-2.x)
- [n8n September 2026 News -- mean.ceo](https://blog.mean.ceo/n8n-news-september-2026/)
- [n8n 2026: Neue Features -- softomatesolutions](https://www.softomatesolutions.com/blog/n8n-updates-2026-whats-new/)
- [Ollama MLX auf Apple Silicon -- Ollama Blog](https://ollama.com/blog/mlx)
- [Ollama MLX Performance -- MacRumors](https://www.macrumors.com/2026/03/31/ollama-now-runs-faster-apple-silicon-macs/)
- [Beste Ollama-Modelle Apple Silicon 2026 -- promptquorum.com](https://www.promptquorum.com/de/local-llms/best-models-apple-silicon-2026)
- [Digital Omnibus AI Act -- allbytes.de](https://www.allbytes.de/blog/eu-ai-act-digital-omnibus-kmu/)
- [Digital Omnibus Fristen Mai 2026 -- scalewise-ai.de](https://www.scalewise-ai.de/blog/2026-05-digital-omnibus-einigung-eu-ai-act-fristen)
- [EU AI Act KMU-Entlastung 2026 -- skill-sprinters.de](https://skill-sprinters.de/blog/compliance/eu-ai-act-omnibus-kmu-entlastung-2026/)
- [EU AI Act & DSGVO Leitfaden KMU -- optimusflow.consulting](https://optimusflow.consulting/blog/eu-ai-act-dsgvo-leitfaden-kmu)
- [NRW.BANK.Impuls KI -- Zukunftszentrum KI NRW](https://www.zukunftszentrum-ki.nrw/digitalisierungs-ziele-der-eu-foerderung-auch-fuer-kmus/)
- [KI-Förderung KMU 2026: Alle Programme -- hypescale.com](https://hypescale.com/de/blog/ki-foerderung-kmu-2026-programme-zuschuesse)
- [KI-Automatisierung KMU: Lead-Qualifizierung -- ki-automatix.de](https://ki-automatix.de/blog/ki-automatisierung-kmu)
- [Cyber Resilience Act -- Borncity](https://borncity.com/news/europas-datenschutz-wende-strengere-regeln-und-neue-fristen-ab-2026/)

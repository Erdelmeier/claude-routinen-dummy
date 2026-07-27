# KI-Wochenbericht -- 27. Juli 2026

Recherchezeitraum: 21.--27. Juli 2026

---

## 1. Neue KI-Tools für KMU im DACH-Raum

- Keine neuen Tools mit echtem Neuigkeitswert aus dem DACH-Markt diese Woche. Bestehende Empfehlungen bleiben stabil: Brevo für DSGVO-konformes E-Mail-Marketing (EU-Server, klare AVV-Dokumentation), Neuroflash für deutschsprachige Werbetexte, Claude oder ChatGPT für allgemeine Assistenz.
- Der wesentliche Impuls kommt nicht von neuen Tools, sondern vom Kalender: In sechs Tagen (2. August) greifen erstmals Pflichten aus dem EU AI Act. Kunden, die KI-Tools einsetzen, brauchen jetzt ein kurzes Compliance-Dokument -- das ist dein kurzfristiger Gesprächsanlass.
- Brevo empfiehlt sich weiterhin als erste Wahl gegenüber Mailchimp für DACH-KMU, da Server in der EU liegen und die DSGVO-Konformität klar dokumentiert ist.

## 2. n8n, Make, Zapier: neue AI-Nodes und Integrationen

- **n8n Release 1.107.0 (KW 30):** Fünf vorgefertigte AI-Agenten jetzt direkt aus dem AI-Agent-Node einbindbar ("pre-built agents"). Per Klick wird ein fertiger Workflow auf die Arbeitsfläche importiert. Das senkt den Einstiegsaufwand für Standard-Flows spürbar -- gut für erste Kundenprojekte.
- **Human-in-the-Loop (HITL) für AI Tool Calls:** n8n erzwingt jetzt auf Wunsch eine menschliche Freigabe, bevor ein KI-Agent bestimmte Tools ausführt (z.B. E-Mail senden, CRM-Eintrag ändern). Für KMU mit wenig KI-Erfahrung ein wichtiges Sicherheitsnetz und ein gutes Verkaufsargument gegen Bedenken.
- **Make AI Agents** mit Visual Reasoning Panel (seit Februar 2026 in Beta): Der Reasoning-Prozess des Agenten wird im Interface sichtbar. Gut für Teams ohne Programmiererfahrung, da Fehler leichter nachvollziehbar sind.
- **Zapier Agents** seit Januar 2026 aus der Beta entlassen. Bei Kunden mit vielen heterogenen Tools (Kalender, CRM, E-Commerce, Buchhaltung) ist die Zapier-Bibliothek mit 8.000+ Integrationen weiterhin das stärkste Argument.

## 3. Lokale Modelle: Ollama und Apple Silicon

- **Ollama 0.31 (29. Juni):** Aktuellste stabile Version. Multi-Token Prediction für Gemma 4 auf MLX bringt bis zu 90% mehr Geschwindigkeit bei Coding-Agenten auf Apple Silicon. Kein neues Ollama-Release in KW 30 selbst, aber das Update ist für alle M-Series-Mac-Nutzer relevant.
- **MLX-Backend (seit März 2026):** Ollama nutzt auf Apple Silicon jetzt Apples MLX-Framework statt des alten Metal-Backends von llama.cpp. Ergebnis: ca. 112 tok/s statt vorher 58 tok/s beim Dekodieren. Für datenschutzsensible KMU-Workflows (lokale Verarbeitung ohne Cloud) ist das ein echtes Argument.
- **Neue Modelle in der Ollama-Bibliothek:** Kimi K2.6, GLM-5.2, MiniMax M2 jetzt verfügbar. Alle nutzen Mixture-of-Experts-Architektur mit kleinem aktivem Parameterbudget (3--17 B Parameter pro Token). Laufen auch auf MacBooks mit 16 GB RAM -- relevant für den lokalen Einsatz in KMU ohne IT-Infrastruktur.

## 4. DSGVO / EU AI Act

- **2. August 2026 (in 6 Tagen) -- was wirklich gilt:** Nur Artikel 50 (Transparenzpflichten) tritt in Kraft. KI-generierte Texte, Deepfakes und Chatbots müssen als KI-erzeugt gekennzeichnet sein -- sichtbar, nicht im Kleingedruckten. KI-Kompetenznachweise im Team (Art. 4) sind ebenfalls Pflicht. Hochrisiko-Pflichten aus Anhang III hingegen erst ab 2. Dezember 2027.
- **Digital Omnibus (Mai 2026):** Hat die ursprünglichen August-Fristen für Hochrisiko-Systeme entschärft. Verschoben auf Dezember 2027 (Anhang III) und August 2028 (Anhang I). Entlastet die meisten KMU-Anwendungsfälle kurzfristig erheblich.
- **Nudification-Apps:** Ab 2. August verboten. Nicht für typische KMU relevant, aber gut zu wissen für Kunden im Medien- oder Kreativbereich.
- **Sofortmaßnahme für deine Kunden:** Ein kurzes internes Dokument ("KI-Nutzungsnachweis") mit Liste der eingesetzten Tools, Verantwortlichkeit und Grundlage der Datenverarbeitung reicht für die meisten KMU bis zur nächsten formalen Prüfung. Das lässt sich in einem 1-2-Stunden-Termin gemeinsam aufsetzen.

## 5. Förderprogramme: NRW, Bund, EU

- **NRW.BANK.Impuls KI (Ankündigung 16. Juli 2026, Start 17. August 2026):** Neues Zuschussprogramm für NRW-KMU. Bis zu 25.000 EUR, Förderquote 50%. Modul A fördert Beratungsleistungen zur KI-Vorbereitung, Modul B fördert konkrete Testprojekte inklusive Softwarelizenzen und Testinfrastruktur. Gesamtvolumen im ersten Jahr: 3 Millionen Euro -- Mittel können schnell vergriffen sein. Antragsstellung ab 17.8. über das Online-Portal der NRW.BANK.
- **MID-Programm NRW (seit Januar 2026):** Weiterhin aktiv, Digitalisierungsgutscheine bis 15.000 EUR. Gut kombinierbar mit dem neuen Impuls-KI-Programm.
- **ZIM (Bund):** Themenoffene Zuschusse bis 310.500 EUR für Einzelprojekte ohne Rückzahlung. Weiterhin der Goldstandard für KMU mit konkreten KI-Entwicklungsvorhaben.

## 6. Konkrete Anwendungsfälle für KMU-Kunden

**Use Case 1: Angebotsautomatisierung im Handwerk**
Branche: Sanitär/Heizung/Klima, Elektro, allgemeines Handwerk. Toolstack: n8n plus bestehendes CRM. Ein Klempnerbetrieb mit acht Mitarbeitern hat den kompletten Angebotsprozess (Anfrage erfassen, Angebot kalkulieren, verschicken, Nachfassung) in drei Wochen ohne IT-Abteilung automatisiert. Aufwand: ca. 2.000 EUR für Konzept und Implementierung. ROI unter drei Monaten durch Zeitersparnis im Büro. Jetzt besonders gut verkaufbar, weil n8n 1.107.0 vorgefertigte Agenten für Standard-Flows mitbringt.

**Use Case 2: KI-gestützte Belegerkennung für die Buchhaltung**
Branche: Alle KMU mit eigenem Buchhaltungsaufwand, 10--50 MA. Tools: Candis oder Belegfit, DATEV-Schnittstelle. Belegerkennung, automatische Buchungsvorschläge und DATEV-Export reduzieren den manuellen Aufwand von 15 auf 3 Stunden pro Woche. Beide Tools sind DSGVO-konform und in Deutschland zertifiziert. Besonders geeignet als Ergänzung zu bestehenden Steuerberater-Beziehungen, da kein Systemwechsel nötig ist.

---

## Das solltest du dir genauer anschauen

1. **NRW.BANK.Impuls KI ab 17. August:** Das Programm passt direkt auf dein Beratungsangebot. Modul A fördert Konzeptberatung zur KI-Vorbereitung -- also genau das, was du lieferst. Bei einem 25.000-EUR-Gesamtprojekt übernimmt die NRW.BANK 12.500 EUR. Jetzt Antragsunterlagen vorbereiten und Kunden gezielt ansprechen, bevor das Budget ausgeschöpft ist. Start: 17. August.

2. **EU AI Act Transparenzpflicht bis 2. August (in 6 Tagen):** Kunden mit aktiven KI-Tools (Newsletter-Generierung, Chatbot auf der Website, KI-generierte Social Posts) sind oft unvorbereitet. Ein kurzes Audit bestehender Touchpoints plus Muster-Nutzungsnachweis ist ein sofort verkäufliches Kurzpaket. Aufwand: ein halber Tag pro Kunde. Der Zeitdruck ist das Verkaufsargument.

---

## Quellen

- [NRW.BANK: Pressemitteilung Impuls KI (16. Juli 2026)](https://www.nrwbank.de/de/info-und-service/presseinformationen/2026/260716_PI-Impuls-KI.html)
- [NRW.BANK.Impuls KI: Produktseite](https://www.nrwbank.de/de/foerderung/foerderprodukte/60447/nrwbank-impuls-ki.html)
- [Zenit: NRW.BANK.Impuls KI](https://www.zenit.de/neues-foerderprogramm-nrw-bank-impuls-ki/)
- [EU AI Act: Was am 2. August 2026 wirklich gilt](https://digitalhandwerk.rocks/ki/eu-ai-act-was-am-2-august-2026-wirklich-gilt-und-was-gerade-noch-verschoben-wird/)
- [Digital Omnibus und KMU: Allbytes](https://www.allbytes.de/blog/eu-ai-act-digital-omnibus-kmu/)
- [EU AI Act nach dem Digital Omnibus: OptimusFlow](https://optimusflow.consulting/blog/eu-ai-act-compliance-vakuum-2026)
- [Ollama Blog (aktuelle Releases)](https://ollama.com/blog)
- [Ollama MLX auf Apple Silicon 2026](https://runaihome.com/blog/ollama-mlx-apple-silicon-2026/)
- [n8n Release Notes (aktuell)](https://docs.n8n.io/release-notes)
- [n8n AI Agents 2026: Kompletter Guide](https://chronexa.io/blog/n8n-ai-agents-features-2026-complete-guide)
- [n8n AI Agents in Production 2026: HITL](https://www.bovo-digital.tech/en/blog/n8n-ai-agents-production-human-in-the-loop-2026)
- [Zapier vs Make vs n8n 2026](https://aibuzz.blog/zapier-ai-vs-make-vs-n8n/)
- [KI-Automatisierung für Handwerker](https://www.terranovaai.de/blog/ki-automatisierung-fur-handwerker-welche-prozesse-sich-sofort-automatisieren-lassen)
- [KI-Agenten für KMU: Use Cases 2026](https://optimusflow.consulting/ki-agenten-kmu)
- [KI-Förderung KMU 2026: Alle Programme](https://hypescale.com/de/blog/ki-foerderung-kmu-2026-programme-zuschuesse)

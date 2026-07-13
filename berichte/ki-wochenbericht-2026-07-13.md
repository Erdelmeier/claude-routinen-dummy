# KI-Wochenbericht -- 13. Juli 2026

Recherchezeitraum: 6.-13. Juli 2026 (mit einigen relevanten Entwicklungen aus der Vorwoche, die in dieser Woche Wirkung entfalten).

---

## 1. Neue KI-Tools fuer KMU im DACH-Raum

- **Xero Ultra (ab 10. Juli):** Xero startet einen neuen Premium-Tarif fuer Unternehmen mit 20-200 Mitarbeitern, der die Luecke zwischen einfachen Buchhaltungstools und teurem ERP schliesst. KI-Integration laeuft ueber Anthropic Claude (Mehrjahresvertrag seit Maerz 2026). Seit dem 10. Juli koennen Nutzer ihre Finanzdaten direkt in Microsoft 365 Copilot einbinden und per natuerlicher Sprache in Excel, Word und PowerPoint abfragen. Bisher ist der Rollout auf Australien beschraenkt; Deutschland-Start noch offen. Fuer dich relevant als Argument beim Lexware/DATEV-Gespraech mit Kunden: zeigt die Richtung, wohin auch deutsche Anbieter muessen.
- **DSGVO-konforme Text-KI:** Claude (Anthropic), Neuroflash und DeepL Write gelten laut aktuellen Vergleichen als DSGVO-Sieger 2026, alle mit EU-Hosting oder deutschen Servern. Neuroflash ist besonders relevant fuer Marketing-KMU, da es auf deutschsprachige Werbetexte spezialisiert ist.
- **Bitkom KI-Barometer 2026:** Nur jedes vierte deutsche KMU nutzt KI aktiv -- groesste Bremsen sind fehlendes Know-how und unklare Datenschutzlage. Das ist deine Verkaufsargumentbasis.

## 2. n8n, Make, Zapier: neue AI-Nodes und Integrationen

- **n8n (Juli 2026):** Neues Release mit Verbesserungen an MCP-Nodes, die bisher dazu neigten, KI-Agenten in Reasoning-Loops zu schicken. Ausserdem: staerkere Security-Features und Workflow-Tracing fuer Debugging. Praktisch relevant fuer jede Agentenarchitektur, die du fuer Kunden baust.
- **n8n (Juni 2026):** Debugging Engine mit Execution-Replay-Modus -- Variablen in JavaScript/Python-Nodes lassen sich jetzt Schritt fuer Schritt in fehlgeschlagenen Runs nachverfolgen. Spart Stunden bei der Fehlersuche in komplexen Workflows.
- **MCP-Node-Integration:** n8n verbindet Agenten jetzt out-of-the-box mit MCP-Servern (Apify, Linear, monday.com, Notion, PostHog) ohne manuelle Konfiguration.
- **Make:** Konversationeller Workflow-Builder "Maia" (Beta) baut Szenarien aus natuerlicher Sprache. Noch nicht produktionsreif, aber zeigt die Richtung.

## 3. Lokale Modelle: Ollama und Apple Silicon

- **Ollama v0.30.8 (12. Juni):** Aktuellste Version verbessert die MLX-Engine fuer Apple Silicon deutlich -- schnellere Inferenz bei niedrigerem Speicherbedarf. Das ist die wichtigste Neuerung fuer M1/M2/M3-Nutzer. Ollama setzt jetzt auf MLX statt dem alten Metal-Backend von llama.cpp.
- **MiniMax M3 (via Ollama, ab 1. Juni):** Offen verfuegbares Flaggschiffmodell mit 1-Million-Token-Kontextfenster, nativem Bild- und Videoeingang und starken Coding-Faehigkeiten. Laeuft per Ollama auch lokal auf Apple Silicon -- fuer datenschutzsensible KMU-Workflows interessant.
- **NVIDIA Nemotron 3 Ultra (4. Juni):** Auf hochdurchsatzmassige Reasoning-Aufgaben und langlaufende Agenten-Workflows ausgelegt. Eher fuer Server-Setups, weniger fuer den Mac.

## 4. DSGVO / EU AI Act

- **Transparenzpflicht ab 2. August 2026 (in 20 Tagen):** Ab dann muessen KI-generierte Texte, Bilder, Videos und Audioinhalte sichtbar gekennzeichnet werden. Chatbots muessen Nutzer beim ersten Kontakt als KI kenntlich machen -- nicht im Kleingedruckten, sondern im sichtbaren UI. Das betrifft jeden KMU-Kunden, der einen KI-Chatbot oder KI-generierten Social-Content einsetzt.
- **Bussgeld-Erleichterungen:** KMU erhalten 50% Bussgelderlass, Mikrounternehmen 75%. Trotzdem: bis zu 15 Mio. Euro oder 3% des Jahresumsatzes als Obergrenze.
- **Klarstellung "Safety Component":** KI, die Nutzer nur unterstuetzt oder Leistung optimiert, faellt nicht automatisch unter Hochrisiko -- solange kein Ausfall Gesundheits- oder Sicherheitsrisiken erzeugt. Entlastet viele typische KMU-Anwendungen.
- **Neue Kategorie "Small Mid-Caps":** Etwas groessere Unternehmen (bisher zu gross fuer KMU-Definition) erhalten jetzt erstmals dieselben Erleichterungen wie KMU.

## 5. Foerderprogramme: Bund, Land NRW, EU

- **EU Cascade Calls (Zukunftszentrum KI NRW):** Aktuell fuenf aktive Calls mit 100%-Foerderung bis 300.000 Euro fuer KMU -- ohne Konsortiumspartner, mit deutlich geringerem Antragsaufwand als regulaere Horizon-Europe-Projekte. Themenfelder: KI/Daten, Mobilitaet, Energie. Einige Deadlines fallen noch in den Juli. Direktlink: [zukunftszentrum-ki.nrw](https://www.zukunftszentrum-ki.nrw/neue-eu-cascade-calls-100-prozent-foerderung-fuer-kmu-ohne-den-ueblichen-antragsaufwand/)
- **MID-Programm NRW (seit Januar 2026):** NRW.Bank verwaltet Digitalisierungsgutscheine: bis 15.000 Euro fuer digitale Produkte/IT-Sicherheit, bis 48.000 Euro fuer Innovation (Hochschulabsolventen-Einstellung). Gut kombinierbar mit deinen Beratungsprojekten.
- **ZIM (Bund):** Themenoffene, nicht rueckzahlbare Zuschuesse bis 310.500 Euro fuer Einzelprojekte. Goldstandard fuer KI-Entwicklungsvorhaben.

## 6. Konkrete Anwendungsfaelle fuer KMU-Kunden

**Use Case 1: Vertriebsautomatisierung Handwerk/Dienstleistung**
Branche: Handwerk, Facility Management, B2B-Dienstleister. Toolstack: n8n + Pipedrive + DocuSign. Angebotserstellung, Nachfassung und Vertragsversand werden automatisiert. Dokumentierter Aufwand in Praxisprojekten: 250 Minuten Einsparung pro Deal. Implementierungsaufwand: 3-5 Tage. Guter Einstieg, da der ROI innerhalb von 6-8 Wochen sichtbar wird.

**Use Case 2: KI-Kennzeichnung als Compliance-Service**
Timing: Die EU-Deadline am 2. August trifft viele Kunden unvorbereitet. Kurzpaket: Audit bestehender KI-Touchpoints (Chatbot, Social Posts, Newsletter), Einbau sichtbarer Kennzeichnung, kurze Mitarbeiterschulung. Aufwand: 1-2 Tage pro Kunde. Verkaufbar als "AI Act Readiness Check" -- der Zeitdruck macht das Angebot von selbst.

---

## Das solltest du dir genauer anschauen

1. **EU Cascade Calls mit Juli-Deadline:** Einige Fristen laufen noch diesen Monat. Pruefe konkret die Liste auf [zukunftszentrum-ki.nrw](https://www.zukunftszentrum-ki.nrw/neue-eu-cascade-calls-100-prozent-foerderung-fuer-kmu-ohne-den-ueblichen-antragsaufwand/) -- 100%-Foerderung bei reduziertem Antragsaufwand ist selten.
2. **AI Act Readiness Check als Sofortprodukt:** Der 2. August ist in 20 Tagen. Die meisten deiner KMU-Kunden haben keine KI-Kennzeichnung und keinen Plan. Ein schnelles 1-Tages-Audit laesst sich sofort verkaeufen und liefert echten Mehrwert.

---

## Quellen

- [Xero Ultra: KI-Buchhaltung fuer 20-200-Mitarbeiter-Firmen ab Juli](https://borncity.com/news/xero-ultra-ki-buchhaltung-fuer-20-200-mitarbeiter-firmen-ab-juli/)
- [Xero Ultra: Fuenf-Millionen-Kundenplattform erhaelt KI-Agenten](https://borncity.com/news/xero-ultra-fuenf-millionen-kundenplattform-erhaelt-ki-agenten/)
- [n8n 2026 Updates: Release Notes, AI Agents & MCP Integration Guide](https://nodesify.com/blog/n8n-workflow-automation-guide-2026)
- [n8n Release Notes July 2026](https://releasebot.io/updates/n8n)
- [Ollama MLX on Apple Silicon in 2026](https://runaihome.com/blog/ollama-mlx-apple-silicon-2026/)
- [Ollama Juni 2026 Update: v0.30.8](https://www.promptquorum.com/de/local-llms/top-open-source-models-ollama)
- [Kennzeichnungspflicht fuer KI-Inhalte gilt ab August 2026 (Haufe)](https://www.haufe.de/recht/kanzleimanagement/kennzeichnungspflicht-fuer-ki-inhalte-gilt-ab-august-2026_222_681220.html)
- [KI-Verordnung: Neue Transparenzpflichten ab August 2026 (IHK Koeln)](https://www.ihk.de/koeln/hauptnavigation/digitalisierung-und-innovation/digitalisierung/transparenzpflichten-nach-der-ki-verordnung-7100068)
- [EU AI Act 2026: Was der Digital Omnibus fuer den Mittelstand aendert](https://www.allbytes.de/blog/eu-ai-act-digital-omnibus-kmu/)
- [Neue EU-Cascade-Calls: 100 Prozent-Foerderung fuer KMU (Zukunftszentrum KI NRW)](https://www.zukunftszentrum-ki.nrw/neue-eu-cascade-calls-100-prozent-foerderung-fuer-kmu-ohne-den-ueblichen-antragsaufwand/)
- [KI-Foerderung 2026: Alle Programme & Zuschuesse fuer KMU](https://hypescale.com/de/blog/ki-foerderung-kmu-2026-programme-zuschuesse)
- [KI-Agenten fuer KMU: 7 Use-Cases & Kosten 2026](https://optimusflow.consulting/ki-agenten-kmu)
- [Bitkom KI-Barometer 2026](https://skill-sprinters.de/blog/praxis/bitkom-ki-barometer-2026-jedes-vierte-kmu-bremsen/)

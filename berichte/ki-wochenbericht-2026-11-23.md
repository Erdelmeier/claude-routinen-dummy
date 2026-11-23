# KI-Wochenbericht -- 23. November 2026

Recherchezeitraum: 16.--23. November 2026

---

## 1. Neue KI-Tools für KMU im DACH-Raum

- **Keine Neuerscheinungen mit belastbarem Datum in dieser Woche.** Brevo, neuroflash, sevDesk und Candis entwickeln ihre Plattformen weiter, ohne publizierte Sprung-Updates in KW 47.
- **neuroflash (Hamburg) bleibt DACH-Empfehlung für KI-Marketing.** Datenschutzargument hält: EU-Server, kein US-Daten-Transfer. Für KMU ohne eigene DSGVO-Prüfung der sicherste Einstieg in KI-Texterstellung.
- **Lexware Office und sevDesk** dominieren weiterhin die KI-Buchhaltung für KMU. Automatische Kontierung nach 50 bis 100 Belegen bei 85 bis 95 Prozent Trefferquote (Herstellerangabe, nicht unabhängig geprüft). Kein neues Release diese Woche.

## 2. n8n, Make, Zapier

- **Keine neuen AI-Nodes oder Integrationen** mit Datum in der aktuellen Woche gefunden.
- **Make AI Agents in open beta (laufend).** Make's Maia-Assistent baut Automatisierungs-Szenarien aus natürlichsprachigen Prompts. Für KMU noch nicht produktionsreif, aber zum Testen geeignet. Einzug in Beta bedeutet: noch keine SLA-Garantien.
- **Zapier Agents weitet Beta aus.** Zapier hat MCP-Konnektivität neben dem Copilot-Builder hinzugefügt. Für KMU mit Zapier-Stack noch nichts Handlungsrelevantes -- beobachten.
- **n8n:** MCP-Server-Integration seit April 2026 in public preview, kein neues Major-Release diese Woche. Wer noch nicht auf 2.43.5 oder höher aktualisiert hat (Oktober-Sicherheitsupdates): jetzt nachholen.

## 3. Lokale Modelle (Ollama / Apple Silicon)

- **Ollama v0.40.17 bringt Inkling 2 Mini (21. November 2026).** Ein kompaktes Text-und-Bild-Modell, das ausschliesslich auf Apple Silicon laeuft. Start: `ollama run inkling-2-mini`. Fuer KMU-Demo-Setups mit Mac-Hardware sofort einsetzbar.
- **Ripple Preview 65B im stabilen Release (v0.40.16).** Ein 65-Milliarden-Parameter-Coding-Modell von Ricursive Intelligence -- relevant fuer Software-Kunden, die lokal entwickeln wollen. Braucht mindestens 64 GB RAM.
- **Qwen3.8 Flash Next spart ~27 GB RAM auf Apple Silicon.** Wer bisher keinen 32-GB-Mac hatte, um Qwen3.8 lokal zu betreiben, profitiert jetzt moeglicherweise. Ollamaq3.8:27b laeuft laut Drittnachweise bei rund 18 GB.
- **MLX-Backend (prerelease):** Concurrent Generation fuer MLX aktiviert -- mehrere gleichzeitige Anfragen an ein lokales Modell moeglich. Noch als Release Candidate (rc0), nicht fuer Produktion geeignet.
- Aktuelle Modell-Empfehlungen je RAM unveraendert: 8 GB -> Phi-4 Mini oder Llama 3.2 3B; 16 GB -> Qwen3.8 27B Flash Next; 32 GB+ -> Ripple Preview oder Gemma 4 26B.

## 4. DSGVO / EU AI Act

- **Frist 2. Dezember 2026 naht.** Bestandssysteme, die vor dem 2. August 2026 im Einsatz waren, muessen bis zum 2. Dezember 2026 die Transparenzanforderungen (Art. 50) erfullen. Das ist in neun Tagen. Wer KMU-Kunden mit laengerem KI-Einsatz betreut: jetzt pruefen, ob sichtbare Hinweise auf KI-generierte Inhalte vorhanden sind.
- **AI-Literacy-Pflicht (Art. 4) noch oft ignoriert.** Fuer alle Unternehmen, unabhaengig von der Groesse, gilt: Mitarbeitende muessen nachweisbar im KI-Umgang geschult sein. Eine Teilnahmeliste eines einstuendigen Workshops reicht fuer niedrige Risikostufen. Kein neuer Leitfaden diese Woche, aber die Frist laeuft.
- **Hochrisiko-Pflichten (Anhang III) weiterhin auf Dezember 2027 verschoben** (Digital Omnibus, VO (EU) 2026/1744). Fuer KMU ohne Hochrisiko-KI keine Aenderung.
- **Keine neuen Bussgelder oder Aufsichtsmassnahmen publiziert** in KW 47.

## 5. Foerderprogramme (NRW, Bund, EU)

- **NRW.BANK.Impuls KI (laufend, aber Budget unter Druck).** Bis 25.000 Euro Zuschuss, 50 Prozent Foerderquote, Gesamtbudget 3 Mio. Euro. Laufzeit seit August 2026 -- ein erheblicher Teil des Budgets duerfte abgeflossen sein. Modul A (konzeptionelle Beratung) ist der schnellste Einstieg und hat geringere Anforderungen als Modul B.
- **MID-Digitalisierung (laufend bis Ende 2029).** Bis 15.000 Euro bei 50 Prozent Foerderquote, Vergabe per Losverfahren. KI-Loesungen ausdruecklich foerderfaehig. Fuer NRW-KMU eine Alternative zum Impuls-KI-Programm, wenn das Budget dort erschoepft ist.
- **EU Digital Europe (63,2 Mio. Euro KI-Aufruf).** Einreichungsfrist war 1. Oktober 2026 -- dieser Aufruf ist geschlossen. Nachfolge-Calls noch nicht publiziert.
- **go-digital BMWK (laufend).** Bis 16.500 Euro, 50 Prozent Foerderquote, deckt digitalisierte Geschaeftsprozesse einschliesslich KI-Einfuehrung ab.

## 6. Konkrete Anwendungsfaelle

**Use Case 1: Lokale Rechnungsprufung mit Inkling 2 Mini**
Branche: Handwerk, Bau, Dienstleister mit Eingangsrechnungsvolumen. Seit v0.40.17 laeuft Inkling 2 Mini auch auf Apple-Silicon-Macs mit 16 GB RAM. Das Modell versteht Bilder und PDFs -- Rechnungen einlesen, Betrag/Lieferant/Position extrahieren, direkt in eine Tabelle schreiben, ohne dass Daten das Unternehmen verlassen. Einführungsaufwand: 1 Tag plus Testphase. Laufende Kosten: Strom und Mac-Hardware, kein API-Vertrag notwendig. Förderfähig über NRW.BANK.Impuls KI Modul B.

**Use Case 2: KI-Transparenznachweis als Einsteigerprojekt**
Branche: alle KMU mit Website, Chatbot oder KI-gestutzten E-Mails. Hintergrund: 2.-Dezember-Frist (AI Act Art. 50). Konkreter Auftrag: kurzes Audit aller KI-Tools im Einsatz, sichtbarer Disclaimer auf Chatbot und Website, ein einseitiges Inventardokument. Aufwand: ein halber Tag. Verkaufsargument fuer Erstgespraech: "Pruefen wir gemeinsam, ob ihr bis 2. Dezember compliant seid."

---

## Das solltest du dir genauer anschauen

1. **2.-Dezember-Frist (AI Act Art. 50) -- konkret handeln.** Neun Tage bis zur Pflicht fuer Bestandssysteme. Ruf drei bis fuenf NRW-Kunden an, die du schon mit KI-Tools betreust, und pruefe, ob Transparenzhinweise sichtbar sind. Das ist ein konkreter Einsteiger-Auftrag ohne grosse technische Huerde. [EU AI Act Leitfaden KMU -- ki-compliance-kit.de](https://ki-compliance-kit.de/ai-act-leitfaden)

2. **Ollama 0.40.17 + Inkling 2 Mini testen.** Das neue Modell laeuft auf 16-GB-Apple-Silicon-Macs und versteht Bilder -- das ist ein echter Demo-Fortschritt gegenueber dem letzten Bericht. Wenn du Kunden mit M2 oder M3 MacBook Pro hast: Rechnungslesedemo in einem Nachmittag aufgebaut. [Ollama Releasebot -- releasebot.io](https://releasebot.io/updates/ollama)

---

## Quellen

- [Ollama v0.40.16/0.40.17 Release Notes -- Guth Labs (10.11.2026)](https://guthlabs.ai/news/story/ollama-04016-04017-preview-2026-11-10)
- [Ollama Release Notes November 2026 -- releasebot.io](https://releasebot.io/updates/ollama)
- [Ollama für Mac: Text-to-Speech-Unterstutzung -- 9to5Mac (26.10.2026)](https://9to5mac.com/2026/10/26/ollama-for-mac-gains-support-for-local-text-to-speech-models/)
- [Best Ollama Models 2026 -- morphllm.com](https://www.morphllm.com/best-ollama-models)
- [EU AI Act Leitfaden KMU 2026 -- ki-compliance-kit.de](https://ki-compliance-kit.de/ai-act-leitfaden)
- [EU AI Act und DSGVO fuer KMU -- optimusflow.consulting](https://optimusflow.consulting/blog/eu-ai-act-dsgvo-leitfaden-kmu)
- [NRW.BANK.Impuls KI Forderung -- 40komma6.de](https://www.40komma6.de/leistungen/ki-foerderung-nrw)
- [KI-Forderung NRW 2026 -- procevia.de](https://procevia.de/blog/ki-foerderung-nrw-prozessdigitalisierung/)
- [KI-Forderung 2026 Ubersicht -- thekey.academy](https://www.thekey.academy/de/wissen/ki-foerderprogramme-kmu)
- [n8n vs Make vs Zapier 2026 -- flowmondo.com](https://www.flowmondo.com/article/n8n-vs-zapier-vs-make)
- [Make vs n8n vs Zapier -- neura.market (11.2026)](https://www.neura.market/blog/zapier-vs-make-vs-n8n-the-2026-ai-automation-showdown)
- [KI-Automatisierung KMU -- ucar-solutions.de](https://ucar-solutions.de/allgemein/ki-automatisierung-kmu-praxisbeispiele)

# KI-Wochenbericht -- 28. September 2026

Recherchezeitraum: 21.--28. September 2026

---

## 1. Neue KI-Tools für KMU im DACH-Raum

- **Kein grösserer Neueinsteiger diese Woche:** Die DACH-KI-Tool-Landschaft für KMU hat in den letzten 7 Tagen keinen relevanten Neustart gebracht. Laufende Tools wie Lexoffice, sevDesk, Brevo und Neuroflash werden weiterentwickelt, aber ohne sprunghafte Updates.
- **Candis und Moss weiter auf Wachstumskurs:** Beide Buchhaltungs-KI-Tools gewinnen an Marktdurchdringung im 10--50-Personen-Segment. Candis hat automatisches SEPA-Zahlungsmanagement mit KI-Plausibilitätsprüfung -- kein neues Feature, aber in Kundengesprächen noch unterbekannt.
- **Bitkom-Zahl (aktuell):** 41 Prozent der deutschen Unternehmen nutzen KI aktiv -- eine Verdopplung innerhalb eines Jahres. Mittelstand hinkt noch hinterher. Das ist dein Hauptargument in der Erstberatung.
- Bewertung: Keine News dieser Woche, die sofortiges Handeln erfordern. Wer Buchhaltungskunden hat, sollte Candis/Moss einmal kurz vorführen -- das sitzt in 15 Minuten.

## 2. n8n, Make, Zapier: neue AI-Nodes und Integrationen

- **n8n: Agents-Feature jetzt offiziell (diese Woche breit kommuniziert):** n8n hat das neue Agents-System aus dem Beta-Status genommen. Kern: Ein Agent wird als eigenständiges Projekt-Objekt erstellt -- du wählst ein Modell, schreibst Anweisungen, hängst Tools und bestehende Workflows dran. Einstiegspunkte sind Slack, Telegram oder Linear. Derselbe veröffentlichte Agent bedient mehrere Eingangskanäle gleichzeitig, während der Entwurf getrennt bleibt. Das ist der grösste n8n-Sprung seit dem 2.0-Release im Januar.
- **n8n MCP jetzt per API prüfbar:** Agent-Test-Ausführungen sind jetzt über das MCP-Protokoll zugänglich -- Schritte und Tool-Aufrufe bleiben gespeichert und lassen sich nachvollziehen. Praktisch für die Fehlersuche in komplexen Workflows.
- **Make Maia -- stabil:** Keine neuen Funktionen diese Woche, aber Maia (AI-Scenario-Builder) ist seit der Stabilisierung vor zwei Wochen in der Praxis deutlich zuverlässiger. Für technisch schwache Kunden weiterhin der beste Einstieg.
- **Zapier MCP -- keine Aenderung:** Zapier's MCP-Integration bleibt träge bei Aktionsketten über 3 Schritte. Breite des App-Katalogs (9.000+ Apps) schlägt n8n bei nicht-technischen Anwendern, Zuverlässigkeit noch nicht auf Produktionsniveau.
- Bewertung: Das neue Agents-System in n8n ist sofort verkaufbar als "dein eigener KI-Mitarbeiter in Slack oder Telegram". Konkrete Demo vorbereiten -- du kannst in 2 Stunden einen Prototyp aufbauen.

## 3. Lokale Modelle: Ollama und Apple Silicon

- **Ollama 0.40.0-rc0 (veröffentlicht 25. September 2026):** MLX-Unterstützung auf Apple Silicon läuft jetzt standardmässig -- kein manuelles Aktivieren mehr nötig. Wichtiger Vorbehalt: MLX aktiviert sich nur automatisch ab 32 GB Unified Memory; Macs mit 16 GB oder weniger fallen auf den älteren Metal-Engine zurück (weiterhin nutzbar, aber langsamer).
- **Qwen3 auf Apple Silicon schneller:** Qwen 3.8 prompt processing wurde explizit optimiert. Wer mit 32-GB-M3-Konfigurationen arbeitet, merkt das sofort bei mehrstufigen Aufgaben.
- **Gemma 4 -- bessere Bildauflösung:** Gemma 4 wählt auf Apple Silicon jetzt automatisch die beste Bildauflösung pro Bild -- relevant für Kunden, die Rechnungen, Fotos oder Grafiken lokal auswerten wollen.
- **Nemotron H Vision (neu in dieser Version):** MLX-Unterstützung für Nemotron H Vision auf Apple Silicon hinzugekommen. Ein weiteres leistungsfähiges Multimodal-Modell, das vollständig lokal läuft.
- Bewertung: Das Update ist sofort nutzbar. Wer Kunden mit einem 32-GB-M-Chip-Mac betreut, sollte Ollama auf 0.40.0 updaten -- bessere Geschwindigkeit ohne Konfigurationsaufwand. Für 16-GB-Macs: Erwartungen realistisch halten.

## 4. DSGVO / EU AI Act

- **EU AI Act Omnibus-Aenderung (Verordnung 2026/1744):** Die ursprüngliche KI-Verordnung wurde durch den EU-Omnibus von 2026 an einem Punkt verschärft: Die Liste verbotener KI-Systeme wurde um Systeme zur Erzeugung oder Manipulation nicht einvernehmlicher intimer Darstellungen erweitert. Für das KMU-Umfeld kein unmittelbarer Handlungsbedarf, aber relevant für Kunden in Medienproduktion oder Content-Erstellung.
- **Hochrisiko-Frist auf Dezember 2027 verschoben:** Gute Nachricht für KMU: Die Anforderungen an Hochrisiko-KI-Systeme wurden durch die Omnibus-Revision auf Dezember 2027 verschoben. Wer keine Hochrisiko-KI entwickelt oder vertreibt, hat mehr Vorlauf.
- **Transparenzpflichten (Art. 50) weiterhin aktiv:** Seit August 2026 in Kraft -- Chatbots und KI-Inhalte müssen kenntlich gemacht werden. Noch keine Bussgeldfälle publiziert, aber Behörden sammeln Fallmaterial. Wer das noch nicht umgesetzt hat: Ein kurzer Hinweis auf der Website oder im Chatbot-Interface reicht.
- **EDSA-Konsultation zu KI-Profiling (Frist 15. Oktober):** Entwurf zu Einwilligungspflichten bei KI-gestütztem Profiling und Lead-Scoring ist noch offen. Für KMU, die personalisierten KI-Output einsetzen, lohnt ein Blick auf den Entwurf.
- Bewertung: Keine Panik, aber Transparenzpflicht jetzt umsetzen -- das ist in 30 Minuten erledigt. Für Kunden mit Lead-Scoring: EDSA-Entwurf auf dem Schirm behalten.

## 5. Förderprogramme: NRW, Bund, EU

- **NRW.BANK.Impuls KI (seit 17. August -- jetzt 6 Wochen alt):** Förderanträge bis zu 25.000 EUR Zuschuss, 50% Förderquote. Modul A (Beratungsleistungen) deckt genau das ab, was du lieferst. Das Budget von 3 Mio. EUR ist endlich -- der Durchlauf beschleunigt sich. Antrag digital über das NRW.BANK-Kundenportal.
- **MID-Digitale Prozesse: Antragsstopp für 2026:** NRW.BANK hat wegen grosser Nachfrage Anträge für das Jahr 2026 gestoppt. Kunden, die darauf spekuliert haben, müssen auf 2027 warten oder auf NRW.BANK.Impuls KI ausweichen.
- **ZIM Bund (laufend):** Keine neue Ausschreibungsrunde. Laufende Runde für KI-Entwicklungsprojekte noch offen, bis 310.500 EUR ohne Rückzahlung.
- Keine neuen EU- oder Bundesförderungen diese Woche. Zukunftszentrum KI NRW bleibt kostenlose Erstanlaufstelle.
- Bewertung: Das Zeitfenster für NRW.BANK.Impuls KI wird enger. Wenn du noch Kunden hast, die zögern, jetzt aktiv werden.

## 6. Konkrete Anwendungsfälle

**Use Case 1: n8n-Agent als Kundenservice-Erstlinie (Einzelhandel, E-Commerce)**
Branche: Onlineshops und stationärer Einzelhandel mit hohem Anfragevolumen. Umsetzung: Ein n8n-Agent (neues Agents-System) nimmt Kundenanfragen via Telegram oder Website-Chat entgegen, zieht Bestellstatus aus dem Shop-System und beantwortet FAQs aus einer Wissensdatenbank. Unklare Fälle werden an einen Menschen eskaliert mit vollständigem Kontext. Aufwand Erstaufbau: 2--4 Projekttage. Monatliche Einsparung: 3--8 Stunden Kundenkommunikation pro Woche. Förderbar über NRW.BANK.Impuls KI Modul B.

**Use Case 2: Lokale Rechnungsprüfung mit Ollama + Gemma 4 (Handwerk, Bau)**
Branche: Handwerksbetriebe und Bauunternehmen mit vielen Lieferantenrechnungen. Umsetzung: Gemma 4 läuft lokal via Ollama auf einem Mac mit 32 GB RAM, liest Rechnungs-PDFs aus, extrahiert Betrag, Lieferant und Position und schreibt das Ergebnis in eine Tabelle oder direkt ins Buchhaltungstool. Keine Daten verlassen das Unternehmen -- ideal für datenschutzsensible Kunden. Aufwand: 1--2 Projekttage für Integration und Test.

---

## Das solltest du dir genauer anschauen

1. **n8n Agents als Verkaufspaket:** Das neue Agents-System in n8n ist jetzt produktionsreif. Schnür ein konkretes Angebot: "KI-Erstlinie für Kundenanfragen in 3 Tagen", gefördert über NRW.BANK.Impuls KI. Das ist der stärkste Kombinations-Pitch, den du gerade hast -- neues Feature, sofortiger Nutzen, Förderung übernimmt die Hälfte.

2. **Ollama-Update für Bestandskunden mit Apple Silicon:** Wenn du Kunden betreust, die bereits lokal mit Ollama arbeiten, ist das Update auf 0.40.0 ein kurzes Service-Touchpoint -- du kannst gleichzeitig auf neue Möglichkeiten (Gemma 4 für Belege, Nemotron H Vision) hinweisen und einen Folgeauftrag anbahnen.

---

## Quellen

- [Ollama 0.40.0-rc0 Release -- Freedom.Tech (25. Sept. 2026)](https://freedom.tech/posts/2026-09-25-ollama-0-40-0/)
- [Ollama September 2026 Release Notes -- Releasebot](https://releasebot.io/updates/ollama)
- [n8n September 2026 Updates -- Releasebot](https://releasebot.io/updates/n8n)
- [n8n Agents: Was sich geändert hat -- Kingy AI](https://kingy.ai/news/n8n-agents-2026-what-changed-cost-controls/)
- [n8n 2026 neue Features -- softomatesolutions](https://www.softomatesolutions.com/blog/n8n-updates-2026-whats-new/)
- [EU AI Act Omnibus Aenderung -- ai-act-law.eu](https://ai-act-law.eu/de/)
- [EU AI Act & DSGVO Leitfaden KMU -- optimusflow.consulting](https://optimusflow.consulting/blog/eu-ai-act-dsgvo-leitfaden-kmu)
- [EU AI Act Mittelstand Fristen 2026 -- sage.com](https://www.sage.com/de-de/blog/eu-ai-act-2026-fuer-den-mittelstand-fristen-pflichten-und-compliance/)
- [NRW.BANK.Impuls KI -- Foerdergeld.org](https://www.xn--frdergeld-07a.org/news-meldung/neues-foerderprogramm-in-nrw-bis-zu-25000-euro-zuschuss-fuer-die-vorbereitung-von-ki-projekten/)
- [KMU-Foerderungen 2026 -- kmu-heute.de](https://www.kmu-heute.de/kmu-foerderungen-2026-ausschreibungen-voraussetzungen-und-antragsstellung/)
- [KI-Agenten fuer KMU: Use Cases 2026 -- optimusflow.consulting](https://optimusflow.consulting/ki-agenten-kmu)
- [Zapier vs n8n KI-Workflows -- IntuitionLabs](https://intuitionlabs.ai/articles/zapier-vs-n8n-ai-workflows)
- [Ollama MLX Mac Setup -- switchingtomac.com](https://www.switchingtomac.com/ollama-mlx-mac-setup-guide/)

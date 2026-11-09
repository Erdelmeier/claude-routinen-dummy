# KI-Wochenbericht -- 9. November 2026

Recherchezeitraum: 2.--9. November 2026

---

## 1. Neue KI-Tools für KMU im DACH-Raum

- **Privatemode AI im Test (t3n, diese Woche):** Ein verschlüsselter KI-Chatbot, der laut Hersteller Anfragen clientseitig verschlüsselt, bevor sie den Server erreichen. Für datenschutzsensible KMU-Kunden potenziell interessant. Bewertung: Früh -- kein DSGVO-Zertifikat, keine unabhängige Prüfung bestätigt. Beobachten, nicht empfehlen.
- **Keine DACH-Neueinsteiger mit belastbarem Datum diese Woche.** Brevo, Neuroflash, sevDesk und Candis entwickeln ihre Tools weiter, ohne publizierte Sprung-Updates.
- **Claude Code Sicherheitsvorfall (Heise, diese Woche):** Eine offizielle Claude-Code-Erweiterung für den IDE Cursor wurde mit Malware manipuliert -- betrifft Entwickler, nicht KMU-Endnutzer. Bewertung: Wer Cursor plus Claude Code nutzt, Extension manuell prüfen und auf aktuelle Version aktualisieren.

## 2. n8n, Make, Zapier

- **Keine neuen AI-Nodes oder Integrationen** mit Datum in der aktuellen Woche gefunden.
- **Nachzügler Oktober -- n8n Sicherheitshinweis:** 15 Advisories vom 14. Oktober, vier davon CVSS "high". Self-hosted-Instanzen sollten jetzt auf 2.43.5 oder höher aktualisiert sein. Falls noch nicht geschehen, ist das dringend.
- **Make Prompt Caching stabil (seit 9. Oktober):** AI-Agents in Make profitieren von Prompt Caching -- wiederholte Anfragen mit gleichen System-Prompts werden deutlich günstiger. Für kostenintensive Automatisierungen direkt messbar.
- Bewertung: Diese Woche ruhig. Wer n8n self-hosted betreibt und das Oktober-Update verpasst hat, muss jetzt handeln.

## 3. Lokale Modelle (Ollama / Apple Silicon)

- **Keine relevanten Änderungen diese Woche.** Letzter bekannter Stand: Ollama 0.40.0 (Oktober) mit automatischer MLX-Aktivierung ab 32 GB RAM. Für 16-GB-Macs weiterhin Metal-Engine.
- Hinweis für Bestandskunden: M2 Pro (200 GB/s Speicherbandbreite) übertrifft M3 Pro (150 GB/s) bei lokalen Modellen -- relevant, wenn Kunden über einen Mac-Kauf nachdenken.
- Aktuelle Modell-Empfehlungen je RAM: 8 GB -> Llama 3.2 3B oder Phi-4 Mini; 16 GB -> Qwen 3.5 9B; 32 GB+ -> Qwen 3.5 32B oder Gemma 4.

## 4. DSGVO / EU AI Act

- **Transparenzpflicht (Art. 50) seit 2. August 2026 in Kraft.** KI-Chatbots und KI-generierte Inhalte müssen als solche erkennbar sein. Keine neuen Bußgelder publiziert -- aber Aufsichtsbehörden sammeln aktiv Fallmaterial. Wer das noch nicht umgesetzt hat: Ein sichtbarer Hinweis im Chat oder auf der Website reicht für einfache Anwendungen.
- **Digital Omnibus:** Hochrisiko-Pflichten (Anhang III) auf Dezember 2027 verschoben. Für KMU, die keine Hochrisiko-KI entwickeln, keine Änderung zum letzten Bericht.
- **KI-Kompetenzpflicht (Art. 4):** Unternehmen müssen nachweisen, dass Mitarbeitende ausreichend geschult sind. Kein neuer Leitfaden diese Woche, aber ein kurzer interner Nachweis (z.B. Teilnahmeliste eines KI-Workshops) reicht für niedrige Risikostufen.

## 5. Förderprogramme (NRW, Bund, EU)

- **KI-Nation 2030 -- Bundesregierung (2. November 2026):** Der Ergebnisbericht der KI-Taskforce wurde beim Digitalgipfel Berlin vorgestellt. Ziel: 55 Prozent der KMU nutzen KI bis 2030. Konkret geplant: ein konsolidiertes Förderprogramm "KI stärkt den Mittelstand" und die Prüfung eines KI-Gutschein-Modells für KMU -- analog zu bereits beschlossenen Gemeinde-Gutscheinen. Bewertung: Absichtserklärung, noch kein offener Call. Trotzdem beobachten -- Gutscheinmodell könnte die Einstiegshürde für Erstberatung drastisch senken.
- **NRW.BANK.Impuls KI (laufend):** Bis 25.000 Euro Zuschuss, 50 Prozent Förderquote, Bewerbung über das NRW.BANK-Kundenportal. Gesamtbudget 3 Mio. Euro -- nach 12 Wochen Laufzeit dürfte ein Teil abgeflossen sein. Keine neuen EU- oder Bundesaufrufe diese Woche.

## 6. Konkrete Anwendungsfälle

**Use Case 1: Angebotskalkulation im Handwerk**
Branche: Elektro, SHK, Maler. KI erstellt Angebotsentwurf aus Aufmaß-Fotos und Standardleistungsverzeichnis. Aufwand sinkt von 45 auf ca. 10 Minuten pro Angebot. Einführungsaufwand: 1--2 Tage. Laufende Kosten: ca. 200--400 Euro/Monat. Förderfähig über NRW.BANK.Impuls KI Modul B.

**Use Case 2: Lokale Rechnungsprüfung mit Ollama**
Branche: Handwerk und Bau mit hohem Eingangsrechnungsvolumen. Ollama + Qwen 3.5 9B läuft lokal, liest PDFs, extrahiert Betrag, Lieferant und Position in eine Tabelle. Keine Daten verlassen das Unternehmen -- ideal für datenschutzsensible Kunden. Einführungsaufwand: 1--2 Projekttage. Rechenbeispiel: 15 Fehler/Monat à 120 Euro, KI reduziert Fehler um 60 Prozent = 1.080 Euro Ersparnis/Monat.

---

## Das solltest du dir genauer anschauen

1. **KI-Gutschein-Modell aus dem Bund-Bericht vom 2. November** -- wenn das umgesetzt wird, ändert sich dein Verkaufsargument für KMU-Erstberatung grundlegend. Lass den Plan auf deinem Radar und melde dich beim Zukunftszentrum KI NRW für Updates. [Bundesregierung KI-Nation 2030](https://www.bundesregierung.de/resource/blob/992814/2459514/b8518975df987ac1cfdc1fc5b655efb3/2026-11-02-ki-data.pdf)

2. **NRW.BANK.Impuls KI -- Budget läuft ab.** 12 Wochen laufen, Gesamtbudget 3 Mio. Euro. Wenn du NRW-Kunden hast, die noch zögern, jetzt aktiv werden -- Modul A (Konzeptberatung) ist der einfachste Einstieg. [nrwbank.de/impuls-ki](https://www.nrwbank.de/de/unternehmen/nrw-bank-innovationspartner/aktuelles/nrw.bank.impuls.ki)

---

## Quellen

- [Bundesregierung: KI-Taskforce Ergebnisbericht "KI-Nation 2030" (02.11.2026)](https://www.bundesregierung.de/resource/blob/992814/2459514/b8518975df987ac1cfdc1fc5b655efb3/2026-11-02-ki-data.pdf)
- [t3n: Digitalgipfel 2026 Kommentar (07.11.2026)](https://t3n.de/news/digitalgipfel-2026-ki-weltspitze-deutschland-kommentar-1771341)
- [KI-News KW 44 -- roover.de](https://roover.de/ki-news-kw-44-2026/)
- [Make + n8n + Zapier Updates Oktober 2026 -- nex-automations.com](https://nex-automations.com/blog/automation-platform-updates)
- [NRW.BANK.Impuls KI Pressemitteilung](https://www.nrwbank.de/de/info-und-service/presseinformationen/2026/260716_PI-Impuls-KI.html)
- [EU AI Act konkret -- dr-dsgvo.de](https://dr-dsgvo.de/eu-ai-act-konkret-was-unternehmen-wissen-und-umsetzen-muessen/)
- [KI Automatisierung KMU 2026 -- findskill.ai](https://findskill.ai/de/blog/ki-automatisierung-mittelstand-2026/)
- [Best LLM for Mac Apple Silicon 2026 -- willitrunai.com](https://willitrunai.com/blog/best-llm-for-mac-apple-silicon-2026)
- [n8n Release Notes -- docs.n8n.io](https://docs.n8n.io/changelog/release-notes)

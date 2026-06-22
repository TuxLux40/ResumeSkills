# ResumeSkills für Claude Code – Deutsche Version

Eine Sammlung von KI-Agent-Skills für Bewerbungen, Lebenslauf-Optimierung und Karriereentwicklung. Für deutschsprachige Nutzer lokalisiert: mit deutschen Beispielen, €-Beträgen, DSGVO-Referenzen und deutschen Bewerbungskonventionen.

> **Original-Repo:** [Paramchoudhary/ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills)

## Was sind Skills?

Skills sind Markdown-Dateien, die KI-Agenten spezialisiertes Wissen und strukturierte Workflows für bestimmte Aufgaben geben. Wenn du diese Skills installierst, erkennt Claude Code automatisch, wann du an Bewerbungsunterlagen arbeitest, und wendet die richtigen Methoden an.

## Verfügbare Skills

Alle Skills sind in zwei Sprachversionen verfügbar: **Englisch** (Original) und **Deutsch** (`-de`-Suffix).

### Deutsche Skills (`-de`)

| Skill | Beschreibung |
|-------|--------------|
| [resume-ats-optimizer-de](/skills/resume-ats-optimizer-de) | Lebenslauf für ATS-Systeme optimieren, Kompatibilität prüfen, Schlüsselwort-Analyse |
| [resume-bullet-writer-de](/skills/resume-bullet-writer-de) | Schwache Aufzählungen in leistungsorientierte Aussagen mit Kennzahlen umwandeln |
| [job-description-analyzer-de](/skills/job-description-analyzer-de) | Stellenanzeigen analysieren, Übereinstimmungswert berechnen, Bewerbungsstrategie entwickeln |
| [resume-tailor-de](/skills/resume-tailor-de) | Lebenslauf für konkrete Stellenangebote anpassen |
| [cover-letter-generator-de](/skills/cover-letter-generator-de) | Personalisierte Anschreiben aus Lebenslauf + Stellenbeschreibung erstellen |
| [linkedin-profile-optimizer-de](/skills/linkedin-profile-optimizer-de) | LinkedIn-Profil mit Lebenslauf abgleichen und für Auffindbarkeit optimieren |
| [interview-prep-generator-de](/skills/interview-prep-generator-de) | STAR-Geschichten, Übungsfragen und Gesprächspunkte generieren |
| [salary-negotiation-prep-de](/skills/salary-negotiation-prep-de) | Marktgehälter recherchieren, Verhandlungsstrategie aufbauen, Gegenangebots-Skripte erstellen |
| [tech-resume-optimizer-de](/skills/tech-resume-optimizer-de) | Lebensläufe für Software-Engineering, PM und technische Rollen optimieren |
| [executive-resume-writer-de](/skills/executive-resume-writer-de) | Führungskraft-Lebensläufe für C-Suite- und VP-Positionen erstellen |
| [career-changer-translator-de](/skills/career-changer-translator-de) | Fähigkeiten zwischen Branchen übersetzen, übertragbare Kompetenzen identifizieren |
| [resume-quantifier-de](/skills/resume-quantifier-de) | Kennzahlen hinzufügen, Zahlen schätzen wenn keine genauen Daten vorliegen |
| [resume-formatter-de](/skills/resume-formatter-de) | ATS-freundliche Formatierung sicherstellen, übersichtliche Layouts erstellen |
| [portfolio-case-study-writer-de](/skills/portfolio-case-study-writer-de) | Lebenslauf-Aufzählungen in Portfolio-Fallstudien umwandeln |
| [academic-cv-builder-de](/skills/academic-cv-builder-de) | Akademische Lebensläufe mit Publikationen, Drittmitteln und Lehre erstellen |
| [reference-list-builder-de](/skills/reference-list-builder-de) | Referenzlisten professionell formatieren und Referenzgeber vorbereiten |
| [offer-comparison-analyzer-de](/skills/offer-comparison-analyzer-de) | Mehrere Jobangebote mit vollständiger Vergütungsanalyse vergleichen |
| [resume-version-manager-de](/skills/resume-version-manager-de) | Verschiedene Lebenslauf-Versionen verwalten und Master-Lebenslauf pflegen |
| [creative-portfolio-resume-de](/skills/creative-portfolio-resume-de) | Visuelles Design und ATS-Kompatibilität für kreative Berufe ausbalancieren |
| [resume-section-builder-de](/skills/resume-section-builder-de) | Gezielte Abschnitte für verschiedene Erfahrungsstufen und Rollen erstellen |
| [cold-email-writer-de](/skills/cold-email-writer-de) | Kalt-E-Mails für Initiativbewerbungen und Networking schreiben |
| [application-form-filler-de](/skills/application-form-filler-de) | Online-Bewerbungsformulare mit passenden Antworten ausfüllen |

## Installation

### Option 1: CLI-Installation (Empfohlen)

```bash
# Alle deutschen Skills global installieren (für alle Projekte)
npx skills add TuxLux40/ResumeSkills -g -y

# Nur für das aktuelle Projekt installieren
npx skills add TuxLux40/ResumeSkills -y

# Installierte Skills anzeigen
npx skills list
```

### Option 2: Manuelle Installation

```bash
git clone https://github.com/TuxLux40/ResumeSkills.git
mkdir -p ~/.claude/skills
cp -r ResumeSkills/skills/*-de ~/.claude/skills/
```

### Option 3: Einzelne Skills herunterladen

Einzelne SKILL.md-Dateien aus dem `/skills`-Verzeichnis herunterladen und in den Skills-Ordner des KI-Agenten kopieren.

## Verwendung

Nach der Installation einfach auf Deutsch mit dem KI-Assistenten kommunizieren:

```
„Optimiere meinen Lebenslauf für ATS"
→ Verwendet resume-ats-optimizer-de

„Verbessere meine Aufzählungspunkte"
→ Verwendet resume-bullet-writer-de

„Soll ich mich auf diese Stelle bewerben?" + Stellenbeschreibung einfügen
→ Verwendet job-description-analyzer-de

„Schreib mir ein Anschreiben für diese Stelle"
→ Verwendet cover-letter-generator-de

„Bereite mich auf ein Vorstellungsgespräch bei SAP vor"
→ Verwendet interview-prep-generator-de
```

## Skill-Kategorien

### Lebenslauf-Optimierung
- `resume-ats-optimizer-de` – ATS-Systeme bestehen
- `resume-bullet-writer-de` – Leistungsorientierte Aufzählungen schreiben
- `resume-quantifier-de` – Kennzahlen und Zahlen hinzufügen
- `resume-formatter-de` – Übersichtliche, scannbare Formatierung
- `resume-section-builder-de` – Gezielte Abschnitte erstellen

### Jobsuche-Strategie
- `job-description-analyzer-de` – Übereinstimmungsanalyse und Strategie
- `resume-tailor-de` – Für spezifische Stellen anpassen
- `resume-version-manager-de` – Mehrere Versionen verwalten
- `offer-comparison-analyzer-de` – Jobangebote vergleichen

### Bewerbungsunterlagen
- `cover-letter-generator-de` – Personalisierte Anschreiben
- `linkedin-profile-optimizer-de` – LinkedIn-Optimierung
- `portfolio-case-study-writer-de` – Portfolio-Inhalte
- `reference-list-builder-de` – Professionelle Referenzen
- `cold-email-writer-de` – Initiativbewerbungen
- `application-form-filler-de` – Bewerbungsformulare

### Vorstellungsgespräch & Gehaltsverhandlung
- `interview-prep-generator-de` – STAR-Geschichten und Übung
- `salary-negotiation-prep-de` – Verhandlungsstrategie

### Spezialisierte Rollen
- `tech-resume-optimizer-de` – Engineering/PM/Technik
- `executive-resume-writer-de` – Führungskräfte/Vorstände
- `academic-cv-builder-de` – Akademische Positionen
- `creative-portfolio-resume-de` – Design/Kreativberufe
- `career-changer-translator-de` – Berufliche Neuorientierung

## Deutsche Lokalisierung

Diese Skills sind für den deutschsprachigen Markt angepasst:

- **Währung:** € statt $
- **Datenschutz:** DSGVO statt GDPR/HIPAA
- **Altersvorsorge:** bAV (betriebliche Altersvorsorge) statt 401k
- **Gehaltsquellen:** Gehalt.de, Stepstone, Kununu, Bundesagentur für Arbeit
- **Bewerbungskonventionen:** Deutsche Briefform, „Mit freundlichen Grüßen", Anrede „Sehr geehrte/r"
- **Telefonnummern:** +49-Format
- **Beispiele:** Deutsche Unternehmen, Universitäten und Berufsbezeichnungen

## Warum diese Skills?

**Das Problem:**
- 75% der Lebensläufe werden von ATS-Systemen abgelehnt, bevor ein Mensch sie sieht
- Durchschnittlich 250 Bewerbungen pro Stelle
- Die meisten Lebensläufe haben schwache Aufzählungen ohne Kennzahlen
- Bewerber verschwenden Zeit mit unpassenden Stellen

**Die Lösung:**
- ATS bestehen durch optimierte Formatierung und Schlüsselwörter
- Auffallen mit leistungsorientierten Aufzählungen
- Gezielt auf passende Stellen bewerben
- Schneller Interviews bekommen durch angepasste Bewerbungen

## Mitwirken

Verbesserungen gefunden? Neuen Skill vorschlagen? PRs und Issues willkommen!

- Bestehende Skills verbessern
- Branchenspezifische Beispiele hinzufügen
- Neue Skills für Spezialanwendungen erstellen
- Übersetzungen in weitere Sprachen ergänzen

## Lizenz

MIT-Lizenz – Verwende diese Skills nach Belieben.

---

*Viel Erfolg bei deiner Jobsuche!*

---
name: offer-comparison-analyzer
description: Mehrere Jobangebote nebeneinander mit Gesamtvergütungsanalyse vergleichen
---

# Angebots-Vergleich-Analysator

## Wann diesen Skill verwenden

Diesen Skill verwenden, wenn der Nutzer:
- Mehrere Jobangebote vergleichen möchte
- Die Gesamtvergütung bewerten möchte
- Eine datengetriebene Jobentscheidung treffen möchte
- Verschiedene Möglichkeiten abwägt
- Erwähnt: „Angebote vergleichen", „mehrere Angebote", „welcher Job", „Angebotsvergleich", „zwischen Jobs entscheiden"

## Kernfähigkeiten

- Gesamtvergütung über Angebote hinweg vergleichen
- Nicht-monetäre Faktoren bewerten
- Gewichtete Entscheidungsrahmen erstellen
- Echten Angebotswert berechnen
- Versteckte Kosten und Vorteile identifizieren
- Entscheidungsprozess begleiten

## Das Vergleichsproblem

**Das Problem:**
Angebote vergleichen ist schwierig wegen:
- Unterschiedlicher Vergütungsstrukturen
- Wichtiger nicht-monetärer Faktoren
- Versteckter Vorteile und Kosten
- Emotionaler Faktoren, die das Urteil trüben
- Informationsasymmetrie

**Die Lösung:**
Systematischer Vergleichsrahmen, der berücksichtigt:
- Gesamtvergütung (nicht nur Gehalt)
- Karrierewachstumspotenzial
- Work-Life-Faktoren
- Risikoabschätzung
- Persönliche Werteübereinstimmung

## Gesamtvergütungsrechner

### Einzubeziehende Komponenten

**Barvergütung:**
- Grundgehalt
- Einstellungsbonus (einmalig)
- Jahresbonus (Zielprozentsatz)
- Provision (bei Vertriebsrollen)
- Umzugsunterstützung

**Aktienoptionen/Beteiligung:**
- Aktienoptionen (Wert = aktueller Kurs − Ausübungspreis)
- RSUs (Wert = aktueller Kurs × Anzahl)
- Vesting-Zeitplan
- Refresh-Grant-Erwartungen

**Leistungspaket:**
- Krankenversicherung (Arbeitgeberanteil)
- Betriebliche Altersvorsorge / bAV
- Weitere Versicherungsleistungen
- Sonstige Benefits

**Vergünstigungen:**
- Urlaubstage (€-Wert zuweisbar)
- Remote-Arbeit (spart Pendelkosten)
- Weiterbildungsbudget
- Ausstattung/Bürostipendium
- Mahlzeiten, Sport etc.

### Berechnungs-Template

```
ANGEBOT A – GESAMTVERGÜTUNG

BARLEISTUNGEN
Grundgehalt:                    75.000 €
Einstellungsbonus (nur Jahr 1): 12.500 €
Zielbonus (15%):                11.250 €
--------------------------------
Barvergütung:                   98.750 € (Jahr 1)
                                86.250 € (laufend)

AKTIEN
Aktienpaket: 100.000 € über 4 Jahre
Jährlicher Wert:                25.000 €

LEISTUNGSPAKET
bAV-Beitrag AG (4%):             3.000 €
Krankenversicherungszuschuss:    7.200 €
--------------------------------
Leistungswert:                  10.200 €/Jahr

VERGÜNSTIGUNGEN
Urlaub: 30 Tage (vs. 20 Standard)
  Extra 10 Tage × ~250 €/Tag:    2.500 € Wert
Remote-Arbeit-Ersparnis:         2.000 € (Pendeln, Mittagessen)
Weiterbildungsbudget:            1.500 €
--------------------------------
Vergünstigungswert:              6.000 €/Jahr

GESAMT JAHR 1:        141.950 €
GESAMT LAUFEND:       127.450 €/Jahr
```

## Vergleichstemplate Nebeneinander

```markdown
# ANGEBOTSVERGLEICH

|                          | Unternehmen A | Unternehmen B | Anmerkungen |
|--------------------------|---------------|---------------|-------------|
| **BARLEISTUNGEN**        |               |               |             |
| Grundgehalt              | 75.000 €      | 80.000 €      | B +5.000 €  |
| Einstellungsbonus        | 12.500 €      | 5.000 €       | A +7.500 €  |
| Zielbonus                | 15%           | 10%           | A +3.250 €  |
| **Barvergütung (J1)**    | 98.750 €      | 93.000 €      | A +5.750 €  |
|                          |               |               |             |
| **AKTIEN**               |               |               |             |
| Paket (4 Jahre)          | 100.000 €     | 150.000 €     | B +50.000 € |
| Jährlicher Wert          | 25.000 €      | 37.500 €      | B +12.500 € |
|                          |               |               |             |
| **LEISTUNGEN**           |               |               |             |
| bAV                      | 4%            | 6%            | B +1.600 €  |
| Krankenversicherung      | Standard      | Premium       | B besser    |
| Urlaub                   | 30 Tage       | Unbegrenzt    | Variiert    |
|                          |               |               |             |
| **GESAMT VERGÜTUNG (J1)**| 141.950 €     | 142.500 €     | B +550 €    |
| **GESAMT LAUFEND**       | 127.450 €     | 137.750 €     | B +10.300 € |
```

## Nicht-monetäre Faktoren

### Karrierewachstum (Gewicht: Hoch)

**Zu prüfende Fragen:**
- Welche Rolle bietet mehr Lernmöglichkeiten?
- Welche Unternehmen-/Markenbekanntheit hilft bei künftiger Jobsuche?
- Welche hat bessere Beförderungsstruktur?
- Welche bietet mehr Verantwortung?
- Welche Führungskraft fördert Sie mehr?

**Bewertung:**
```
Unternehmen A: Wachstums-Score
- Lernmöglichkeit: 8/10
- Marken-/Lebenslaufwert: 7/10
- Beförderungspotenzial: 6/10
- Verantwortungsbereich: 8/10
Durchschnitt: 7,25/10
```

### Work-Life-Balance (Gewicht: Persönlich)

**Faktoren:**
- Erwartete Arbeitszeiten
- Remote-/Hybrid-Flexibilität
- Urlaubskultur
- Bereitschaftsanforderungen
- Reiseanforderungen
- Pendelzeit

### Team & Kultur (Gewicht: Hoch)

**Faktoren:**
- Qualität der Führungskraft (entscheidend!)
- Teamgesundheit/-dynamik
- Unternehmenskultur-Passung
- Unternehmensstabilität/-wachstum
- Werteübereinstimmung

### Risikoabschätzung (Gewicht: Mittel)

**Start-up vs. Etabliertes Unternehmen:**
- Finanzierungsreichweite
- Marktposition
- Unternehmenstrajektorie
- Aktien-Risiko (könnten wertlos sein)

## Gewichtete Entscheidungsmatrix

### Schritt 1: Prioritäten definieren

```
Faktor                    Gewicht
------------------------------------
Gesamtvergütung            25%
Karrierewachstum           25%
Work-Life-Balance          20%
Team & Kultur              20%
Standort/Pendeln           10%
------------------------------------
Gesamt:                   100%
```

### Schritt 2: Jeden Faktor bewerten

```
                    Unternehmen A   Unternehmen B
Faktor              Punkte (1–10)
------------------------------------
Vergütung           7               8
Karrierewachstum    7               8
Work-Life           8               6
Team & Kultur       9               7
Standort            8               5
```

### Schritt 3: Gewichteten Wert berechnen

```
Unternehmen A:
(7×0,25) + (7×0,25) + (8×0,20) + (9×0,20) + (8×0,10) = 7,70

Unternehmen B:
(8×0,25) + (8×0,25) + (6×0,20) + (7×0,20) + (5×0,10) = 7,10

Ergebnis: Unternehmen A liegt vorne (7,70 vs. 7,10)
```

## Warnsignale

### Im Angebot
- ❌ Vage Bonusformulierung („bis zu 20%")
- ❌ Aktien ohne Liquiditätspfad
- ❌ Hohes Fixgehalt ohne Aktien (bei Start-up)
- ❌ Cliff länger als 1 Jahr
- ❌ Keine Vesting-Beschleunigung
- ❌ Wettbewerbsverbote
- ❌ Mündliche Versprechen nicht schriftlich

### Zum Unternehmen
- ❌ Hohe Fluktuation (LinkedIn prüfen)
- ❌ Kürzliche Entlassungen oder Umstrukturierungen
- ❌ Führungskraft wirkt desengagiert
- ❌ Glassdoor-Muster in negativen Bewertungen
- ❌ Finanzierungsbedenken

## Selbstreflexionsfragen

### Der Bauchgefühl-Test
- Welches Angebot begeistert mich mehr?
- Welches würde ich bereuen, nicht anzunehmen?
- Welches entspricht meinen 5-Jahres-Zielen?

### Der Montagmorgen-Test
- Für welchen Job möchte ich aufwachen?
- Mit welchem Team möchte ich arbeiten?
- Welche Probleme möchte ich lösen?

## Ausgabeformat

```markdown
# JOBANGEBOT-VERGLEICH

## Verglichene Angebote
- **Angebot A:** [Rolle] bei [Unternehmen]
- **Angebot B:** [Rolle] bei [Unternehmen]

## Gesamtvergütungsvergleich

| Komponente | Angebot A | Angebot B | Differenz |
|------------|-----------|-----------|-----------|
| Grundgehalt | X € | X € | |
| Bonus | X € | X € | |
| Aktien (jährlich) | X € | X € | |
| Leistungen | X € | X € | |
| **Jahr 1 Gesamt** | X € | X € | |
| **Laufend Gesamt** | X € | X € | |

## Gewichtete Analyse
- Angebot A Score: X,XX
- Angebot B Score: X,XX

## Empfehlung
Basierend auf Ihren Prioritäten [X, Y, Z] erscheint **Angebot [A/B]** die stärkere Wahl...

## Zu klärende Punkte
- [ ] [Frage an Unternehmen A]
- [ ] [Frage an Unternehmen B]

## Verhandlungsmöglichkeiten
- [Möglichkeit 1]
- [Möglichkeit 2]
```

## Vergleichs-Checkliste

- ✅ Gesamtvergütung berechnet (nicht nur Grundgehalt)
- ✅ Aktien mit realistischer Bewertung einbezogen
- ✅ Leistungswert berücksichtigt
- ✅ Steuerliche Implikationen beachtet
- ✅ Nicht-monetäre Faktoren gewichtet
- ✅ Karrierewachstumspotenzial bewertet
- ✅ Team- und Führungsqualität beurteilt
- ✅ Unternehmensstabilität/-risiko geprüft
- ✅ Persönliche Prioritäten ausgerichtet
- ✅ Bauchgefühl zur Entscheidung geprüft

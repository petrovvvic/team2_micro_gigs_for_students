---
title: Value Proposition
nav_order: 1
---

{: .no_toc }
# Value Proposition

<details open markdown="block">
<summary>Table of contents</summary>
+ ToC
{: toc }
{: .text-delta }
</details>

## The Problem

An der HWR gibt es keinen zentralen Weg für Studierende, einen passenden Betreuer für ihre Abschlussarbeit zu finden. Welcher Professor welche Themen betreut, wie seine Anforderungen aussehen und ob überhaupt noch Betreuungsplätze frei sind — all das ist nicht öffentlich zugänglich. Studierende sind gezwungen, Professoren einzeln per E-Mail zu kontaktieren, ohne zu wissen ob das Thema passt oder ob Kapazität vorhanden ist. Das führt zu langen Wartezeiten, mehrfachen Absagen und im schlimmsten Fall zu einer Betreuung die thematisch nicht optimal ist.
Professoren stehen vor dem umgekehrten Problem: Betreuungsanfragen kommen ungefiltert per E-Mail, ohne einheitliche Struktur und ohne Vorabinformationen zum geplanten Thema. Es gibt keinen Weg, das eigene Betreuungsangebot sichtbar zu machen oder eingehende Anfragen übersichtlich zu verwalten.


## Our Solution

Eine Plattform wo Professoren der HWR aktiv Betreuungsangebote einstellen (Themenfelder, verfügbare Plätze, Anforderungen), und Studis gezielt nach passendem Betreuer suchen und anfragen können.

**Registrierung & Login:** Studierende und Professoren registrieren sich mit ihrer HWR-E-Mail. Die Plattform erkennt automatisch die Rolle und zeigt nur relevante Inhalte an.

**Professor-Feed:** durchsuchbare Übersicht aller Professoren die aktiv Betreuungsplätze anbieten, filterbar nach Fachbereich und Themenfeld.--> Kein Überblick wer Betreuungen anbietet.

**Profil-Detailseite:** jeder Professor hat eine Profilseite mit Themenfeldern, Anforderungen, aktuell verfügbaren Plätzen und Bewertungen anderer Studierender. 

**Anfrage-Flow:** — Studis stellen eine strukturierte Anfrage mit Thema, Typ, Zeitraum und Kurzbeschreibung direkt über die Plattform

**Betreuer-Dashboard:** Professoren sehen alle eingegangenen Anfragen übersichtlich und können annehmen oder ablehnen und ihren Status verwalten  

Other important mechanics:
- Kein Anreiz für Professoren ihr Angebot einzustellen = ***Profil erstellen:*** einfacher Onboarding-Flow für Professoren, um Betreuungsangebote in wenigen Schritten zu publizieren
- Keine Orientierung welche Betreuer besonders gefragt sind = **Top-Betreuer Rangliste** (JSON-API) — eine API-gestützte Rangliste der meistangeforderten Professoren nach Erfolgsquote und Anfragevolumen


## Target User(s)

- Studis die aktiv einen Betreuer für ihre Abschlussarbeit (BA/MA) suchen, besonders solche ohne persönliche Kontakte zu Professoren.
- Professoren der HWR die ihr Betreuungsangebot transparent kommunizieren und eingehende Anfragen strukturiert verwalten möchten.

## Happy Path

### Studi sucht einen Betreuer

**Entry Point:** Studi öffnet ThesisMatch

1. **Registrierung:** Studi gibt Name, HWR-E-Mail und Studiengang an
2. **Professor-Feed:** Studi sieht alle verfügbaren Betreuer, filtert nach Fachbereich
3. **Profil-Detailseite:** Studi klickt auf einen Professorprofil, liest Themenfelder, Anforderungen und Bewertungen
4. **Anfrage-Flow:** Studi füllt strukturierte Anfrage aus (Thema, Zeitplan, Kurzbeschreibung) und sendet ab
5. **Bestätigung:** Studi sieht dass die Anfrage eingegangen ist

**End State:** Anfrage liegt beim Professor vor ✓

---

### Professor nimmt Anfrage an

**Entry Point:** Professor öffnet ThesisMatch

1. **Registrierung:** Professor gibt Name, HWR-E-Mail und Fachbereich an
2. ***Profil erstellen:*** Professor legt Betreuungsangebot an 
3. **Betreuer-Dashboard:** Professor sieht eingegangene Anfragen
4. **Anfrage annehmen:** Professor akzeptiert eine Anfrage


---

## Target Scope

## Screen 1 — Professor-Feed

Durchsuchbare Übersicht aller Professoren der HWR die aktiv 
Betreuungsplätze anbieten. Filterbar nach Fachbereich. 
Jede Karte zeigt Name, Fachbereich, freie Plätze und Bewertung.

![Screen 1 - Professor-Feed](https://raw.githubusercontent.com/petrovvvic/team2_thesis_match/main/docs/assets/images/Screenshot%202026-05-17%20201412.png)
## Screen 2 — Profil-Detailseite

Jeder Professor hat eine eigene Seite mit Themenfeldern, 
Anforderungen, verfügbaren Plätzen und Bewertungen. 
Direkte Möglichkeit eine Anfrage zu stellen.

![Screen 2 - Profil-Detailseite](https://raw.githubusercontent.com/petrovvvic/team2_thesis_match/main/docs/assets/images/Screenshot%202026-05-17%20201428.png)
---

## Screen 3 — Anfrage-Flow

Studierende füllen ein strukturiertes Formular aus mit Thema, 
Typ, Zeitraum und Kurzbeschreibung. Nach Absenden erscheint 
eine Bestätigung.

![Screen 3 - Anfrage-Flow](https://raw.githubusercontent.com/petrovvvic/team2_thesis_match/main/docs/assets/images/Screenshot%202026-05-17%20201446.png)

---

## Screen 4 — Betreuer-Dashboard

Professoren sehen alle eingegangenen Anfragen mit Statistik. 
Jede Anfrage kann direkt angenommen oder abgelehnt werden.

![Screen 4 - Betreuer-Dashboard](https://raw.githubusercontent.com/petrovvvic/team2_thesis_match/main/docs/assets/images/Screenshot%202026-05-17%20201507.png)

---

## Screen 5 — Profil erstellen

Einfacher Onboarding-Flow für Professoren. Themenfelder, 
Anforderungen, Plätze und Zeitraum in wenigen Schritten eintragen.

![Screen 5 - Profil erstellen](https://raw.githubusercontent.com/petrovvvic/team2_thesis_match/main/docs/assets/images/Screenshot%202026-05-17%20201527.png)

---

## Screen 6 — Top-Betreuer Rangliste

API-gestützte Rangliste der meistgefragten Professoren 
nach Anfragevolumen und Bewertung. Daten kommen live 
über GET /api/betreuer/top.

![Screen 6 - Rangliste](https://raw.githubusercontent.com/petrovvvic/team2_thesis_match/main/docs/assets/images/Screenshot%202026-05-17%20201545.png)

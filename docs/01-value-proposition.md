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

Studis an der HWR die eine Bachelor- oder Masterarbeit schreiben wollen, haben keinen strukturierten Weg einen passenden Betreuer zu finden. Professoren-Profile, Forschungsinteressen und verfügbare Betreuungsplätze sind verstreut oder gar nicht öffentlich. Das Ergebnis: Studis schreiben kalte E-Mails ins Blaue, warten wochenlang auf Antworten, und landen oft bei einem Prof der thematisch gar nicht passt.

- Sie wissen nicht, welche Professoren überhaupt Betreuungen anbieten — es gibt keinen zentralen Überblick.
- Selbst wenn sie einen Namen kennen, wissen sie nicht ob das Thema wirklich passt — Forschungsinteressen und Anforderungen sind kaum öffentlich. 
- Es gibt keinen definierten Weg eine Anfrage zu stellen — Studis schreiben kalte E-Mails ins Blaue und warten wochenlang. 
- Professoren haben keinerseits einen Überblick über eingehende Anfragen und können ihr Angebot nicht sichtbar machen.


## Our Solution

Eine Plattform wo Professoren der HWR aktiv Betreuungsangebote einstellen (Themenfelder, verfügbare Plätze, Anforderungen), und Studis gezielt nach passendem Betreuer suchen und anfragen können.
- Kein Überblick wer Betreuungen anbietet = Professor-Feed — eine durchsuchbare Übersichtsseite aller Professoren, die aktiv Betreuungsplätze anbieten, filterbar nach Fachbereich und Themenfeld
- Unklare Passung zwischen Thema und Betreuer = Profil-Detailseite — jeder Professor hat eine Profilseite mit Forschungsinteressen, Anforderungen an die Arbeit und aktuell verfügbaren Plätzen
- Kein strukturierter Weg eine Anfrage zu stellen = Anfrage-Flow — Studis können direkt über die Plattform eine strukturierte Betreuungsanfrage mit Thema, Zeitplan und Kurzbeschreibung absenden
- Professoren haben keinen Überblick über eingehende Anfragen = Betreuer-Dashboard — Professoren sehen alle eingegangenen Anfragen, können annehmen oder ablehnen und ihren Status verwalten
Other important mechanics:
- Kein Anreiz für Professoren ihr Angebot einzustellen = Profil erstellen — einfacher Onboarding-Flow für Professoren, um Betreuungsangebote in wenigen Schritten zu publizieren
- Keine Orientierung welche Betreuer besonders gefragt sind = Top-Betreuer Rangliste (JSON-API) — eine API-gestützte Rangliste der meistangeforderten Professoren nach Erfolgsquote und Anfragevolumen


## Target User(s)

- Studis im 5./6. Semester (BA) oder 2./3. Semester (MA) die einen Betreuer suchen
- Professoren der HWR die Betreuungskapazität transparent machen wollen

##  Happy Path
Entry Point: Studi öffnet ThesisMatch

Professor-Feed — Studi sieht alle verfügbaren Betreuer, filtert nach Fachbereich
Profil-Detailseite — Studi klickt auf einen Professor, liest Forschungsinteressen und Anforderungen
Anfrage-Flow — Studi füllt strukturierte Anfrage aus (Thema, Zeitplan, Kurzbeschreibung) und sendet ab
Bestätigung — Studi sieht dass die Anfrage eingegangen ist

End State: Anfrage liegt beim Professor vor ✓

Happy Path — Professor nimmt Anfrage an
Entry Point: Professor öffnet ThesisMatch

Profil erstellen — Professor legt Betreuungsangebot an (einmalig)
Betreuer-Dashboard — Professor sieht eingegangene Anfragen
Anfrage annehmen — Professor akzeptiert eine Anfrage

---

## Target Scope

[Include your visual scoping of the web app (e.g., UI screens scribbles), as elaborated at start of the project as part of your Assignment.]
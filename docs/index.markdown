---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
permlink: /home/
---

# Refactoring
Wir haben in den letzten Jahren etliche Softwareprojekte miterlebt - darunter Neuentwicklungen, oft aber auch den Umbau oder die Migration von bestehen Codebases.
Wir haben in diversen Teams gearbeitet, nach mehr oder weniger agilen Ansätzen. Wir haben Erfolge erlebt - ebenso wie Fehler und Projekte, die schlecht gelaufen sind.

Das, was unsere Arbeit aber immer prägt, ist <mark>refactoring</mark>. Eine Softwarelösung ist stets im Fluss. So steht die Frage nach Wartung und Weiterentwicklung ständig an erster Stelle.
 
# Die Herausforderung
Leichter gesagt als getan - denn damit beschäftigt sich die Softwareindustrie seit jeher. 
Unser Fokus waren und sind immer die Menschen. Im Team wie im Fachbereich gehören klare und gute Kommunikation sowie strukturierter Aufbau von Know-How zu den wichtigsten Grundprinzipien.

Dadurch kann einerseits ein zeitlich und budgetär eingeschränktes Projekt erfolgreich abgeschlossen und gleichzeitig schwankende Human Resources abgefedert werden. Denn nicht jeder ist als Entwickler geboren oder hat am Anfang den entsprechenden Ausbildungspfad gewählt. Menschen im Team, die sich von selbst ständig neu ausrichten und einlernen? 

Eine fast unrealistische Erwartung.


---
# Wie gehen wir damit um?
Die nächsten Abschnitte beschreiben im Detail, nach [arc42](https://arc42.org) strukturiert, welche Ansätze und Tools wir nutzen, damit das menschliche Element im breiten Softwareuniversum seine Stärken voll entfalten und einsetzen kann - und dass immer wieder neu.


# 1. Einführung und Ziele {#einfuehrung-und-ziele}
 
Unser Zeil ist, dass mit jedem <mark>refactoring</mark> die Qualität[^1] des Codes steigt und das Team ein Stück schlauer wird. 

Damit Projekte geligen und <mark>refactoring</mark> sicher gemacht werden kann, glauben wir:

- Die [Grundlangen](/grundlagen/) sind entscheidend.
- Know-How wird auf Grundlagen strukturiert aufgebaut - mit den besten Mitteln, die zur Verfügung stehen.
- Standards (im Code und in Workflows) werden eingehalten.
- Alles, was automatisiert werden kann, wird automatisiert.



## 1.2 Qualitätsziele {#qualitaetsziele}

Welche Ziele verfolgen wir mit unserem Ansatz? 

|Id| Ziel      | Erwartung |
|--| ----------- | ----------- |
|Q1| erflogreiches Projekt | sollte in den gegeben Constraints (Zeit, Budget) machbar sein    |
|Q2| Wartbarkeit des Codes     | Changes müssen vorgesehen werden, Entwicklungsmuster und Prinzipien (z.B. [Open-closed principle](https://en.wikipedia.org/wiki/Open–closed_principle)) sind Standar       |
|Q3| Jeder ist im Team Willkommen      | Das Team kann flexibel neue Mitgleider aufnehmen und verlieren, ohne dass das Projekt groß leidet       |
|Q4| Standards werden eingehalten     | Regeln sind einfach, klar und nachvollziehbar kommuniziert und im Team veränderbar       |

## 1.3 Stakeholder {#stakeholder}

Welche Erwartungen haben diverse Stakeholder an <mark>refactoring</mark>?

| Role      | Erwartung |
| ----------- | ----------- |
| Fachbereich | will neue Features schnell implementiert haben (und Bugs gefixed), ohne den Satz *"das hat schon mal funktioniert"* nutzen zu müssen        |
| Entwickler      | will für eine kleine Anpassung wenig Zeit benötigen, sich nicht wiederholen und wiederkehrende Aufgaben (z.B. Testing) automatisieren   |
| Quereinsteiger   | will verstehen, was der Unterschied zwischen int und Integer in Java ist und welche Konsequenzen das mit sich bringt       |
| Software Architekt   | will modulares, skalierbares und sauberes Design das von anderen Stakeholdern mitgetragen wird      |
| Projekt Manager   | will Budget und Zeitconstrainst eingehalten haben      |
| Quality Engineer  | will die Qualität der Software bei jeder inkrementelen Erweiterung steigern         |
| Betrieb | will schnelle Reaktionszeiten durch Development        |


# 4 Lösungsstrategie

Die Qualitätsziele beschreiben Aspekte der Zusammenarbeit, auf die wir besonderen Fokus legen.

### Q1: erfolgreiches Projekt
- Ein Softwareprojekt sollte iterativ nach Standards entwickelt werden. Das heißt für uns nach Scrum, mit allem, was dazu gehört.
- Ziele werden explizit definiert, nach dem arc42-Motto [*Handeln stat jammern*](https://www.arc42.de/downloads/Handeln-statt-Jammern.pdf), für manche sogar nach der schwäbischen Prämisse *Schaffe, Net Schwätza*.
- Es wird dokumentiert - Code über Tests, Architektur oder Prozesse nach einheitlichen Struktur.

### Q3: Jeder ist im Team Willkommen  
- [Code](https://www.joelonsoftware.com/2006/10/25/the-guerrilla-guide-to-interviewing-version-30/) gehört zum Vorstellungsgespräch.
- Es ist ok, keinen eigenen Code oder geringe Programmierkenntnisse zu haben. In diesem Fall gehört ein Beispiel in [Jack](https://www.nand2tetris.org) dazu, das auf einem selbstgebautem [Hack Computer](https://www.nand2tetris.org/course) läuft.
- Weiterbildung & Zeit zum Experimentieren sind vorgesehen.

### Q4: Standards werden eingehalten 
- Im Team zu programmieren benötigt Regeln (was wir unter dem Begriff `Clean Code` verstehen).
- Akzeptanzkriterien, Definitions of Done, Definitions of Ready gehören zum Alltag.
- Statische Codeanalyse und Feedback aus diversen Metriken werden kontinuierlich integriert - es gibt keine Auslieferung ohne *Quality Gate*.

Letztlich wird dadurch ein weiteres Qualitätsziel erreicht, nämlich die *Wartbarkeit des Codes (Q2)*. Im Allgemeinen öffnen sich dadurch die Wegen zum kontinuierlichen <mark>refactoring</mark>.  



[^1]: Qualität kann natürlich beliebig definiert sein, wir verstehen darunter aber eine Qualität, die gemessen werden kann, sei es durch statische Codeanalyse, Team Velocity unsw.

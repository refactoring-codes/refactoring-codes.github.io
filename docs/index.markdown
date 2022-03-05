---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
permlink: /home/
---

# Refactoring
Wir haben in den letzten Jahren etliche Projekte erlebt - neue Projekte, aber auch bestehende Projekte.
Wir haben in diversen Teams gearbeitet, nach mehr oder weniger agilen Ansätzen. 
Wir haben Erfloge erlebt, genaus wo Fehler und Projekte die schlecht gelaufen sind.

Das, was unsere Arbeit aber immer prägt ist <mark>refactoring</mark>. Eine Softwarelösung ist stets im Fluss
und so stehen die Ansprüche an Wartung und Weiterentwicklung im Fokus. 

# Die Herausforderung
Leicht gesagt als getan - denn damit beschäftigt sich die Softwareindustrie seit je. Unser Fokus
waren und sind immer die Menschen. Ob im Team, oder im Fachbereich, gehören klare und gute Kommunkation und strukturierter Aufbau vom Know How zu den wichtigsten Grundprinzipien. 

Dadurch kann einerseits tatsächlich ein zeitlich und budgeter eingeschränktest Projekt erflogreich abgeschlossen werden und gleichzeitig aber auch das Human Resourcen Thema abgefedert werden.
Denn nicht jeder ist als Entwickler geboren oder am Anfang den entsprechenden Ausbildungspfad ausgewählt.

Dennoch brauchen die Wirtschaft und Geschellschaft genau die Menschen, die sich ständig neuadaptieren und stellen dadurch eine fast unrealistische Erwartung.

---
# Wie gehen wir damit um?
Die nächsten Abschnitte beschreiben im Detail, nach [arc42](https://arc42.org) strukturiert, welche Ansätze und Tools wir nutzen, damit das menschliche Element in dem breiten Softwareuniversum seine stärken voll etnfalten und einsezten kann - und dass immer wieder neu.


# 1. Einführung und Ziele {#einfuehrung-und-ziele}
 
Unser Zeil ist, dass mit jedem <mark>refactoring</mark> die Qualität[^1] vom Code steigen soll. 

Damit Projekte geligen und <mark>refactoring</mark> sicher gemacht werden kann glauben wir:

- Die Grundlangen sind entscheidend.
- Knowhow wird sturkturiert aufgebaut, mit den besten Mitteln die zur Verfügung stehen.
- Standards (im Code und in Workflows) werden eingehalten.
- Alles was automatisiert werden kann wird automatisiert.



## 1.2 Qualitätsziele {#qualitaetsziele}

|Id| Ziel      | Erwartung |
|--| ----------- | ----------- |
|Q1| Projekt | Muss in gegeben Budget-Constraints machbar sein    |
|Q2| Wartbarkeit      | Changes müssen vorgesehen werden, Entwicklungsmuster und Prinzipien (z.B. [Open-closed principle](https://en.wikipedia.org/wiki/Open–closed_principle))       |
|Q3| Team      | Kann flexibel neue Mitgleider aufnehmen und verlieren       |
|Q4| Standards      | sind einfach, klar, nachvollziehbar und veränderbar       |

## 1.3 Stakeholder {#stakeholder}

Welche Erwartungen haben diverse Stakeholder an <mark>refactoring</mark>?

| Role      | Erwartung |
| ----------- | ----------- |
| Fachbereicht | will neue Features schnell implementiert werden (und Bugs gefixed), ohne den Satz *"das hat schon mal funktioniert"* nutzen zu müssen        |
| Entwickler      | will für eine kleine Anpassung wenig Zeit gebrauchen, sich nicht wiederholen und wiederkehrende Aufgaben (z.B. Testing) automatisieren   |
| Quereinsteiger   | will verstehen, was der Unterschied  zwischen int und Integer in Java ist und welche Konsequenzen es mit sich bringt        |
| Software Architekt   | will modulares, skalierbares und sauberes Design das von anderen Stakeholdern mitgetragen wird      |
| Projekt Manager   | will Budget und Zeitconstrainst eingehalten haben      |
| Quality Engineer  | will die Qualität der Software bei jeder inkrementelen Erweiterung steigern         |
| Betrieb | will schnelle Reaktionszeiten durch Development        |



[^1]: Qualität kann natürlich beliebig definiert sein, wir verstehen darunter aber eine Qualität, die gemessen werden kann, sei es durch statische Codeanalyse, Team Velocity unsw.
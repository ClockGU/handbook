---
description: Das CLOCK Projekt aus technischer Perspektive
---

# Zur Technik

Clock ist eine _Web-App,_ die aus verschiedenen Komponenten besteht:

### Backend

Das, was die Benutzer\*innen _nicht_ zu sehen bekommen. Dazu gehören:

* die Datenbank \(in der alle Daten gespeichert werden\)
* die Schnittstelle \(über die man Daten auslesen und speichern kann\) 

Die Clock-Datenbank basiert auf [PostGreSQL 9.4+](https://www.postgresql.org/). Die Schnittstelle ist mit dem [Django-REST](https://www.django-rest-framework.org/)-Framework umgesetzt. Eine solche Schnittstelle wird auch als _API_ \(Advanced Programming Interface\) bezeichnet.

### Frontend

Das, was Du als Benutzer\*in zu sehen bekommst: die Benutzeroberfläche \(oder auch das _User-Interface_ oder auch _UI_\). Das Frontend kommuniziert über die _API_ mit der Datenbank .

Das Frontend ist mit dem Javascript-Framework [Vue.js](http://vuejs.org) umgesetzt, mit dem man Web-Apps programmieren kann, die in jedem \(modernen\) Webbrowser laufen.

### Design

Apps verwenden wir \(fast\) alle - auf mobilen oder nichtmobilen Geräten - und da gibt es viele Varianten, die Benutzeroberfläche zu gestalten.

Wir halten uns weitestgehend an die Designsprache [Material Design](http://material.io), die von Google entwickelt wurde und zu einem gewissen Standard im Web geworden ist.

Diese Richtlinien beschreiben die Darstellung einzelner Komponenten, aber auch die Positionierung von Menüs, Buttons etc. Dabei wird auf Logik, Konsistenz und Klarheit geachtet.

Zur Umsetzung von Material Design in Vue.js kommt die Design-Bibliothek [Vuetify](http://vuetifyjs.com) zum Einsatz.

## Mitarbeit

Wenn Du Dich mit der Technik in Frontend und Backend auskennst und mit uns fachsimpeln oder etwas zum Projekt beitragen möchtest, dann kannst Du Dich gerne mit uns in Verbindung setzen: [clock-kontakt@dlist.uni-frankfurt.de](mailto:clock-kontakt@dlist.uni-frankfurt.de) oder im GU-Rocketchat [clock\_user](https://chat.studiumdigitale.uni-frankfurt.de/channel/clock_user).


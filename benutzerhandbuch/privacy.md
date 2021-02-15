---
description: Was geschieht mit meinen Daten?
---

# Datenschutz

Clock ist eine Web-App für individuelle Benutzer\*innen.

Das bedeutet, dass man Clock nur mit einem Benutzerkonto und einem Passwort benutzen kann, weil Deine gesammelten Arbeitszeiten nur _Dich_ etwas angehen.

Das bedeutet aber auch, dass die von Dir eingegebenen Daten gespeichert werden. Welche das sind und was damit geschieht, erklären wir in diesem Artikel.

## Gepeicherte Daten

Alle Daten, die Dich als Benutzer\*in betreffen bzw. von Dir eingegeben wurden, werden in einer _Datenbank_ gespeichert. Dazu gehören

* die Daten Deines Benutzerkontos:
  * Login-Name\*
  * HRZ-Mailadresse\*\*
  * Vor- und Nachname
  * Statusgruppe \(`student` oder `employee`\)
  * Personalnummer \(die bekommst Du von der Uni\)
  * Erstellungsdatum \(entspricht Deiner ersten Anmeldung bei Clock\)
  * Datum der letzten Änderung am Benutzerkonto
* die Daten für jeden Vertrag, den Du in Clock angelegt hast
  * Name des Vertrags
  * Start- und Enddatum
  * Stundenzahl
  * Erstellungsdaten \(Datum und Benutzer\)
  * Änderungsdaten \(Datum und Nutzer der letzten Änderung\)
* die Arbeitszeiten, die Du in Clock eingegeben hast
  * Schichtdaten \(Datum & Zeit von Anfang und Ende der Schicht\)
  * zugehöriger Vertrag
  * Schichttyp \(normal, Urlaub, krank\)
  * Notizen und _Tags_ \(die Du eingegeben hast\)
  * Erstellungs- und Änderungsdaten
  * Status der Schicht \(geplante Schicht / bereits exportiert\)
* die "Reports" - monatliche Zusammenfassungen Deiner Arbeitszeit
  * Datum \(Monat und Jahr\)
  * aktuell gearbeitete Stunden
  * zugehöriger Vertrag
  * Erstellungs- und Änderungsdaten

Aus diesen Daten werden die _Stundenzettel_ generiert und zum Download bereitgestellt. Die PDF-Dateien werden nicht gespeichert, sondern bei jedem Export neu erzeugt.

_\*\) Clock speichert Dein Passwort nicht - die Anmeldung läuft über einen Server beim HRZ._

_\*\*\) Deine Mailadresse wird uns vom HRZ-Login-Server geliefert und unterscheidet sich möglicherweise von Deiner gewohnten Adresse, weil Deine @stud-Adresse nur ein alternativer Namen \(Alias\) ist._

## Welche anderen Daten werden noch gespeichert?

Beim Zugriff auf den Dienst über das Internet werden sowohl von Deinem Provider als auch vom Clock-Server routinemäßig Zugriffsdaten gespeichert \(IP-Adresse und Zugriffszeit\). Diese Daten werden aber nicht in der Clock-Datenbank gespeichert.

## Wo liegen meine Daten?

Die Clock-Datenbank liegt auf einem Server im Hochschulrechenzentrum, der vom Clock-Team administriert wird.

## Wer kann meine Daten einsehen?

Eigentlich nur Du.

"Eigentlich" __deshalb, weil die Administratoren, die die Clock-App betreuen und weiterentwickeln aus technischen Gründen Zugriff auf die Datenbank haben müssen.

Sie werden aber nicht in Deine Arbeitszeitdaten hineinschauen, ohne Dich zu fragen oder ohne von Dir dazu aufgefordert zu werden.

## Kann ich meine Daten einsehen?

Clock enthält nur Daten, die Du selbst eingegeben hast - entweder durch das manuelle Eintragen oder live-Clocken von Schichten. Diese kannst Du immer einsehen.

Auch die in Deinem User-Account hinterlegten Daten kannst Du einsehen \(auch die, die Du nicht ändern kannst\).

## Kann ich meine Daten löschen?

Einzelne Schichten kannst Du jederzeit selbsttätig löschen, sofern der Monat noch nicht gesperrt ist.

Du kannst alle Daten komplett löschen indem Du Deinen Account löschst \("Recht auf Vergessenwerden"\). Zur Bestätigung musst Du dafür Deine Mailadresse eingeben. Diese sieht evtl. anders aus als Deine gewohnte Adresse, weil @stud-Adressen so genannte _Aliasse_ \(alternative Namen\) sind.

Natürlich hat das Löschen des Clock-Accounts keinen Einfluss auf Deinen HRZ-Account.

{% hint style="info" %}
Aus technischen Gründen bleiben die Daten in den Sicherheitskopien erhalten. Bei der Wiederherstellung des Systems nach einem Datenverlust werden Deine gelöschten Daten aber nicht wiederhergestellt.
{% endhint %}

{% hint style="danger" %}
Ein gelöschter Account kann nicht wieder hergestellt werden!
{% endhint %}

## Darf ich meine Daten haben?

Gemäß den Anforderungen der [DSGVO](https://dsgvo-gesetz.de) \(Artikel 15 & 20\) gibt es eine Möglichkeit, alle Clock-Daten in einer gängigen maschinenlesbaren Form \(JSON\) zu exportieren.

Du findest die Funktion in den _Einstellungen_ &gt; _DSGVO_, wenn Du oben auf Deinen Namen klickst.

## Kann ich Euch das alles glauben?

Clock ist ein Projekt von Studis für Studis - das haben wir bei den Vereinbarungen mit den offiziellen Stellen der Uni \(PersonalServices\) auch immer wieder klar gemacht.

Außerdem ist Clock _Open Source_: Alle funktionalen Programmteile und Informationen sind öffentlich und können von Menschen mit entsprechenden Programmierkenntnissen nachvollzogen werden.

Aber natürlich geht es hier um Vertrauen. Du bist jederzeit eingeladen, mit uns direkt ins Gespräch zu kommen: [clock-kontakt@dlist.uni-frankfurt.de](https://github.com/ClockGU/handbook/tree/c6a3efe17c130c71ac14b67706cb399e4d331dfb/benutzerhandbuch/clock-kontakt@dlist.uni-frankfurt.de) oder im [Rocketchat](https://chat.studiumdigitale.uni-frankfurt.de/channel/clock_user) der Uni.


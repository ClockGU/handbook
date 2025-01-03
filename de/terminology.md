---
description: Clock-Terminologie
---

# Begriffe

Clock verwendet einige besondere Begriffe, die wir hier vorstellen und erklären:

## Vertrag

Der _Vertrag_ bildet Deinen realen Arbeitsvertrag in Clock ab.

Als Hilfskraft hast Du mit der Universität einen _Arbeitsvertrag_ abgeschlossen. In diesem steht...

* ...ab wann der Vertrag läuft (immer der 01. oder 16. eines Monats)
* ...bis wann der Vertrag läuft (immer der 15. oder der letzte Tag eines Monats)
* ...wie viele Stunden Du _durchschnittlich_ im Monat arbeiten musst

In Clock hat ein Vertrag zusätzlich einen _Namen_ (z.B. "Mathe 2 Tutorium"), den Du selbst vergeben kannst.

{% hint style="info" %}
Der Vertrag ist die Basis für die Erfassung Deiner Arbeitszeit. Deshalb musst Du immer zuerst einen Vertrag anlegen, bevor Du überhaupt Zeiten erfassen kannst.
{% endhint %}

Du kannst mehrere parallele Verträge mit verschiedenen Dienststellen an der Uni haben, die dann auch in Clock unabhängig voneinander sind.

Beim Anlegen eines Vertrages kannst Du einen _Übertrag aus dem vorangehenden Monat_ angeben, wenn Du schon Stunden auf dem Arbeitszeitkonto hast (z.B. in einer Excel-Datei) und erst später beginnst, Clock zu benutzen. In diesem Fall muss der Clock-Vertrag an dem Zeitpunkt beginnen, an dem Du Clock erstmalig verwendest, da sonst die Berechnung des Übertrags nicht korrekt funktioniert und die Vormonate als Minusstunden angerechnet werden.

#### Vertrag verlängern / ändern

Wenn sich an Deinem Vertrag und an Deiner Beschäftigung nichts ändert (Stundenzahl bleibt gleich), kannst Du einfach das Enddatum auf das neue Vertragsende setzen und den Vertrag weiter nutzen. Wenn sich die Stundenzahl ändert, musst Du für die nächste Zeitperiode einen neuen Vertrag anlegen und den Übertrag angeben.

### Die Referenz-ID

Deine monatlichen Zeiterfassungsdaten werden als Report (siehe unten) digital in einem "Zeitspeicher" (TimeVault) abgelegt und dort für die vorgeschriebene Frist (2 Jahre) gespeichert. Damit Deine Führungskraft diese Daten einsehen können, muss eine Verbindung zwischen Deinen Daten und Deiner Führungskraft hergestellt werden.

Dafür gibt es die Referenz-ID, die Du (je Vertrag) einmalig an Deine Führungskraft schicken musst. Deine Führungskraft kann dann die Referenz-ID in das Supervisor-Portal eingeben und Deine Zeiterfassungsdaten für jeden abgegebenen Monat anzeigen.

Du kannst Deine Referenz-ID auch an mehrere Personen schicken. Alle Personen, die diese ID haben, können Deine Zeiterfassungsdaten anzeigen lassen, wenn sie als Supervisor registriert sind.

{% hint style="warning" %}
Es ist möglich, die Referenz-ID zu ändern, z.B. wenn sich Deine vorgesetzte Person ändert. Bereits abgegebene Reports/Stundenzettel können aber immer unter der alten ID angezeigt werden.&#x20;
{% endhint %}

{% hint style="info" %}
Deine zuständige Führungskraft ist in der Regel die Person, die Dir Deine Aufgaben zuweist und weiß, was Du arbeitest. Das können Professor\*innen sein oder auch Wissenschaftliche Mitarbeiter\*innen, manchmal sollen auch Sekretariate Einsicht in die Zeiterfassungsdaten nehmen dürfen. Wenn Du nicht sicher bist, frage bei der Person nach, bei der Du den Vertrag unterschrieben hast.
{% endhint %}

## Schicht

Als _Schicht_ wird eine zusammenhängende Arbeitszeit bezeichnet.

Für Schichten gelten einige Regeln:

* Eine Schicht gehört immer zu einem Vertrag.
* Eine Schicht darf nicht kürzer als 1 Minute sein.
* Eine Schicht gehört immer zu einem festen Tag/Datum. Wenn Du über Mitternacht hinweg arbeitest, macht Clock daraus automatisch 2 Schichten.
* Schichten können nicht parallel liegen bzw. sich nicht überlappen.

{% hint style="info" %}
Wenn Du eine Schicht über Nacht oder mehrere Tage laufen lässt, erscheint beim Ausclocken ein Hinweis, dass die Schicht ungültig ist. Du kannst die Schicht dann bearbeiten und zum richtigen Zeitpunkt beenden.
{% endhint %}

{% hint style="info" %}
Wenn sich Schichten überlappen, erscheint eine Warnung, und Du musst diesen Konflikt spätestens vor dem Export Deines Stundenzettels beheben. Denn Dich gibt es nur einmal😉
{% endhint %}

_Aktive_ Schichten bezeichnen Schichten, die gerade laufen – z.B. weil Du _eingeclockt_ bist. Aktive Schichten können immer direkt gelöscht werden, falls Du versehentlich eingeclockt hast.

Es ist nicht möglich, eine laufende Schlicht zu bearbeiten, z.B. die Startzeit zu ändern, wenn Du zu spät eingeclockt hast. Du kannst die Schicht aber nach dem Ausclocken korrigieren.

Schichten sind vor allem eine Erleichterung für Dich – beim Abgeben Deiner Arbeitszeitdaten werden alle Schichten eines Tages zusammengerechnet und auf dem Arbeitszeitkonto eingetragen.

## Clocken

_Clocken_ ist das Äquivalent zum Stechen mit einer Stechuhr, also das Beenden oder Starten einer Schicht.

* `Einclocken` beginnt eine Schicht.
* `Ausclocken` beendet eine Schicht.

Der Button zum Ein- und Ausclocken ist immer auf dem _Dashboard_ zu finden. Wenn eine Schicht _aktiv_ ist, wird Dir die aktuelle Laufzeit angezeigt. Du kannst eine laufende Schicht beenden oder auch ganz löschen. Eine geclockte Schicht taucht erst _nach_ dem Ausclocken in Deinem Arbeitszeitkonto auf.

## Arbeitszeitkonto | AZK

Das _Arbeitszeitkonto_ (AZK) ist eine vom Gesetzgeber vorgeschriebene Zusammenfassung Deiner geleisteten Arbeitszeit. Das Arbeitszeitkonto unterliegt besonderen Regeln, z.B. wird darin festgelegt, wie viele Stunden von einem Monat in den nächsten übertragen werden dürfen etc.

Der monatliche Stand Deines AZK wird durch den **Stundenzettel** dargestellt.

Dieser hat Einträge für jeden Tag eines Monats und folgende Spalten

| Datum          | Start                     | Ende                     | Abwesen-heitsgrund | Pause                                                    | Netto-Arbeitszeit         | F/K/U                                             |
| -------------- | ------------------------- | ------------------------ | ------------------ | -------------------------------------------------------- | ------------------------- | ------------------------------------------------- |
| Ein Arbeitstag | Beginn der ersten Schicht | Ende der letzten Schicht | siehe F/K/U        | Summe der "schichtfreien" Zeiten zwischen Start und Ende | Die effektive Arbeitszeit | Zeiten, die Feiertag, Krankheit oder Urlaub sind. |

Einzelne Schichten werden im AZK nicht abgebildet - diese existieren nur Clock-intern und werden beim Export entsprechend zusammengerechnet und im Stundenzettel AZK-konform eingetragen.

### F/K/U

Als Hilfskraft hast Du Anspruch auf Urlaub (U) und Du darfst auch krankgeschrieben (K) sein. Und streng genommen gelten für Dich auch gesetzliche Feiertage (F).

Aktuell kannst Du in Clock Schichten nur als normale `Schicht` (Standard), als `Urlaub` , als`Krank` oder als `Feiertag` markieren. Wenn Du Schichten als `Urlaub` , `Krank` oder `Feiertag` vermerkst, werden deren Zeiten im AZK entsprechend separat vermerkt.

{% hint style="info" %}
An Feiertagen darf laut Arbeitszeitgesetz ([§9 Abs 1 ArbZG](https://www.gesetze-im-internet.de/arbzg/BJNR117100994.html)) nicht gearbeitet werden. Eine Feiertagsschicht anzugeben ist eigentlich nur sinnvoll, wenn Du an diesem Tag regulär gearbeitet hättest - z.B. in einem Dienstplan oder wenn Dein übliches Tutorium auf einen Feiertag fällt.
{% endhint %}

## Report (Stundenzettel)

Um Deine monatlichen Zeiterfassungsdaten abzugeben, musst Du einen **Report** _anfordern_. Diesen kannst Du in Form einer PDF-Datei als "Stundenzettel" herunterladen.

{% hint style="warning" %}
Wenn der `Anfordern`-Button ausgegraut ist, dann hast Du den vorangegangenen Monat vermutlich nicht gesperrt.
{% endhint %}

Du kannst den Report beliebig oft anfordern, z.B. wenn Du noch eine fehlende Schicht nachgetragen hast. Wenn dein Stundenzettel fertig ist und alles richtig aussieht, kannst Du den Monat `Sperren & abgeben`_._

_Sperren_ bedeutet: "Alle Aufzeichnungen dieses Monats sind richtig und ich will nichts mehr ändern." Dann erst kannst Du einen Report für den nächsten Monat anfordern, da der Stand des Arbeitszeitkontos für den automatischen Übertrag in den nächsten Monat gebraucht wird. Du kannst aber schon Schichten im nächsten Monat haben, d.h. Du musst nicht unbedingt den alten Monat sperren, um im neuen Monat zu clocken.

_Abgeben_ bedeutet, dass der Report in den "Zeitspeicher" (TimeVault) übertragen und dort für die gesetzlich vorgeschriebene Frist gespeichert wird. Deine Führungskraft kann dann die Daten einsehen, wenn Du ihr die entsprechende Referenz-ID (siehe oben) des Vertrages übermittelt hast.

## Pausen

Clock macht keine expliziten Pausen, damit es schön einfach bleibt: Entweder Du arbeitest (= es gibt eine Schicht) oder Du arbeitest nicht.

Im AZK werden jedoch Pausenzeiten angegeben, da sie die Grundlage für die Netto-Arbeitszeit darstellen. Wenn Du an einem Tag mehrere Schichten arbeitest, dann wird die "Zeit dazwischen" zusammengezählt als Pausenzeit angenommen. Deine Netto-Arbeitszeit entspricht natürlich weiterhin der Summe Deiner eingetragenen Schichten.

Laut Arbeitszeitgesetz musst Du bei mehr als 6 Stunden Arbeitszeit mindestens 30 Minuten Ruhepause machen und bei mehr als 9 Stunden mindestens 45 Minuten ([§4 ArbZG](https://www.gesetze-im-internet.de/arbzg/__4.html)). Clock zieht Dir diese Pausenzeit automatisch ab - auch, wenn Du die Arbeit nicht unterbrochen hast.

## Benutzer\*in / User

Das bist natürlich Du. Und wir freuen uns, dass Du an Bord bist!

---
description: Clock-Terminologie
---

# Begriffe

Clock verwendet einige besondere Begriffe, die wir hier vorstellen und erklären:

## Vertrag \| Contract

Der _Vertrag_ bildet Deinen realen Arbeitsvertrag in Clock ab.

Als Hilfskraft hast Du mit der Universität einen _Arbeitsvertrag_ abgeschlossen. In diesem steht...

* ...ab wann der Vertrag läuft \(immer der 01. oder 16. eines Monats\)
* ...bis wann der Vertrag läuft \(immer der 15. oder der letzte Tag eines Monats\)
* ...wieviele Stunden Du _durchschnittlich_ im Monat arbeiten musst

In Clock hat ein Vertrag zusätzlich einen _Namen_ \(z.B. "Mathe 2 Tutorium"\), den Du selbst vergeben kannst.

{% hint style="info" %}
Der Vertrag ist die Basis für die Erfassung Deiner Arbeitszeit. Deshalb musst Du immer zuerst einen Vertrag anlegen bevor Du überhaupt Zeiten erfassen kannst.
{% endhint %}

Du kannst mehrere parallele Verträge mit verschiedenen Dienststellen an der Uni haben, die dann auch in Clock unabhängig voneinander sind.

Beim Anlegen eines Vertrages kannst Du einen _Übertrag aus dem vorangehenden Monat_ angeben, wenn Du schon Stunden auf dem Arbeitszeitkonto hast und erst später beginnst, Clock zu benutzen.

Einen Vertrag kannst Du derzeit nicht einfach verlängern, Du musst ihn für die nächste Zeitperiode neu anlegen - dann kannst Du aber einen Übertrag aus dem letzten Vertrag entsprechend angeben.

## Schicht \| Shift

Als _Schicht_ wird eine zusammenhängende Arbeitszeit bezeichnet.

Für Schichten gelten einige Regeln:

* Eine Schicht gehört immer zu einem Vertrag.
* Eine Schicht darf nicht kürzer als 1 Minute sein.
* Eine Schicht gehört immer zu einem festen Tag/Datum. Wenn Du über Mitternacht hinweg arbeitest, macht Clock daraus 2 Schichten.
* Schichten dürfen nicht parallel liegen bzw. sich überlappen.

{% hint style="info" %}
Wenn Du eine Schicht über Nacht oder mehrere Tage laufen lässt, erscheint beim Ausclocken ein Dialog und Du musst entscheiden, wie mit den Schichten umgegangen werden soll. Du kannst entweder die erste oder die letzte - oder alle Schichten behalten. Du kannst jede Schicht natürlich auch im Nachhinein korrigieren.
{% endhint %}

{% hint style="info" %}
Wenn sich Schichten überlappen, erscheint eine Warnung und Du musst diesen Konflikt spätestens vor dem Export Deines Stundenzettels beheben. Denn Dich gibt es nur einmal ;-\)
{% endhint %}

_Aktive_ Schichten bezeichnen Schichten, die gerade laufen - z.B. weil Du _eingeclockt_ bist. Aktive Schichten können immer direkt gelöscht werden, falls Du versehentlich eingeclockt hast.

Es ist nicht möglich, eine laufende Schlicht zu bearbeiten, z.B. die Startzeit zu ändern, wenn Du zu spät eingeclockt hast. Du kannst die Schicht aber nach dem Ausclocken korrigieren.

Schichten sind vor allem eine Erleichterung für Dich - beim Exportieren Deines Stundenzettels werden alle Schichten eines Tages zusammengerechnet und auf dem Arbeitszeitkonto eingetragen.

## Clocken

_Clocken_ ist das Äquivalent zum Stechen mit einer Stechuhr, also das Beenden oder Starten einer Schicht.

* `Einclocken` beginnt eine Schicht.
* `Ausclocken` beendet eine Schicht.

Der Button zum Ein- und Ausclocken ist immer auf dem _Dashboard_ zu finden. Wenn eine Schicht _aktiv_ ist, wird Dir die aktuelle Laufzeit angezeigt. Du kannst eine laufende Schicht beenden oder auch ganz löschen. Eine geclockte Schicht taucht erst nach dem Ausclocken in Deinem Arbeitszeitkonto auf.

## Arbeitszeitkonto \| AZK

Das _Arbeitszeitkonto_ \(AZK\) ist eine vom Gesetzgeber vorgeschriebene Zusammenfassung Deiner geleisteten Arbeitszeit. Das Arbeitszeitkonto unterliegt besonderen Regeln, z.B. wieviele Stunden von einem Monat in den nächsten übertragen werden dürfen etc.

Der monatliche Stand Deines AZK wird durch den **Stundenzettel** dargestellt.

Dieser hat Einträge für jeden Tag eines Monats und folgende Spalten

| Datum | Start | Ende | Abwesen-heitsgrund | Pause | Netto-Arbeitszeit | F/K/U |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Ein Arbeitstag | Beginn der ersten Schicht | Ende der letzten Schicht | siehe F/K/U | "schichtfreie" Zeit zwischen Start und Ende | Die effektive Arbeitszeit | Zeiten, die Feiertag, Krankheit oder Urlaub sind. |

Einzelne Schichten werden im AZK nicht abgebildet - diese existieren nur Clock-intern und werden beim Export entsprechend zusammengerechnet und im Stundenzettel AZK-konform eingetragen.

### F/K/U

Als Hilfskraft hast Du Anspruch auf Urlaub \(U\) und Du darfst auch krankgeschrieben \(K\) sein. Und streng genommen gelten für Dich auch gesetzliche Feiertage \(F\).

Aktuell kannst Du in Clock Schichten nur als normale `Schicht` \(Standard\), als `Urlaub` oder `Krank` markieren. Wenn Du Schichten als `Urlaub` oder `Krank` vermerkst, werden deren Zeiten im AZK entsprechend separat vermerkt.

Feiertage werden derzeit nicht von Clock abgebildet.

## Export \| Report

Um einen Stundenzettel zu exportieren, kannst Du ihn zunächst _anfordern_ und dann in Form einer PDF-Datei herunterladen.

{% hint style="warning" %}
Wenn der `Anfordern`-Button ausgegraut ist, dann hast Du den vorangegangenen Monat vermutlich nicht gesperrt.
{% endhint %}

Da der Stand des AZK auch immer vom vorangegangenen Monat abhängig ist, muss dieser _gesperrt_ werden, um den Stundenzettel für den nächsten Monat exportieren zu können.

Das Sperren bedeutet: "Ich habe den Zettel abgegeben und will nichts mehr ändern." Dann erst kannst Du Stundenzettel für den nächsten Monats exportieren. Du kannst aber schon Schichten im nächsten Monat haben.

## Pausen

Clock macht keine expliziten Pausen damit es schön einfach bleibt: Entweder Du arbeitest \(= es gibt eine Schicht\) oder Du arbeitest nicht.

Im AZK werden jedoch Pausenzeiten angegeben, da sie die Grundlage für die Netto-Arbeitszeit darstellen. Wenn Du an einem Tag mehrere Schichten arbeitest, dann wird die "Zeit dazwischen" als Pausenzeit angenommen. Deine Netto-Arbeitszeit entspricht natürlich weiterhin der Summe Deiner eingetragenen Schichten.

## Benutzer \| User

Der Benutzer - das bist natürlich Du. Und wir freuen uns, dass Du an Bord bist!


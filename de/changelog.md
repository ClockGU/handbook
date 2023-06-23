---
description: Updates und Änderungen an Clock
---

# Changelog

## Release 2021.02

Veröffentlicht am 15.02.2021 - 22:00 Uhr

#### **Neue Features**

* Nachrichten auf dem Dashboard!
* verbessertes Schicht-Formular
  * wiederholbare Schichten (z.B. für wöchentliche Tutorien)
  * verbesserte Uhrzeiteingabe per Tastatur
  * Überprüfung (review) von geplanten Schichten
  * _Letzte Aktivität_ zeigt nur vergangene Schichten
  * Klick auf _Letzte Aktivität_ führt direkt zur Bearbeitung der Schicht
* Neue Schichtansicht
  * Trennung zwischen abgeschlossenen und geplanten (zukünftigen) Schichten
  * transparente Darstellung von überprüften / nicht überprüften Schichten
  * gleichzeitige Bearbeitung mehrerer Schichten (Löschen, Vertrag ändern, überprüfen)
* Kalender
  * nicht überprüfte und zukünftige Schichten werden heller dargestellt

#### **Anpassungen**

* Einwilligung in die Datenverarbeitung (Akzeptieren der Datenschutzerklärung)
* Wochenbeginn am Montag
* abgelaufene Verträge werden überall klarer dargestellt

#### **Fehlerbehebungen**

* Der ausgewählte Vertrag bleibt beim Sprung auf die Kalenderansicht erhalten
* korrekte Berechnung der monatlichen Stundenzahl bei untermonatigem Ein- oder Austritt
* korrekte Anzeige der noch offenen Stunden/Monat
* korrekte Berücksichtigung des Vertragsendes
* Korrekturen und Übersetzungen in Anzeigetexten
* kleinere Verbesserungen und Fehlerkorrekturen
* an Schichten vergebene Tags können auch wieder gelöscht werden

## Fix 2021.02a

#### Fehlerbehebungen

* Der Download der in Clock gespeicherten Daten (nach DSGVO / GDPR) funktioniert nun für alle User
* korrekte Berechnung von Schichten, die in einen anderen Vertrag verschoben wurden

## Release 2021.08

Veröffentlicht am 16.08.2021 - 18:15 Uhr

**Neue Features**

* leichtere Uhrzeiteingabe per Tastatur
* Hervorhebung von falschen Daten im Schichtformular
* Der Dateiname des Datenexports (nach DSGVO / GDPR) enthält den eigenen Namen
* Feiertage können als Schichttyp ausgewählt werden
* Wochen- und tagesbasierte Fortschrittsanzeige (Hinweis: derzeit werden nur abgeschlossene und überprüfte Schichten berücksichtigt.)

**Anpassungen**

* Anpassung der Datenschutzerklärung an die tatsächliche Verarbeitungspraxis
* verbesserte Datenschutz-Dialoge
* bessere Darstellung des _Einstellungen_-Dialogs auf kleinen Bildschirmen
* transparentere Anzeige von überprüften Schichten im Schichtformular
* Abwesenheitsgrund wird übersetzt angezeigt
* verbesserte Uhrzeiteingabe im Schichtformular per Tastatur

**Fehlerbehebungen**

* 404-Blockade nach dem Sperren des aktuellen Monats behoben
* Schichtansicht und Reportansicht springen bei Änderungen an vergangenen Monaten nicht mehr zum heutigen Monat
* Das Dashboard aktualisiert sich bei Änderungen aus den _Letzten Aktivitäten_ heraus korrekt
* Wiederholte Schichten werden mit dem korrekten "überprüft"-Status gespeichert (dieser Fehler trat vor allem bei vergangenen Schichten auf, die in die Zukunft wiederholt werden)
* Korrekturen und Übersetzungen in den Anzeigetexten
* kleinere Verbesserungen und Fehlerkorrekturen

## Release 2022.06

**Neue Features**

* Onboarding:
  * "Tour" mit Erklärungen zu den wichtigsten Clock-Funktionen
  * "Onboarding nicht mehr anzeigen"-Funktion
* verbesserte Zeiteingabe der Stundenzahl in Verträgen
  * Unterstützung von einfachen Eingaben (h; hmm; ...)
  * Unterstützung von dezimalen Minuten bei der monatlichen Arbeitszeit
* Schichten:
  * Schichttypen werden durch farbige Icons dargestellt
  * Geplante bzw. manuell angelegte Schichten werden mit einem "live"-Marker angezeigt, wenn sie zum aktuellen Zeitpunkt gültig sind (nicht zu verwechseln mit live geclockten Schichten)
* Schichttabelle:
  * verbesserte Toolbar mit Icons für Sammelaktionen
  * Schnelles Überprüfen (per Klick auf das X-Symbol)
  * Anzeigen und Filtern/Suchen von Tags und Notizen
  * Anzeige der Gesamtzeit der vergangenen und zukünftigen Schichten
* Warnungen auf der Fortschrittsanzeige:
  * Übertrag (mehr als 100% der monatlichen Arbeitszeit überschritten)
  * maximal erlaubte Mehrarbeitsstunden (50%) überschritten
  * maximale tägliche Arbeitszeit (8h) überschritten

**Anpassungen**

* Zustimmung zur Datenschutzerklärung vor dem Anlegen des ersten Vertrags im Onboarding
* verbesserte Anzeige, wenn kein Vertrag angelegt wurde (kein automatischer Neustart des Onboardings)
* Übertrag kann nicht verändert werden, wenn Monate gesperrt sind
* Bei Überschneidungen wird die Zahl der beteiligten Schichten angezeigt und nicht die einzeln gezählten Überschneidungen
* Archivbereich für abgelaufene Verträge
* maximale Vertragslaufzeit von 7 Monaten
* verpflichtende Angabe der Personalnummer für den Export
* Bestätigungsdialog bei Änderung der Personalnummer

**Fehlerbehebungen**

* fehlende Dashboard-Aktualisierung nach geteilten Schichten behoben
* korrekte Sortierung in der Schichttabelle
* Mitternachts-Clock-out Bug behoben
* Fehler bei wiederholten Schichten über Jahreswechsel behoben
* Schichten können nicht mehr in abgelaufene Verträge verschoben werden
* Korrekturen und Übersetzungen in den Anzeigetexten
* kleinere Verbesserungen und Fehlerkorrekturen

## Release 2023.04

**Neue Features**

* Arbeitszeitvalidierungen gemäß dem deutschen Arbeitsrecht (Arbeitszeitgesetz) und im Rahmen der Selbstverpflichtungserklärung der Goethe-Universität zu den Arbeitsbedingungen für studentische Hilfskräfte
  * Warnungen, falls die Buchung im Konflikt mit den gesetzlichen Vorgaben steht
  * An Sonn- und Feiertagen dürfen keine regulären Schichten geclockt werden (§9 ArbZG)
* Bei Krankheit oder Urlaub ist der Schichttyp tageweise exklusiv.
* Formular für den schnellen Kontakt zur Ombudsperson für Studierende
* Das FAQ gibt es nun auch auf Englisch
* Nachrichten gibt es nun ebenfalls auf Englisch

**Anpassungen**

* Arbeitsverträge haben keine zeitliche Laufzeitbeschränkung mehr
* Die Formulare für Feedback und Ombudsperson setzen den User in CC.
* Eine Überlappung von Schichten wird über einen Vertrag hinaus für einen User nicht mehr akzeptiert.
* Neue Schichten in der Vergangenheit werden automatisch als "überprüft" gespeichert.
* Neue Schichten in der Zukunft werden immer als "nicht überprüft" gespeichert.
* Gesetzliche Mindestpausen werden bei Bedarf automatisiert von der gebuchten Arbeitszeit abgezogen (§4 Arbeitszeitgesetz).
* Die Personalnummer ist nicht mehr zwingend erforderlich für einen Stundenzettelexport

**Fehlerbehebungen**

* Korrekturen und Übersetzungen in den Anzeigetexten
* verschiedene kleinere Verbesserungen und Fehlerkorrekturen

**Hinweise**

* Im Hintergrund wurde die Datenstruktur umgebaut, was sich für die Nutzer:innen wenn, dann durch schnellere Zugriffszeiten bemerkbar machen sollte.

## Release 2023.05

**Neue Features**

* Wenn geclockte Schichten über Mitternacht hinausgehen, wird die Endzeit auf 23:59 gesetzt. Die Schicht muss nach dem Ausclocken nochmals bearbeitet werden.
* In den ersten 5 Tagen eines Monats wird ein Hinweis angezeigt, der an den Export des Stundenzettels erinnert.

**Anpassungen**

* verbesserte Anzeige der Nachrichten
* Die Spracheinstellungen können innerhalb der App in vielen Dialogen geändert werden.

**Fehlerbehebungen**

* Fehler in den Stundenberechnungen wurden behoben.
* Auch bei untermonatigem Vertragsbeginn werden korrekte Zeiten angezeigt.
* Korrekturen und Übersetzungen in den Anzeigetexten
* verschiedene kleinere Verbesserungen und Fehlerkorrekturen

## Release 2023.06

**Anpassungen**

* Für wiederholte Schichten gibt es keine Auswahl mehr von Wiederholungen am Wochenende (§9 ArbZG).
* Beim Löschen von Verträgen wird darauf hingewiesen, dass alle Schichten, die zu diesem Vertrag gehören, ebenfalls gelöscht werden.
* Bei geclockten Schichten, die über 00:00 Uhr eines Tages gehen, wird ein verbesserter Hinweistext angezeigt.

**Fehlerbehebungen**

* Verträge können nun auch mit einem negativen Übertrag angelegt werden.
* Korrekturen und Übersetzungen in den Anzeigetexten
* verschiedene kleinere Verbesserungen und Fehlerkorrekturen

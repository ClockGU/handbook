---
description: Clock terminology
---

# Terminology

Clock uses several special concepts we would like to introduce and explain, along with the technical terms we chose.

## Contract

A _Contract_ \(German: Vertrag\) represents your actual contract of employment within the Clock system.

As student assistant or graduate research assistant, you signed an employment contract with the University. It specifies:

* ...when the period of employment begins \(always on the 1st or 16th of a given month\)
* ... when the period of employment ends \(always the 16th or the llast day of a given month\)
* ...how many hours you are _on average_ expected to work.

Each Contract also has a _name_ \(e.g. "Maths 2 Tutorial"\) which you may choose yourself. It will be printed on your time sheet.

{% hint style="info" %}
A Contract is the basis for recording your working hours. That's why you always have to create a Contract before you can do anything else in Clock.
{% endhint %}

In some cases, you may have several parallel contracts with different departments of the University. These individual Contracts are kept separate within Clock, as well.

Upon creating a Contract, you may enter the hours to be carried over from the previous month. This is useful if you start using Clock at a later time.

It is not \(yet\) possible to simply extend an existing Contract \(although we are working on it\). Technically, you will have to define a new Contract for each new period of employment. Existing time budgets in your account may be _carried over_ by using the respective option.

## Shift

The term _Shift_ denotes a certain amount of consecutive working hours.

There are certain rules for defining Shifts:

* A Shift is always linked to a specified Contract.
* The minimum duration for each Shift is 1 minute.
* A Shift is always connected to one specified day/date. In case you keep working past midnight, Clock records this as two Shifts.
* Two individual Shifts may not run in parallel or overlap.

{% hint style="info" %}
If you record a Shift that carries on past midnight or comprises several days, Clock will display a dialog upon clocking out and asks you how to proceed with the resulting Shifts. You may keep either the first, the last, or all Shifts. Of course, you are always free to edit the record for any Shift later on.
{% endhint %}

{% hint style="info" %}
If two Shifts happen to overlap, a warning is displayed, and you need to resolve this conflict before you can export your time report. That's because you're unique ;-\)
{% endhint %}

_Active_ Shifts are currently running, e.g. because you are clocked in at the moment. Active Shifts may always be deleted directly, in case you logged in by mistake.

It is impossible to edit the record for a hift while it is still active, e.g. because you logged in too late. You may change the record after terminating an active Shift, however \(and we are working on a way to improve this\).

Shifts are primarily intended to assist you in keeping track of your record. Once you export your time record, all the Shifts for each day are added up and displayed as a sum on your time sheet.

## Clocking

_Clocking_ is the equivalent of logging on or off at an actual time clock, i.e. beginning or ending a Shift.

* `clock in` starts a Shift.
* `clock out` terminates a Shift.

The button for clocking in or out is invariably located at the Dashbord. When a Shift is _active_, its current duration is displayed there. You may end an active Shift or delete it altogether. A Shift recorded in Clock appears in your account only after you _clocked out_.

## Working Time Account \| WTA

The Working Time Account \(German: Arbeitszeitkonto or "AZK"\) is a legally mandated summary of your working time. The Working Time Account is subject to a number of regulations, specifying e.g. how many hours may be carried over from one month to the next, and many more details of this kind.

The current state of your Working Time Account is represented on your time sheet for each month.

The time sheet contains an entry for each individual day. An entry is composed of a several colums which translate as:

\| Datum \| Date of the respective working day\) \| \| Start \| Begin of the first Shift \| \| Ende \| End of the last Shift \| \| Abwesenheitsgrund \| Reason of absence, see "F/K/U" \| \| Break \| The summed up amount of time between shifts \| \| Netto-Arbeitszeit \| The sum of all Shifts \| \|F/K/U \| A flag for Shifts, meaning public holidays \(F\), Sick \(K\) and vacation \(U\) \|

Shifts are not represented individually in your Working Time Account: These exist only within the Clock system itself and are summed up during the export process to be documented in the legally required way on your time sheet.

### F/K/U

As a student assistant or graduate research assistant, you are entitled to a certain amount of days off \(U, German: _Urlaub_\) which can be converted into hours, and you are entitled to sick leave \(K, German: _Krankschreibung_\) whenever necessary. Strictly speaking, the regulations concerning public holidays \(Feiertage, F\) apply to you as well.

Currently, you may only register Shifts in the form of a standard Shift _\(Shift\)_, as a personal holiday _\(Vacation\)_ or as a period of sick leave _\(Krank\)_. If you record Shifts as vacation or a period of sick leave, these Shifts are documented separately in your WTA in specific subdivisons.

Official holidays are currently not implemented in Clock.

## Exporting a Report \(Time Sheet\)

You can generates your time sheet by requesting it and download it in the form of a PDF-file.

Since the current state of your Working Time Account inevitably depends on the previous month, the previous report needs to be _locked_, before the report for the current month can be exported.

{% hint style="warning" %}
If the download option is not available, make sure the previous month has been locked.
{% endhint %}

_Locking_ a report tells Clock: "I handed this time report in and do not want to change it anymore." Only after you lock the _previous_ report you may export the _current_ report for this month. However, you may record Shifts for the current month before you lock the previous report.

## Breaks

Clock knows nothing of breaks, to keep things simple -- at least, it does not report them explicitly: Either you are currently at work \(i.e. a Shift exists\) or you are not.

In your Working Time Account, however, pauses are documented explicitly because they need to be considered in calculating the effective working time. In case you work several Shifts in one day, the "time in between" is considered a break. Your effective \(net\) working time nevertheless amounts to the sum of your recorded Shifts, of course.

## User

The User -- that's no one else but you! And we're glad that you're part of the crew.


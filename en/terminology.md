---
description: Clock terminology
---

# Terminology

Clock uses several special concepts which we introduce and explain here, along with the technical terms we chose.

## Contract

A _Contract_ (German: Vertrag) is the digital representation of your actual contract of employment within.

As student assistant, you signed an employment contract with the University. It specifies:

* ...when the period of employment begins (always on the 1st or 16th of a given month)
* ... when the period of employment ends (always the 16th or the llast day of a given month)
* ...how many hours you are _on average_ expected to work.

Each Contract also has a _name_ (e.g. "Maths 2 Tutorial") which you may choose yourself. This name will be stored on your time recordings.

{% hint style="info" %}
A Contract is the basis for recording your working hours. That's why you always have to create a Contract before you can do anything else in Clock.
{% endhint %}

You may have several parallel contracts with different departments of the University. These individual contracts are kept separate within Clock, as well - as you are required to record your working time independently.

Upon creating a Contract, you may enter the hours to be carried over from the previous month. This is useful if you start using Clock at a later time and have already recorded working time outside of Clock. In that case, the digital contract needs to start at the same time as your usage of Clock to ensure that the carryover is calculated correctly.

#### Extend or change your Contract

If your contract is just extende without changing the average working hours, you can just edit the Contract and set it's end date to the new value and continue clocking on this contract. If your working hours change, you need to define a new Contract for the next time period and enter the carryover manually.

The Reference ID

Your monthly time recording data is stored digitally as a _report_ (see below) in the TimeVault database and saved there for the prescribed period (2 years).&#x20;

Since we cannot yet retrieve a logical connection between your supervisor and your contract, you must establish this link by yourself. There is a reference ID for this, which you must send to your supervisor once (for each contract). Your supervisor can then enter the reference ID in the Clock Supervisor portal and view your time recording data for each month submitted.&#x20;

You can also send your reference ID to several people. Everyone who has this ID can view your time recording data if they are registered as a supervisor.



{% hint style="warning" %}
It is possible to change the reference ID, e.g. if your supervisor changes mid-contract. However, reports that have already been submitted will always be displayed under the old ID.
{% endhint %}

{% hint style="info" %}
Your responsible manager is usually the person who assigns you your tasks and knows what you are working on. This may be a professor or research assistant, sometimes secretariats should also be allowed to view the time recording data. If you are not sure who your supervisor is, ask the person with whom you signed the contract.
{% endhint %}

## Shift

The term _Shift_ denotes a certain amount of consecutive working hours.

There are certain rules for defining Shifts:

* A Shift is always linked to a specified Contract.
* The minimum duration for each Shift is 1 minute.
* A Shift is always connected to one specified day/date: In case you keep working past midnight, Clock will notify you about an error.
* Two individual Shifts can not run in parallel or overlap.

{% hint style="info" %}
If you record a Shift that carries on past midnight or comprises several days, Clock will display an error upon clocking out. You can then edit the Shift and set the correct end time.
{% endhint %}

{% hint style="info" %}
If two Shifts happen to overlap, a warning is displayed, and you need to resolve this conflict before you can export your time report. That's because you're unique ;-)
{% endhint %}

_Active_ Shifts are currently running Shifts you started by clocking in. Active Shifts may always be deleted directly, in case you logged in by mistake.

It is not possible to edit the record for a Shift once it is active, e.g. because you logged in too late. You can change the record after terminating an active Shift and save a new start time.

Shifts are primarily intended to assist you in keeping track of your record. Once you export your time record, all the Shifts for each day are added up and displayed as a sum on your time sheet.

## Clocking

_Clocking_ is the equivalent of logging on or off at an actual time clock, i.e. beginning or ending a Shift.

* `clock in` starts a Shift.
* `clock out` terminates a Shift.

The button for clocking in or out is located at the Dashbord. When a Shift is _active_, its current duration is displayed there. You may end an active Shift or delete it altogether. A Shift recorded in Clock appears in your account only after you _clocked out_. A clocked Shift is always considered as _reviewed_.

## Working Time Account (WTA)

The Working Time Account (German: Arbeitszeitkonto or "AZK") is a legally mandated summary of your working time. The Working Time Account is subject to a number of regulations, specifying e.g. how many hours may be carried over from one month to the next, and many more details of this kind.

The current state of your Working Time Account for each month can be represented as timesheet.

The timesheet contains an entry for each individual day. An entry is composed of a several colums which translate as:

| Datum                              | Start                    | End                   | Abwesenheitsgrund             | Pause                                                           | Netto-Arbeitszeit                                          | F/K/U                                             |
| ---------------------------------- | ------------------------ | --------------------- | ----------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------------- |
| Date of the respective working day | Start of the first Shift | End of the last Shift | Reason of Absence (see F/K/U) | sum of all non-shift times between start and end of all shifts. | daily sum of all Shifts = the effective daily working time | sum of all vacation, holiday ot sick leave Shifts |

Shifts are not represented individually in your Working Time Account: These exist only within the Clock system itself and are summed up during the export process to be documented in the legally required structure on your time sheet.

### F/K/U

As a student assistant, you are entitled to a certain amount of days off (**U**, German: _Urlaub_) which can be converted into hours. You are also entitled to sick leave (**K**, German: _Krankschreibung_) whenever necessary. Strictly speaking, the regulations concerning public holidays (**F**, Feiertage) apply to you as well.

Currently, you may only register Shifts in the form of a standard Shift _(Shift)_, as a personal holiday _(Vacation)_ or as a period of sick leave _(sick)_ or as a bank holiday. If you record Shifts as vacation, bank holiday or a period of sick leave, these Shifts are documented separately in your WTA in specific subdivisons.

{% hint style="info" %}
According to the Working Hours Act ([§9 Para. 1 ArbZG](https://www.gesetze-im-internet.de/arbzg/__9.html)), it is not permitted to work on public holidays. It only makes sense to indicate a public holiday shift if you would have worked regularly on that day - e.g. in a rota or if your usual tutorial falls on a public holiday.
{% endhint %}

## Report (Timesheet)

To hand in your monthly time recording, you need to _request_ a **Report**. You can also download it as a PDF-file.

{% hint style="warning" %}
If the download option is not available, make sure the previous month has been locked.
{% endhint %}

You can request the report as often as you like, e.g. if you have added a missing shift. When your timesheet is finished and everything looks correct, you can `lock & submit` the month.&#x20;

_Locking_ means: ‘All records for this month are correct and I don't want to change anything.’ Only then can you request a report for the next month, as the status of the working time account is needed for the automatic carryover to the next month. However, you can already have shifts in the next month, i.e. you do not necessarily have to block the old month in order to clock in the new month.&#x20;

_Submitting_ means that the report is transferred to the TimeVault databse and stored there for the legally prescribed period. Your supervisor can view the data if you have sent them the corresponding reference ID (see above) for the contract.

## Breaks

Clock does not take any explicit breaks to keep things nice and simple: Either you work (= there is a shift) or you do not.&#x20;

However, break times are specified in the AZK, as they form the basis for the net working time. If you work several shifts in one day, the ‘time in between’ is summed up as a total break time. Of course, your net working time still corresponds to the sum of your entered shifts.&#x20;

According to the Working Hours Act, you must take at least a 30-minute break if you work more than 6 hours and at least a 45-minute break if you work more than 9 hours ([§4 ArbZG](https://www.gesetze-im-internet.de/arbzg/__4.html)). Clock automatically deducts this break time - even if you have not interrupted your work. You will of course receive a warning.

## User

The User - that's no one else but you! And we're glad that you're part of the crew.

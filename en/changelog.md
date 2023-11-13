---
description: Updates und changes
---

# Changelog

## Release 2021.02

Released Feb. 15, 2021 - 22:00

### New Features

* Messages on the Dashboard!
* improved Shift form
  * recurring Shifts (e.g. for weekly tutorials or fixed work schedules)
  * improved time entry by keyboard
  * review of scheduled Shifts
  * _last activity_ displays only past Shifts
  * clicking a Shift on the _last activity_ card opens the edit dialog
* New Shift View
  * past and future (scheduled) Shifts are separated
  * better display of reviewed / unreviewed Shifts
  * batch editing of multiple Shifts (delete, assign to Contract, review)
* Calendar
  * unreviewed and future Shifts are displayed in a lighter tone

### Modifications

* data storage consent (Accept the privacy agreement)
* the week begins on monday
* better display of expired Contracts‌

### Bugfixes

* The selected contract remains being selected after switching views/tabs
* correct computation of monthly work time if a Contract starts/ends in the middle of a month
* correct display of remaining hours per month
* correct treatment of a Contract's end date
* corrections and translations
* Smaller corrections and fixes
* Shift tags may be deleted

## Fix 2021.02a

### Bugfixes

* download of your own data (GDPR) works for all Users
* correct computation of Shifts that are moved to another Contract

## Fix 2021.08

Released Aug. 16, 2021 - 18:15&#x20;

### New Features

* simplified time input by keyboard
* invalid dates in shift forms are highlighted
* GDPR-export filename contains user's name
* new shift type _bank holdiay_
* weekly and daily progress (note: only saved and reviewed shifts are included)

### Anpassungen

* privacy information adapted to actual data processing
* improved privacy dialog
* improved _settings_ menu for smaller screens
* improved display of a shift's review status
* translation of worksheet export

### Fehlerbehebungen

*   fixed 404-blocking error after locking the actual month

    shift and report views remember stay in the last-edited month upon update.
* correct update of dashboards after modification of _last activity_ shifts
* repeated shifts are saved with a correct review status
* corrections and translations
* Smaller corrections and fixes

## Release 2022.06

**New Features**

* Onboarding
  * quick tour featuring the most important Clock concepts
  * "do not show onboarding"-checkbox
* improved worktime input in contract form
  * support of simple entries (h; hmm; ...)
  * support of decimal minutes (h,mm)
* Shifts:
  * colored icons for Shift types (holiday, sick leave, ...)
  * scheduled and manually generated shifts are marked with a "live"-tag if they are presently valid (not to be confused with live-clocked Shifts)
* Shifts table:
  * improved bulk action interface with icons
  * quick review (click on X symbol to review shift)
  * display and filter/search notes and tags
* warning messages on the dashboard progress card:
  * carryover (more than 100% monthly worktime)
  * maximum allowed carryover into next month (50%) exceeded
  * maximum daily worktime (8h) exceeded

**Modifications**

* accept privacy agreement before saving any data (i.e. first contract in onboarding)
* improved display if no contracts exist (no automatic reroute to onboarding)
* carryover worktime can not be edited after locking the first months (consistent carryover)
* show number of overlapping shifts instead of counting all individual collisions
* archive section for expired contracts
* set the maximum duration of a new contract to 7 months
* personnel number is mandatory prior to export
* confirmation on personnel number modification

**Bugfixes**

* fix dashboard not refreshing after split shift action
* correct sort order for dates and times in Shift table view
* fix midnight clock out edge case
* fix repeated shifts breaking across turn of the year
* shifts can no longer be assigned to expired contracts
* corrections and translations
* smaller corrections and fixes

## Release 2023.04

**New Features**

* Work times are now validated according to German legal requirements (Working Time Act a.k.a. ArbZG) and to the university's self-commitment declaration on working conditions for student workers
  * a warning will be displayed if your working hours conflict with the Working Time Act
  * no regular shifts are allowed on sundays and bank holidays (§9 ArbZG)
* shifts of the type "sick" "holiday" are mutually exclusive on a given day
* contact form to reach the ombudsperson for student affairs
* The FAQ are now available in English
* Messages are now available in English

**Modifications**

* the runtime of contracts is not limited
* contact forms also send a mail in cc to the user
* overlapping of shifts is not allowed across contracts
* new shifts on a past date will automatically be saved as "reviewed"
* new shifts in the future will not be saved as "reviewed"
* breaks will automatically be subtracted according to the Working Time Act (§4 ArbZG) - this applies to single hifts longer than 6 hours.
* The personnel number is no longer required to export your timesheet

**Bugfixes**

* corrections and translations
* smaller corrections and fixes

**Hints**

* The data structure has been massively rebuild and Clock should show faster responses
* Please report all errors and bugs as soon as possible!

## Release 2023.05

**New Features**

* Clocked shifts running past midnight will be set to end at 23:59 and must be edited before saving.
* Users are reminded to export their time sheets during the first 5 days of a month.

**Modifications**

* improved message display
* Language settings can be changed from many views within the app.

**Bugfixes**

* fix general errors in report calculations
* fix errors in report calculations for contracts starting on the 16th of a month
* minor corrections and fixes
* revised translations and corrections

## Release 2023.06

**Modifications**

* repeating shift rules exclude the weekend (§9 ArbZG - no work on sundays)
* new warning that all shifts will be deleted if the associated contract is deleted
* improved message display for shifts past midnight.

**Bugfixes**

* allow negative carryover value in contracts
* minor corrections and fixes
* revised translations and corrections

## Release 2023.07

**Modifications**

* consistent and sufficient size for dialogs
* The inital carryover can not be modified if a month is locked.
* Shifts with warnings are highlighted with an exclamation mark.
* The standard date for new Shifts matches the selected month in the shift table or the calendar.
* The repeating rules of scheduled Shifts allows excludes weekends and allows weekday repetitions only.
* Scheduled shifts will be qualified by their start time and correctly displayed as actually running shifts.

**Bugfixes**

* All repeating shifts will be generated.
* "Holiday" shifts can only be saved on bank holidays.
* The automatic subtraction of breaks is correctly reported on the worktime sheet.
* minor corrections and fixes
* revised translations and corrections

## Release 2023.10

**New Features**

* Clock goes dark! Introducing an new Dark Theme for the user interface
* User data will be deleted one month afther the HRZ-account expires

**Modifications**

* Optimised mail handling for feedback messages with the HRZ mail server
* Optimised representation for formatted messages

**Bugfixes**

* Alle months are accessible upon changing the contract's start/end dates
* carryover is only shown once

## Release 2023.11

**New Features**

* improved date switcher in caldendar view (weekly and monthly)

**Modifications**

* "Add Shift" form
  * improved default date, especially with contracts starting on the 16th of a month
  * form reacts to main view's selected contract
  * all contracts shown and labelled (expired & future) for more transparency
  * selecting a past contract invalidates the form

**Bugfixes**

* The problem with the GDPR-export have been solved.
* All snack notifications are shown.

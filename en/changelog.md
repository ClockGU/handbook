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

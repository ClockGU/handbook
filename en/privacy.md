---
description: What about my data?
---

# Privacy

Clock is a web app for individual users.

This implies that Clock may only be used with a user account and a password because your recorded working hours are nobody's business but _yours_.

This also implies, however, that the data you enter is saved somewhere. This chapter explains, which data are concerned.

## Collected data

All data relating to you as a user, and all the data you enter, respectively, is stored in a _database._ This includes above all:

* The data implicated in your user account:
  * Login name\*
  * HRZ- E-mail address\*
  * Your full name\*
  * Personnel Number \(assigned to you by the University\)
  * Creation date \(equals your first login with Clock\)
  * Last modification \(Date and user\)
* The data for each of the Contracts you created in Clock:
  * Name of the Contract
  * Date of beginning and expiry
  * Number of working hours expected
  * creation and last modification \(Date and User\)
* The working hours you documented using Clock
  * Shift data \(Date & Time for begin and end of each shift\)
  * Contract the Shift belongs to
  * Shift type \(\_s\_hift, \_v\_acation, \_s\_ick leave\)
  * Notes and _tags_ \(entered by yourself\)
  * Creation and modification dates
  * Shift status \(scheduled / reviewed / exported\)
* The "Reports" which are monthly summaries of your working hours
  * Date \(month and year\)
  * actual working Hours
  * Contract the report belongs to
  * Creation and modification dates

From all this data, the Time Sheets are generated and made available to you for download. These PDF files are not stored in the database, but created anew with every Time Sheet you request.

_\*\) This data is retrieved from the Central Authentication Service \(CAS\) of the HRZ \(Hochschulrechenzentrum, the University's IT service provider\) when you log in for the first time. Your HRZ password is not saved in our Clock database._

{% hint style="info" %}
Your email-address is provided to us by the HRZ CAS-Server and may differ from your usual address. Your @stud-address is just an alias \(alternative name\). The address saved in our system will have the form &lt;username&gt;@uni-frankfurt.de .
{% endhint %}

## Which other items of data are saved?

Whenever you access the service via internet, your internet provider as well as the Clock server will routinely save access data \(IP address and time of access\). However, these details are not stored in the Clock database.

The login process with Clock is conducted via the Central Authentication Service \(CAS\) of HRZ, which stores a Cookie in your browser once your login has been successfully completed.

Clock itself does not use Cookies, but it employs your browser's local storage to place a login token there \(which is a similar technology\). Whenever you visit Clock, a request to CAS is sent, to verify that your access tokens are still valid and you are using a proper login. If such a token does not exist, you are required to login again on the CAS server.

## Where is my data located?

The Clock database is located on a server at HRZ, administered by the Clock Team and subject to the standard security guidelines of the HRZ.

## Who can view my data?

The simple answer is: Only you can access your data.

The full answer is: the administrators in charge of Clock and its future development need to be able to access the database for technical reasons and can not be technically barred from viewing your data.

They will not access any data concerning your individual working hours without asking you, or acting on your request.

## How can I view my own data?

Clock only contains the data you entered there yourself: either manually \(by setting up a Contract\) or by clocking Shifts. You can always view these entries, this idea of transparency is largely what Clock is about.

Likewise, you can view the data stored in your user account \(even those items you cannot change\).

## How can I delete my data?

You can always delete individual Shifts yourself, as long as the month concerned has not been blocked yet.

You can delete all your data completely by deleting your entire account \(cf. "Right to erasure", GPDR Art 17\). To confirm this step, you will have to enter your e-mail address. This address may look different from the one you usually use but it will be displayed - it is just to make the step complicated enough so it does not happen by accident.

Of course, deleting your Clock account does not affect your HRZ account in any way.

{% hint style="info" %}
For technical reasons, your data remains in our database backup. In the event of a system recovery following data loss, your deleted data will not be restored
{% endhint %}

{% hint style="danger" %}
A deleted account cannot be recovered! All your Contracts and Shifts will be gone.
{% endhint %}

## How can I export all my personal data?

As required by the GDPR \(Art. 15 & 20\) you can export all Clock data into a customary machine-readable format \(JSON\).

You can find this feature in the _Settings_ \(GDPR\).

## Can I trust you on any of these issues?

Clock is a project by students for students: in all agreements with official representatives of the University \(Human Resources / PersonalServices\), we have insisted on that, unequivocally.

Moreover, Clock is _Open Source_: All functional components of code and all information is publicly available, so it can be reviewed by people with the respective programing skills.

But of course, this is all about trust. You're welcome to get in touch with us any time: [mailto:clock-kontakt@dlist.uni-frankfurt.de](https://github.com/ClockGU/handbook/tree/c6780545131183b61f042c6c884a9e1316ca60b5/en/clock-kontakt@dlist.uni-frankfurt.de) or via the University's [Rocket.Chat](https://chat.studiumdigitale.uni-frankfurt.de/channel/clock_user).


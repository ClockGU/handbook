# Technological Aspects

Clock is a *Web App* consisting of several components:

### The Backend

That's what users won't get to see. The backend includes:

-   the databank (storing all data)
-   the interface (for recovering and saving the data)

The Clock-Database is based on [PostGreSQL
9.4+](https://www.postgresql.org/). The interface has been realised
using the
[Django-REST](https://www.django-rest-framework.org/)-Framework. Such an
interface is also called an *API* (Advanced Programming Interface).

### Frontend

That's what you as a user get to see: the *User Interface* (*UI*). Das
Frontend communicates with the databank via the *API*.

The Frontend has been realised using the Javascript Framework
[Vue.js](http://vuejs.org), which allows developers to build web
applications that run in every (modern) browser.

We (nearly) all use apps frequently -- on mobile and stationary devices
-- and there are accordingly many ways to design an app's user
interface.

For the most part, we comply with Google's design language [Material
Design](http://material.io), which has become something like a standard
on the web.

These guidelines specify the visual design of individual components, but
also the positioning of menus, buttons etc. They foster logic,
consistency and clarity.

To realise Material Design using Vue.js, the Design Library
[Vuetify](http://vuetifyjs.com) has been employed.

## Collaboration 

If you know something about technologies used in the Frontend and the
Backend, and would like to talk the matter over with us, or contribute
something to the project, feel free to contact us via:
<clock-kontakt@dlist.uni-frankfurt.de> oder via the GU-Rocketchat:
[clock_user](https://chat.studiumdigitale.uni-frankfurt.de/channel/clock_user).

Clock's source code "resides" on Github: <https://github.com/ClockGU>.

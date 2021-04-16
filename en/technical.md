# Technological Aspects

Clock is a _Web App_ consisting of several components:

### The Backend

That's what users won't get to see. The backend includes:

- the database (where all data is stored)
- the interface (to access and update the database)

The Clock-Database is based on [PostGreSQL 9.4+](https://www.postgresql.org/). The interface has been realised
using the [Django-REST](https://www.django-rest-framework.org/)-Framework. Such an interface is also called an _API_ (Advanced Programming Interface).

### Frontend

That's what you as a user get to see: the _User Interface_ (_UI_). The Frontend communicates with the databank via the _API_.

The Frontend has been realised using the Javascript Framework [Vue.js](http://vuejs.org), which allows developers to build web applications that run in every (modern) browser.

We (nearly) all use apps frequently -- on mobile and non-mobile devices -- and there are accordingly many ways to design an app's user interface.

For the most part, we comply with Google's design language [Material Design](http://material.io), which has become something like a standard on the web.

These guidelines specify the visual design of individual components, but also the positioning of menus, buttons etc. They foster logic, consistency and clarity.

To realise Material Design using Vue.js, the Design Library [Vuetify](http://vuetifyjs.com) has been employed.

## Collaboration

If you know something about the technologies used in the Frontend and the Backend, and would like to chat with us, or contribute something to the project, feel free to contact us via:
[clock-kontakt@dlist.uni-frankfurt.de](mailto:clock-kontakt@dlist.uni-frankfurt.de) or via [Rocket.Chat](https://chat.studiumdigitale.uni-frankfurt.de/channel/clock_user).

Clock's source code "resides" on [Github](https://github.com/ClockGU).

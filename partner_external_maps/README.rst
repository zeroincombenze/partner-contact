[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/partner-contact/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)
































































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

Partner External Maps
=====================

In the old days of Odoo/Odoo, back in version 6.1, there was an official *google_map* module ; this module added a *Map* button on the partner form view and, when the user clicked on that button, it would open a new tab on its web browser and go to Google Map with a search on the address of the partner.

This module aims at restoring this feature with several improvements:

* each user can select the map website he wants to use in its preferences

* there are now two buttons on the partner form view: one to open a regular map on the address of the partner, and another one to open an itinerary map from the start address configured in the preferences of the user to the address of the partner.

This module supports several map websites:

* `Google Maps <https://www.google.com/maps>`

* `OpenStreetMap <https://www.openstreetmap.org/>`

* `Bing Maps <https://www.bing.com/maps/>`

* `Here Maps <https://www.here.com/>`

* `MapQuest <http://www.mapquest.com/>`

* `Yahoo! Maps <https://maps.yahoo.com/>`

If the module *base_geolocalize* from the official addons is installed on the system, it will use the latitude and longitude to localize the partner (instead of the address) if this information is present on the partner.

Installation
------------




Configuration
-------------





If you want to create additionnal map websites, go to the menu *Sales > Configuration > Address Book > Localization > Map Websites*. You are invited to send the configuration information of your additionnal map websites to the author of the module, so that the module can be updated with more pre-configured map websites.

Usage
-----








=====

First, you need to configure in your preferences:

* the map website to use for the regular maps,

* the map website to use for the route maps,

* the start address for the route maps.

Then you can use the two new buttons on the partner form to open a regular map or a route map.

Known issues / Roadmap
----------------------




Bug Tracker
-----------




Credits
-------










### Contributors





* Alexis de Lattre <alexis.delattre@akretion.com>

### Funders
### Maintainer









.. image:: http://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: http://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose mission is to support the collaborative development of Odoo features and promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)

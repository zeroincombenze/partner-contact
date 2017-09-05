[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/partner-contact/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

    :alt: License: AGPL-3
=========================

Partner first name and last name

This module was written to extend the functionality of contacts to support
having separate last name and first name.

Installation
------------


Configuration
-------------


Usage
-----

-----

=====

The field *name* becomes a stored function field concatenating the *last name*
and the *first name*. This avoids breaking compatibility with other modules.

Users should fulfill manually the separate fields for *last name* and *first
name*, but in case you edit just the *name* field in some unexpected module,
there is an inverse function that tries to split that automatically. It assumes
that you write the *name* in format *"Lastname Firstname"*, but it could lead to
wrong splitting (because it's just blindly trying to guess what you meant), so
you better specify it manually.

For the same reason, after installing, previous names for contacts will stay in
the *name* field, and the first time you edit any of them you will be asked to
supply the *last name* and *first name* (just once per contact).

You can use *_get_inverse_name* method to get lastname and firstname from a simple string
and also *_get_computed_name* to get a name form the lastname and firstname. 
These methods can be overridden to change the format specified above

For further information, please visit:

* https://www.odoo.com/forum/help-1

Known issues / Roadmap
----------------------


Bug Tracker
-----------


Credits
-------



[![Odoo Italia Associazione]]


### Contributors



* Nicolas Bessi <nicolas.bessi@camptocamp.com>
* Yannick Vaucher <yannick.vaucher@camptocamp.com>
* Vincent Renaville <vincent.renaville@camptocamp.com>
* Guewen Baconnier <guewen.baconnier@camptocamp.com>
* Holger Brunn <hbrunn@terp.nl>
* Jonathan Nemry <jonathan.nemry@acsone.eu>
* Olivier Laurent <olivier.laurent@acsone.eu>
* Sandy Carter <sandy.carter@savoirfairelinux.com>
* Alexis de Lattre <alexis.delattre@akretion.fr>
* Lorenzo Battistini <lorenzo.battistini@agilebg.com>
* Hans Henrik Gabelgaard <hhg@gabelgaard.org>
* Jairo Llopis <j.llopis@grupoesoc.es>
* Adrien Peiffer <adrien.peiffer@acsone.eu>
* Ronald Portier <ronald@therp.nl>
* Sylvain Van Hoof
* Pedro Baeza <pedro.baeza@serviciosbaeza.com>

Translations

* Danish: Hans Henrik Gabelgaard
* Italian: Leonardo Donelli
* Spanish: Antonio Espinosa

### Funders

### Maintainer




.. image:: http://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: http://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

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

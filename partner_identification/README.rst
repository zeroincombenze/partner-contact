[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/partner-contact/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)


















[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

Partner Identification Numbers
==============================

This module allows to manage all sort of identification numbers
and certificates which are assigned to a partner (company or individual)
and vary from country to country.

* Commercial register
* VAT ID
* Fiscal ID's
* Membership numbers
* Driver license
* ...


Installation
------------






No specific installation step required


Configuration
-------------






Configure all ID types you need in Sales > Configuration > Address Book > Partner ID Categories.
For example, we create a category 'Driver License':

Name:
  Name of this ID type. For example, 'Driver License'
Code:
  Code, abbreviation or acronym of this ID type. For example, 'driver_license'
Python validation code:
  Optional python code called to validate ID numbers of this ID type.


Usage
-----






=====

In partner form you will see another tab called 'ID Numbers'. You can add
any IDs to this partner, defining:

Category:
   ID type defined in configuration. For example, Driver License
ID Number:
  The ID itself. For example, Driver License number of this person
Issued by:
  Another partner, who issued this ID. For example, Traffic National Institution
Place of Issuance:
  The place where the ID has been issued. For example the country for passports and visa
Valid from:
  Issued date. For example, date when person approved his driving exam, 21/10/2009
Valid until:
  Expiration date. For example, date when person needs to renew his driver license, 21/10/2019
Status:
  ID status. For example new/to renew/expired
Notes:
  Any further information related with this ID. For example, vehicle types this person can drive

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/134/9.0


Known issues / Roadmap
----------------------






* If you want to search a partner by ID you will use advance search form.
  You can't search by issuer, valid dates, category or notes.


Bug Tracker
-----------






Bugs are tracked on `GitHub Issues
<https://github.com/OCA/partner_contact/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed `feedback
<https://github.com/OCA/
partner_contact/issues/new?body=module:%20
partner_identifiers%0Aversion:%20
9.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.


Credits
-------











### Contributors






* Antonio Espinosa <antonioea@antiun.com>
* Ferdinand Gassauer <office@chrcar.at>
* Gerhard Könighofer <gerhard.koenighofer@swing-system.com>
* Laurent Mignon <laurent.mignon@acsone.eu>
* Yajo <Yajo@users.noreply.github.com>

### Funders

### Maintainer










.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.

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

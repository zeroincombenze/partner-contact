[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=10.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=10.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=10.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/10.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/10.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-10.svg)](https://github.com/OCA/partner-contact/tree/10.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-10.svg)](http://erp10.zeroincombenze.it)














































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3

Partner second lastname
=======================

This module was written to extend the functionality of ``partner_firstname`` to
support having a second lastname for contact partners.

In some countries, it's important to have a second last name for contacts.

Contact partners will need to fill at least one of the name fields
(*First name*, *First last name* or *Second last name*).

Installation
------------





Configuration
-------------






You can configure some common name patterns for the inverse function
in Settings > Configuration > General settings:

* Lastname SecondLastname Firstname: For example 'Anderson Lavarge Robert'
* Lastname SecondLastname, Firstname: For example 'Anderson Lavarge, Robert'
* Firstname Lastname SecondLastname: For example 'Robert Anderson Lavarge'

After applying the changes, you can recalculate all partners name clicking
"Recalculate names" button. Note: This process could take so much time depending
how many partners there are in database.

You can use *_get_inverse_name* method to get firstname, lastname and
second lastname from a simple string and also *_get_computed_name* to get a
name form the firstname, lastname and second lastname.
These methods can be overridden to change the format specified above.


Usage
-----







=====

To use this module, you need to:

* Edit any partner's form.
* Make sure the partner is not a company.
* Enter firstname and lastnames.

If you directly enter the full name instead of entering the other fields
separately (maybe from other form), this module will try to guess the best
match for your input and split it between firstname, lastname and second
lastname using an inverse function.

If you can, always enter it manually please. Automatic guessing could fail for
you easily in some corner cases.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/134/10.0


Known issues / Roadmap
----------------------






Patterns for the inverse function are configurable only at system level. Maybe
this configuration could depend on partner language, country or company,
as discussed at `this OCA issue <https://github.com/OCA/partner-contact/issues/210>`_


Bug Tracker
-----------






Bugs are tracked on `GitHub Issues
<https://github.com/OCA/partner-contact/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback `here
<https://github.com/OCA/partner-contact/issues/new>`_.


Credits
-------











### Contributors






* Jairo Llopis <jairo.llopis@tecnativa.com>.
* Antonio Espinosa.
* Pedro M. Baeza <pedro.baeza@tecnativa.com>.

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

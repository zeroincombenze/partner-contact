[![Build Status](https://travis-ci.org/zeroincombenze/addons.svg?branch=10.0)](https://travis-ci.org/zeroincombenze/addons)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/addons/badge.svg?branch=10.0)](https://coveralls.io/github/zeroincombenze/addons?branch=10.0)
[![codecov](https://codecov.io/gh/zeroincombenze/addons/branch/10.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/addons/branch/10.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-10.svg)](https://github.com/OCA/addons/tree/10.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-10.svg)](http://erp10.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

    :alt: License: AGPL-3
=========================

Module name
===========

This module was written to extend the functionality of Odoo to support setting
a birthdate using a date format and allow you to benefit of a clearer API and
UI.

Installation
------------






To install this module, you need to:

* Ensure that the current contents of the *birthdate* field in the
  *res.partner* model in your database are empty or in a format easily readable
  by the python function strptime_ in case you want this module to
  automatically convert those to the new format.
* Install the OCA repository `partner-contact`_.
* Update your modules list.
* Search and install this module.

Configuration
-------------






No configuration is needed.

Usage
-----







=====

To use this module, you need to:

* Edit or create a partner.
* Ensure it is **not** a company.
* Go to the *Personal Information* sheet.
* Set the birthdate there.

For further information, please visit:

* https://www.odoo.com/forum/help-1
* https://github.com/OCA/partner-contact/

Known issues / Roadmap
----------------------






* If you have data in your *res.partner* records' *birthdate* field that cannot
  be converted to date by Pyhton's strptime_ function, those records will have
  an empty *birthdate_date* after install.

Bug Tracker
-----------





Credits
-------











### Contributors






* EL Hadji DEM <elhadji.dem@savoirfairelinux.com>
* Jairo Llopis <j.llopis@grupoesoc.es>
* Matjaž Mozetič <m.mozetic@matmoz.si>
* Rudolf Schnapka <schnapkar@golive-saar.de>
* Denis Leemann <denis.leemann@camptocamp.com>

### Funders

### Maintainer










.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.


.. _partner-contact: https://github.com/OCA/partner-contact/
.. _strptime: https://docs.python.org/2/library/datetime.html#datetime.datetime.strptime

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

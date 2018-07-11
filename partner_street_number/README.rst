[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/partner-contact/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)






























































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
    :alt: License

Split street name and number
============================

This module introduces separate fields for street name and street number.

Changes to the Odoo datamodel
- Introduce two new fields for street name and number
- Keep 'Street' field as a function field to return street name + number
- Data written to the 'Street' field will be parsed into street name and number
  if possible. This will be performed upon installation of the module for
  existing partners.

Compatibility
This module is compatible with Odoo 8.0.


Installation
------------





Upon installation, the module will do a simple migration of existing values in
the street column to split up the street name and number.

Configuration
-------------




Usage
-----








Known issues / Roadmap
----------------------




Bug Tracker
-----------




Credits
-------










### Contributors





* Stefan Rijnhart <stefan@therp.nl>
* Ronald Portier <ronald@therp.nl>
* Pedro M. Baeza <pedro.baeza@serviciosbaeza.com>

Icon
----

* Based on https://openclipart.org/detail/149575/brass-plaques-tags.

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

[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/partner-contact/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/SD)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)






































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

Default sales discount per partner
==================================

This module allows to define at partner level a default discount to be applied
on sales orders as the default one. As the field is a company dependent one,
you can configure a different value for the partner for each of your companies.

Installation
------------





Configuration
-------------






Enabling the use of discounts in Odoo:

#. Go to *Sales > Configuration > Settings*
#. On the group "Quotations & Sales", select the option "Allow discounts on
   sales order lines" for the "Discount" section.

Setting a default sales discount:

#. Then, go to *Sales > Customers*.
#. Create or modify a customer.
#. Go to "Sales & Purchases" page.
#. In the "Sale" section, there's a field called "Default sales discount (%)"
   where you can fill the default discount percentage.
#. This value can only be filled at company partners, not for contacts.

Usage
-----






=====

To use this module, you need to:

#. Go to *Sales > Quotations*.
#. Create a new quotation.
#. Select a partner with a default discount applied.
#. Create an order line, and you will see this discount as default in the line.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/134/9.0

Known issues / Roadmap
----------------------






* This module doesn't work with *product_visible_discount*, as it overwrites
  the discount field with its own value.

Bug Tracker
-----------






Bugs are tracked on `GitHub Issues
<https://github.com/OCA/partner-contact/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
-------






Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.






### Contributors






* Pedro M. Baeza <pedro.baeza@tecnativa.com>

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

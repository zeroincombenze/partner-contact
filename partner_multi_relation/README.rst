[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/partner-contact/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

    :alt: License
=================

Partner Relations

This module aims to provide generic means to model relations between partners.

Examples would be 'is sibling of' or 'is friend of', but also 'has contract X
with' or 'is assistant of'. This way, you can encode your knowledge about your
partners directly in your partner list.

Installation
------------






Configuration
-------------






Usage
-----

-----

-----

-----

-----

=====

Before being able to use relations, you'll have define some first. Do that in
Sales / Configuration / Address Book / Partner relations. Here, you need to
name both sides of the relation: To have an assistant-relation, you would name
one side 'is assistant of' and the other side 'has assistant'. This relation
only makes sense between people, so you would choose 'Person' for both partner
types. For the relation 'is a competitor of', both sides would be companies,
while the relation 'has worked for' should have persons on the left side and
companies on the right side. If you leave this field empty, the relation is
applicable to all types of partners.

If you use categories to further specify the type of partners, you could for
example enforce that the 'is member of' relation can only have companies with
label 'Organization' on the left side.

Now open a partner and choose relations as appropriate in the 'Relations' tab.

Searching partners with relations

Searching for relations is integrated transparently into the partner search
form. To find all assistants in your database, fill in 'is assistant of' and
autocomplete will propose to search for partners having this relation. Now if
you want to find Anna's assistant, you fill in 'Anna' and one of the proposals
is to search for partners having a relation with Anna. This results in Anna's
assistant(s), as you searched for assistants before.

By default, only active, not expired relations are shown. If you need to find
partners that had some relation at a certain date, fill in that date in the
search box and one of the proposals is to search for relations valid at that
date.

More info

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






* Holger Brunn <hbrunn@therp.nl>
* Stefan Rijnhart <stefan@therp.nl>
* Ronald Portier <ronald@therp.nl>
* Sandy Carter <sandy.carter@savoirfairelinux.com>
* Bruno Joliveau <bruno.joliveau@savoirfairelinux.com>
* Adriana Ierfino <adriana.ierfino@savoirfairelinux.com>

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

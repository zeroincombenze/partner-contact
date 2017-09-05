[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/partner-contact/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)
================================================================================================
================================================================================================

OCA partner and contact management modules for Odoo

This project is meant to gather all community extensions about partner and contact management for Odoo.

Here you should find community modules that:

* Enable isolated contact management.
* Add first name, birth name, street number and other extensions for the partners.
* Manage cities and post codes.
* Etc.

[//]: # (addons)


Available addons
----------------
addon | version | OCA version | summary
--- | --- | --- | ---
[base_location](base_location/) | 9.0.1.0.0 | 9.0.1.1.0 | Enhanced zip/npa management system
[base_location_geonames_import](base_location_geonames_import/) | 9.0.1.0.1 | :repeat: | Import better zip entries from Geonames
[base_partner_merge](base_partner_merge/) | 9.0.1.0.0 | :repeat: | Partner merge wizard without dependency on CRM
[partner_address_street3](partner_address_street3/) | 9.0.1.1.0 | :repeat: | Street3 in addresses
[partner_contact_birthdate](partner_contact_birthdate/) | 9.0.1.0.0 | :repeat: | Contact's birthdate
[partner_contact_department](partner_contact_department/) | 9.0.1.0.0 | :repeat: | Assign contacts to departments
[partner_contact_gender](partner_contact_gender/) | 9.0.1.1.0 | :repeat: | Add gender field to contacts
[partner_contact_height](partner_contact_height/) | 9.0.1.0.0 | 9.0.1.0.1 | Provide contact height.
[partner_contact_in_several_companies](partner_contact_in_several_companies/) | 9.0.1.0.0 | :repeat: | Allow to have one contact in several partners
[partner_contact_job_position](partner_contact_job_position/) | 9.0.1.0.0 | :repeat: | Categorize job positions for contacts
[partner_contact_nationality](partner_contact_nationality/) | 9.0.1.0.0 | :repeat: | Add nationality field to contacts
[partner_contact_nutrition](partner_contact_nutrition/) | 9.0.1.0.0 | 9.0.1.0.1 | Provide caloric intake
[partner_contact_nutrition_diet](partner_contact_nutrition_diet/) | 9.0.1.0.0 | :repeat: | Set the nutrition diet of your contacts
[partner_contact_personal_information_page](partner_contact_personal_information_page/) | 9.0.1.0.0 | :repeat: | Add a page to contacts form to put personal information
[partner_contact_weight](partner_contact_weight/) | 9.0.1.0.0 | 9.0.1.0.1 | Provide contact weight
[partner_default_sale_discount](partner_default_sale_discount/) | 9.0.1.0.0 | :repeat: | Default sales discount per partner
[partner_external_map](partner_external_map/) | 9.0.1.0.0 | :repeat: | Add Map and Map Routing buttons on partner form to open GMaps, OSM, Bing and others
[partner_financial_risk](partner_financial_risk/) | 9.0.1.0.0 | :repeat: | Manage partner risk
[partner_firstname](partner_firstname/) | 9.0.1.0.0 | 9.0.2.0.0 | Split first name and last name for non company partners
[partner_identification](partner_identification/) | 9.0.1.0.0 | :repeat: | Partner Identification Numbers
[partner_multi_relation](partner_multi_relation/) | 9.0.1.1.1 | :repeat: | Partner relations
[partner_sector](partner_sector/) | 9.0.1.0.1 | :repeat: | Add partner sectors


Unported addons
---------------
addon | version | OCA version | summary
--- | --- | --- | ---
[account_partner_merge](account_partner_merge/) | 1.0 (unported) | :repeat: | Account Partner Merge
[base_contact](base_contact/) | 8.0.2.0.0 (unported) | :x: | [DEPRECATED] Manage your contacts separately
[base_continent](base_continent/) | 8.0.1.0.0 (unported) | :repeat: | Continent management
[base_location_nuts](base_location_nuts/) | 8.0.1.0.0 (unported) | :repeat: | NUTS Regions
[base_partner_sequence](base_partner_sequence/) | 8.0.1.1.0 (unported) | 9.0.0.1.0 | Sets customer's code from a sequence
[firstname_display_name_trigger](firstname_display_name_trigger/) | 1.0 (unported) | :repeat: | Link module if partner_lastname and account_report_company are installed
[partner_auto_salesman](partner_auto_salesman/) | 8.0.1.0.0 (unported) | :repeat: | Partner auto salesman
[partner_contact_address_detailed](partner_contact_address_detailed/) | 8.0.1.0.0 (unported) | :repeat: | All address data in summarized contact form
[partner_helper](partner_helper/) | 8.0.0.1.0 (unported) | 9.0.0.1.0 | Partner Helper
[partner_street_number](partner_street_number/) | 8.0.0.1.0 (unported) | :repeat: | Introduces separate fields for street name and street number.
[portal_partner_merge](portal_partner_merge/) | 8.0.1.0.0 (unported) | :repeat: | Portal Partner Merge
[res_partner_affiliate](res_partner_affiliate/) | 8.0.1.0.0 (unported) | 9.0.1.0.0 | Partner Affiliates

[//]: # (end addons)

Translation Status
[![Transifex Status](https://www.transifex.com/projects/p/OCA-partner-contact-9-0/chart/image_png)](https://www.transifex.com/projects/p/OCA-partner-contact-9-0)

----

OCA, or the Odoo Community Association, is a nonprofit organization whose 
mission is to support the collaborative development of Odoo features and 
promote its widespread use.

http://odoo-community.org/

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

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)

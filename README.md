[![Build Status](https://travis-ci.org/zeroincombenze/partner-contact.svg?branch=10.0)](https://travis-ci.org/zeroincombenze/partner-contact)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/partner-contact/badge.svg?branch=10.0)](https://coveralls.io/github/zeroincombenze/partner-contact?branch=10.0)
[![codecov](https://codecov.io/gh/zeroincombenze/partner-contact/branch/10.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/partner-contact/branch/10.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-10.svg)](https://github.com/OCA/partner-contact/tree/10.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-10.svg)](http://erp10.zeroincombenze.it)




























































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

OCA partner and contact management modules for Odoo
===================================================

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
[base_location](base_location/) | 10.0.1.0.1 | 10.0.1.0.2 | Enhanced zip/npa management system
[base_location_geonames_import](base_location_geonames_import/) | 10.0.1.0.1 | 10.0.1.1.1 | Import better zip entries from Geonames
[base_location_nuts](base_location_nuts/) | 10.0.1.0.0 | :repeat: | NUTS Regions
[base_partner_merge](base_partner_merge/) | 10.0.1.0.0 | :repeat: | Partner merge wizard without dependency on CRM
[base_partner_sequence](base_partner_sequence/) | 10.0.1.0.0 | :repeat: | Sets customer's code from a sequence
[base_vat_sanitized](base_vat_sanitized/) | 10.0.1.0.0 | :repeat: | Adds field sanitized_vat on partners
[partner_academic_title](partner_academic_title/) | 10.0.1.0.0 | :repeat: | Add possibility to define some academic title
[partner_address_street3](partner_address_street3/) | 10.0.1.0.0 | :repeat: | Add a third address line on partners
[partner_alias](partner_alias/) | 10.0.1.0.0 | :repeat: | Adds aliases to partner names.
[partner_capital](partner_capital/) | 10.0.1.0.0 | :repeat: | Partners Capital
[partner_coc](partner_coc/) | 10.0.1.0.0 | :repeat: | Adds a field 'Chamber Of Commerce Registration Number' to partner
[partner_contact_birthdate](partner_contact_birthdate/) | 10.0.1.1.0 | :repeat: | Contact's birthdate
[partner_contact_configuration](partner_contact_configuration/) | 10.0.1.0.0 | :repeat: | Adds menu configuration access through the 'contacts' module main menu
[partner_contact_department](partner_contact_department/) | 10.0.1.0.0 | :repeat: | Assign contacts to departments
[partner_contact_gender](partner_contact_gender/) | 10.0.1.1.0 | :repeat: | Add gender field to contacts
[partner_contact_in_several_companies](partner_contact_in_several_companies/) | 10.0.1.0.0 | :repeat: | Allow to have one contact in several partners
[partner_contact_job_position](partner_contact_job_position/) | 10.0.1.0.0 | 10.0.1.0.1 | Categorize job positions for contacts
[partner_contact_nationality](partner_contact_nationality/) | 10.0.1.0.0 | :repeat: | Add nationality field to contacts
[partner_contact_personal_information_page](partner_contact_personal_information_page/) | 10.0.1.0.0 | :repeat: | Add a page to contacts form to put personal information
[partner_contact_weight](partner_contact_weight/) | 10.0.1.0.0 | 10.0.1.0.1 | Provide contact weight
[partner_create_by_vat](partner_create_by_vat/) | 10.0.1.0.0 | 10.0.1.0.1 | Using VIES webservice, name and address information will be fetched and added to the partner.
[partner_employee_quantity](partner_employee_quantity/) | 10.0.1.0.0 | :repeat: | Know how many employees a partner has
[partner_external_map](partner_external_map/) | 10.0.1.0.0 | :repeat: | Add Map and Map Routing buttons on partner form to open GMaps, OSM, Bing and others
[partner_firstname](partner_firstname/) | 10.0.2.0.0 | 10.0.2.1.1 | Split first name and last name for non company partners
[partner_helper](partner_helper/) | 10.0.0.1.0 | :repeat: | Add specific helper methods
[partner_identification](partner_identification/) | 10.0.1.1.1 | :repeat: | Partner Identification Numbers
[partner_multi_relation](partner_multi_relation/) | 10.0.1.0.0 | 10.0.1.0.1 | Partner relations
[partner_password_reset](partner_password_reset/) | 10.0.1.0.0 | :repeat: | Add Wizard to allow resetting of a Partner's associated user password from within the partner view.
[partner_second_lastname](partner_second_lastname/) | 10.0.1.0.0 | :repeat: | Have split first and second lastnames
[partner_sector](partner_sector/) | 10.0.1.0.0 | 10.0.1.1.0 | Add partner sectors
[partner_street_number](partner_street_number/) | 10.0.1.0.0 | :repeat: | Introduces separate fields for street name and street number.


Unported addons
---------------
addon | version | OCA version | summary
--- | --- | --- | ---
[account_partner_merge](account_partner_merge/) | 1.0 (unported) | :repeat: | Account Partner Merge
[base_continent](base_continent/) | 8.0.1.0.0 (unported) | :repeat: | Continent management
[firstname_display_name_trigger](firstname_display_name_trigger/) | 1.0 (unported) | :repeat: | Link module if partner_lastname and account_report_company are installed
[partner_auto_salesman](partner_auto_salesman/) | 8.0.1.0.0 (unported) | :repeat: | Partner auto salesman
[partner_contact_address_detailed](partner_contact_address_detailed/) | 8.0.1.0.0 (unported) | :repeat: | All address data in summarized contact form
[portal_partner_merge](portal_partner_merge/) | 8.0.1.0.0 (unported) | :repeat: | Portal Partner Merge
[res_partner_affiliate](res_partner_affiliate/) | 8.0.1.0.0 (unported) | :x: | Partner Affiliates

[//]: # (end addons)

Translation Status
[![Transifex Status](https://www.transifex.com/projects/p/OCA-partner-contact-10-0/chart/image_png)](https://www.transifex.com/projects/p/OCA-partner-contact-10-0)

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

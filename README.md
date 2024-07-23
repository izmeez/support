**Support Ticketing System**

The support module provides a basic ticketing system and helpdesk that is native
to Drupal, offering complete email integration.

The Support module offers the following features:

* Ticketing activity is illustrated with colorful charts (depends on the Chart
API module).
* Tickets can be assigned to users (and users can view all tickets assigned to
them).
* Tickets support states (new, active, pending, closed, etc) and priorities
(low, normal, high, critical, etc).
* Configurable email notifications for new and updated tickets.
* Email integration allows tickets to be created and updated via email, with
 support for attachments. New users can be automatically created. Ticket
 properties can be updated via email (using included support_mailcmd module).
* Highly configurable client and user ticket overviews, highlighting tickets
that haven't been updated for a long time.
* Fully integrated with Drupal's search functionality, users can only search for tickets they have access to.
* Supports an unlimited number of clients, each with their own configuration and access permissions.
* Tickets are nodes, ticket updates are comments.

**Dependencies:**

* Required: Core comment and file modules
* Required: Entity API, CRUD support
* Optional: Google chart API, generates basic charts from ticket statistics
* Optional: Internationalization, allows translation of all mail text variables

**Supporting projects:**

* Support Timer, implements a time tracker for the ticketing system, optionally supports billing rates and time planning.
* Support Views, exposes support tickets to the Views module.
* Support Dashboard, provides all tickets, all client dashboard view.
* Support Bot, report on support tickets in IRC via bot integration.
* Support Fields, define additional per-client support ticket fields with CCK
* Support Token, integrate with tokens
* Support Deadline, allows you to add a "due date" to tickets.
* Support Nag, can send regular reminders about open tickets, and can
automatically close issues after a period of time.
* Support SMS, can send details about open support tickets as SMS messages to
cell phones and pagers.

**Installation**

* Install this module using the official Backdrop CMS instructions at
https://backdropcms.org/guide/modules.
* Configure permissions including when new clients are added.

**Issues**

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/izmeez/support/issues.

**Current Maintainers**
Seeking maintainers.

**Credits**

* Ported to Backdrop CMS by ...
* Originally written for Drupal by Jeremy Andrews(Jeremy).
* Drupal maintainers: catch, FabianX-1, Jeremy, John Franklin, John Cullen (Purencool), Brandon Bergren (bdragon), Jeff Sheltren (JeffSheltren), Marco Molinari (marco)

**Sponsors**
Development of the Support module for Drupal was originally sponsored by Tag1
Consulting and now is maintained by Purencool Digital.

**License**

This project is GPL v2 software. See the LICENSE file in the project
directory for complete text.

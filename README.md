# service_club_install_profile
This is the installation profile for service_club_install_profile.
It combines the core Drupal modules, custom modules, themes,
and pre-defined configuration into one download.
They are all used to provide certain functionality to the program, with specific
purpose listed below.

Used by [didymo/service_club_base](https://github.com/didymo/service_club_base)

#Specific or Custom Modules:

## address - Address
Storing, validating and displaying international postal addresses

## address_map_link - Address Map Link
Allow for address fields to be linked to an external map site.
Allows for a display of the event location on a map, useful for planning or
event advertisement.

## admin_toolbar
Improves the default Drupal Toolbar by enabling drop-down menu functionality.
Exclusively used to make back-end functionality easier to perform, not intended
for front end user functionality.

## calendar - Calendar
Display any Views date field in calendar formats, including date fields, 
node created or updated dates.

## front_page
Allows for the creation and implementation of a custom or alternative default front page.
It allows for different front pages for both anonymous and authenticated front users.

## geolocation - Geolocation Field
Allows for locations to be found and viewed with google maps within the site

## mailsystem - Mail System
Provides an Administrative UI and Developers API for managing the used mail 
backend/plugin.
Allows plugins to use different backends for formatting and sending e-mails by default, 
per module and per mail key. Additionally, a theme can be configured that is 
used for sent mails.

## scheduler - Scheduler
Allows for content editors to schedule when nodes will be published/unpublished at specified
dates/times.

## simplify - Hide UI
Allows for particular fields to be hidden from the user interface. Can be used to de-clutter
forms and other UI elements for content editors. Useful for backend and administrators to
remove anything in the UI that they will never need to access.
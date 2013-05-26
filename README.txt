Moduled developed by Danny Najm <danny@dannyn.com>


DESCRIPTION
-----------

A powerful module to display different content based on the browsing device.
Mobile Content module allows content administrator to tag sections of content to be displayed on mobile devices. Tag format should be {mobile}...{/mobile}. 



INSTALLATION
------------

 1. CREATE DIRECTORY

    Create a new directory "mobile_content" in the sites/all/modules directory and
    place the entire contents of this mobile_content folder in it.

 2. ENABLE THE MODULE

    Enable the module on the Modules admin page.



USAGE
-----------

Edit a content type and wrap any text to be displayed on mobile devices using {mobile}....{/mobile} tags.
Example, if you entered the following when editing a node:

{mobile}Drupal is an open source content management platform{/mobile} powering millions of websites and applications. It’s built, used, and {mobile}supported by an active and diverse community{/mobile} of people around the world



The content when viewed from Desktop will be displayed as:

Drupal is an open source content management platform powering millions of websites and applications. It’s built, used, and supported by an active and diverse community of people around the world



The same content when viewed from a mobile device will be displayed as:

Drupal is an open source content management platform supported by an active and diverse community

Twilio
======================

The Twilio module provides integration with the Twilio cloud communication
platform allowing for your Drupal site to integration Voice and SMS
functionality. 

The module currently provides the following functionality:

- Rules event to act on incoming SMS message
- Rules action to send an SMS message
- Hook for incoming SMS messages
- Hook for incoming voice calls
- User object phone number storage and validation
- Uses libraries api to manage the Twilio php library

Project homepage: http://backdropcms.org/project/twilio

Installation
------------

1. Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules
2. Download the Twilio php library from (http://www.twilio.com/docs/libraries).
3. Extract the library in your sites/all/libraries folder and rename the
   directory to 'twilio'.
4. Visit 'admin/config/system/twilio' and enter your Twilio API information
   found on the twilio dashboard 

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/twilio/wiki/Documentation

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/twilio/issues

Current Maintainers
-------------------

- Marc Linn (https://github.com/mclinn)

Credits
-------

- Ported to Backdrop CMS by Marc Linn (https://github.com/mclinn).
- Originally written for Drupal by Arvin Singla (arvinsingla), arvin.singla@gmail.com

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

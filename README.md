Deprecated
==========
This repository is deprecated, and may be deleted.

Use <https://github.com/OS2WebCore/os2web_fics_esdh>

OS2Web FICS ESDH Provider
==============================

Description
-----------
This module provides an implementation of the FICS ESDH system. It comes
with a MM plugin for the os2web_esdh_provider module, and a custom case
publishing import importing into the content types from 
os2web_case_publishing. 

Dependencies
------------
- os2web_esdh_provider
- ctools

Installation
------------
This module should reside in the modules directory of the installation,
most commonly profiles/os2web/modules/, but alternativly in sites/all/modules
(This could be for development purposes).

See https://github.com/OS2web/os2web/wiki for further instructions.

This module can also be installed with drush make in your install profile.

Developer info
--------------
Automatic cleanup of imported XML files can be disabled by adding
"$conf['os2web_fics_esdh_keep_xml_files'] = TRUE"; to the settings.php file.
Notice: this line should be removed or set to FALSE in production environments,
if XML files contain closed bullets!

Additional Info
---------------
This repository should be governed using Git Flow. for more information see
http://nvie.com/posts/a-successful-git-branching-model/

Note: This module can work without OS2Web core if the OS2Web Meetings Light
(https://github.com/PropeopleDK/os2web_meetings_light) feature is used 
instead.

OpenSRS Pro Autosynch
=====================

Synchronization of mod_opensrs for WHMCS.

Install
-------

* Backup you db_whmcs
* This script is ment to run via cron or manually.
* Copy mod_opensrs_sync.php to a non public_html directory.
* Copy and edit config.sample.php to config.php
* Edit config.php to connect to your db_whmcs
* run php mod_opensrs_sync.php
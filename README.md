<img src='https://travis-ci.org/petroskilp/moodle-auth_totvs.svg?branch=master'/>
# Moodle TOTVS Webservice Authentication Plugin

Moodle plugin to authenticate users against TOTVS webservice.

This plugin let you configure a SOAP webservice
to authenticate users against it.

Install
-------

* Put these files at moodle/auth/totvs/
 * You may use composer
 * or git clone
 * or download the latest version from 
* Log in your Moodle as Admin and go to "Notifications" page
* Follow the instructions to install the plugin

Usage
-----

You configure the web service URL, the name of the function to be called, the returned Class and attribute to get the boolean result from.

This plugins does not create users, and also does not update users records.

Users are suposed to be created and updated by external service using the Moodle's webservices.

Users should have "auth = totvs" for this plugin to authenticate users.

To see a sample of how to configure you plugin to call your webservice take a look at 

Dev Info
--------

Please, report issues at: https://github.com/petroskilp/moodle-auth_totvs/issues

Feel free to send pull requests at: https://github.com/petroskilp/moodle-auth_totvs/pulls

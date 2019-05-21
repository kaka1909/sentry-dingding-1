sentry-dingding
==============

An extension for Sentry which integrates with DingDing. It will send issues notification to DingDing.


Why fork?
-------
You will face unicode issue if use https://github.com/L3T/sentry-dingding to handle messages contain special characters.


How to configure with sentry server?
-------

Add below dependency in requirements.txt if you are usring docker to deploy sentry components.

git+https://github.com/kaka1909/sentry-dingding-1


Configuration
-------------

Go to your project's configuration page (Projects -> [Project]) and select the
DingDing tab. Enter the required credentials and click save changes.


# Introduction #

Add your content here.


# Outline #

Django/App Engine Presentation

Why Django?
  1. Brief History
    * Lawrence Journal-World & News
    * Adrian Holovaty, Simon Willison, Jacob Kaplan-Moss
    * Initial Purpose and Philosophy
  1. What makes Django appealing?
    * Installation is Easy
    * URL Patterns are Regular Expressions
    * Free Admin Site (well practically free)
    * Generic Views
    * Template Engine (lots of filters and tags it is also extendable through template tags)
    * Template Tags

Why App Engine?
  1. Brief History
  1. What makes App Engine appealing?
    * It is $free.99.
    * No hassling with hardware
    * No system administration
    * Automatic scaling and load balancing
    * Datastore (BigTable)
    * Very similar to Django “out of the box”

What are the limitations of using Django and GAE together?
  1. No Relational Databases (but there is the DataStore)
  1. Python Only
  1. No access to the file system
  1. Limit of 500 MB of Persistent Storage (in the Beta Period)
  1. 1MB File Size limit per file
  1. Models are different
  1. You cannot use httplib but you can use urlfetch (Google’s version)
  1. No Cron
  1. No non appspot.com SSL
  1. No “out of the box” support for the following (although the app-engine-patch project is working on them):
    * Django/bin
    * Django/contrib/admin
    * Django/contrib/auth
    * Django/contrib/databrowse
    * Django/test
    * Generic views

What do I need to setup the dev environment?
  1. Python 2.5
  1. Google SDK
  1. Django 1.0 (or you could use the 0.96 version that comes with the SDK)
  1. App-engine-patch
  1. Eclipse (optional)
  1. pyDev (optional)
  1. Web Tools Platform (WTP) – you can install this right from Ganymede (optional)

Overview of Django’s Application Structure
  1. Settings
  1. Models
  1. Views
  1. URLs
  1. Forms
  1. Views
  1. Cache
  1. Tests

Ok, now let’s write some code!!
  1. Settings
  1. Models
  1. Views
  1. URLs
  1. Forms
  1. Views
  1. Cache
  1. Tests

Questions & Answers

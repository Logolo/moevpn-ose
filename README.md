MOEVPN OPENSOURCE EDITION                                                                                                                                    
=========================                                                                                                                                    

Intro
-----

MOEVPN is a sales and management system for VPN service based on Django project. 

Original MOEVPN is designed for <http://moecn.net>, and it is open-sourced now.

Features
--------

* VPN accounts management
 * Add or remove accounts
 * Change password
 * Data quota usage monitoring
 
* Orders management
 * Submit orders online
 * Pay online
 * Cancel orders online
 * Custom payment cycles
 * Custom vpn plans
 * Custom sales promotions
 
* Online payment
 * Alipay payment
 * Automatically account activation after payment
 
* Ticket system
 * submit online tickets

* Knowledgebase
 * create and manage knowledgebase document
 * show knowledge by categories

* Email notifacation
 * Automatically notifacation
 * User mail archives 

Installation
------------

###requirement

* django 1.4
* mysql-python

###step-by-step

1. Modify settings.py according to your needs
2. Run `python manage.py syncdb` to sync create tables and install fixtrues
3. That's all
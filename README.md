![](http://dev.lutece.paris.fr/jenkins/buildStatus/icon?job=cms-plugin-contact-deploy)
# Plugin Contact

## Introduction

The Contact plugin allows to manage several lists of contacts and to display the email form.

Below is the list of the main features:
 
* Add a portal front-office page with a standard form to send an email to a contact
* Contact management feature : create, list, modify and delete the contacts
* Contact List management feature : create, list, modify and delete the contact lists
* Link several contacts to one list
* Link a contact to several lists


## Usage

Front office URL web page to display the send email form : */jsp/site/Portal.jsp?page=contact* 

A "Contact" link is automaticaly added in the Lutece portal footer when the plugin is enabled.

Back office URL web page to access to the admin feature : */jsp/admin/plugins/contact/ManageContactsHome.jsp* 

## Plugin Contact Administration

Access to the admin feature

This page gives access to either the contact or contact list management:

![plugin access point](http://dev.lutece.paris.fr/plugins/plugin-contact/user/images/manage_contacts_home.png)

Contact management feature

This page displays the stored contacts. Possible actions are: Add, modify, delete and assigment of a contact to a list

![Contact management](http://dev.lutece.paris.fr/plugins/plugin-contact/user/images/manage_contact.png)

Contact edition page:

![Contact edition](http://dev.lutece.paris.fr/plugins/plugin-contact/user/images/modify_contact.png)

Management page to assign a contact to lists:

![Contact assignment](http://dev.lutece.paris.fr/plugins/plugin-contact/user/images/manage_contact_assignments.png)

Management of contact lists

This managament page displays the stored contact lists. Possible actions are : Add, modify, delete a list and manage contact assigment to one list.

![contact list management](http://dev.lutece.paris.fr/plugins/plugin-contact/user/images/manage_contact_lists.png)

Contact list edition page:

![Contact list edition](http://dev.lutece.paris.fr/plugins/plugin-contact/user/images/modify_contact_list.png)

List assignment page:

![contact list assignment](http://dev.lutece.paris.fr/plugins/plugin-contact/user/images/manage_list_assignments.png)

## Plugin security management

It is possible to assign a contact or a contact list to a workgroup. They will be visible and editable only by the selected workgroup.

On front-office side, it is possible to limit access to a list only to some roles. This feature can be enabled when creating or editing a list.


[Maven documentation and reports](http://dev.lutece.paris.fr/plugins/plugin-contact/)



 *generated by [xdoc2md](https://github.com/lutece-platform/tools-maven-xdoc2md-plugin) - do not edit directly.*
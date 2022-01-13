---
title: UH Manoa Meteorites
---
* [Uh Manoa Meteorites Organization](https://github.com/uh-manoa-meteorites)
* [M1 Project Board](https://github.com/uh-manoa-meteorites/uh-manoa-meteorites.github.io/projects/1?add_cards_query=is%3Aopen)

## Table of contents
* [Overview](#overview)
* [User Guide](#user-guide)
* [Milestones](#milestones)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Deployment](#deployment)
* [Team Members](#team-members)

## Overview

Kanak Attack is an app designed for the UH Manoa campus. It gives vendors the ability to maintain an active menu, update items, and list the availability of items. The user have the ability to view menu items, vendors, and the menu for each vendor. On top of that, they are also able to read reviews from other users and leave their own. The overall purpose of this app is to display available items around campus so the user can make a decision on what to eat based on their personal taste and availability.

The system provides the following:

* There are three user roles (vendor, consumer, and admin) in which the vendors can update the app to include available menu options, changes, or specials.
* Top-level index pages for Food and Vendors.
* Initialization code to define Vendors and Foods and relations between them.
* The ability to leave reviews for vendors.
* Accessing the menu page, vendor page, and review pages requires user-level authorization, while editing menu data and vendor profiles requires either vendor-level or admin-level authorization.

## User Guide

This is a user guide for Kanak Attack Manoa.

### Landing Page

When arriving at the landing page, the user has the option to login to an existing account or create a new one. It also displays general information about the app in case the user is contemplating creating an account.

### Index pages

Kanak Attack provides two public pages that present the contents of the database organized in various ways. The following are pages that greet the user upon startup and login.

Login Page:



Signup/Register Page:



### Admin Home Page

The Admin page is the first page that greets any admin-level account user upon login, and allows them to modify existing accounts by changing their account type (user-level or vendor-level).


### Edit Vendors

The admin user also has the ability to edit the information of all the vendors.

### Vendor Home page

After logging in, you are taken to the home page, which presents a form where you can complete and/or update your personal profile as a vendor if you have vendor-level authorization.


### Add Menu Item

Once a vendor is logged in, the vendor can define new menu items with the Add Menu Item page.

The vendor also has the ability to view their current menu and edit it.
<img src="public/images/vendor-edit.png">
<img src="public/images/edit-menu-item.png">

### List Menu Item

### List Vendor



### Review Page


## Milestones
* In Milestone 1, we created the landing page, deployed to Digital Ocean, and created four mockup pages. We also have two pages that read/write to the database. Our latest updates have also been deployed to Digital Ocean. (Finished) [M1 Project Board](https://github.com/kanak-attack-manoa/kanak-attack-manoa/projects/1)

## Community Feedback


## Developer Guide

### Installation

First, [install Meteor](https://www.meteor.com/install).

Second, go to [Kanak Attack Manoa](https://github.com/kanak-attack-manoa/kanak-attack-manoa), and download a copy of Kanak Attack Manoa.

Then, cd into the app/ directory of your local copy of the repo, and install the required libraries with:

```
$ meteor npm install
```

## Development History


## Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file](https://github.com/kanak-attack-manoa/kanak-attack-manoa/blob/master/app/package.json):

```
$ meteor npm run start
```

The first time you run the app, it will create default users and contacts.

Here is the output:

```
meteor npm run start

> meteor-application-template-react@ start /Users/triciamariereyes/Documents/GitHub/kanak-attack-manoa/app
> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.development.json

[[[[[ ~/Documents/GitHub/kanak-attack-manoa/app ]]]]]

=> Started proxy.                             
=> Started MongoDB.                           
I20211124-16:49:31.438(-10)? Creating the default user(s)
I20211124-16:49:31.448(-10)?   Creating user admin@foo.com.
I20211124-16:49:31.535(-10)?   Creating user john@foo.com.
I20211124-16:49:31.610(-10)?   Creating user vendor@foo.com.
I20211124-16:49:31.693(-10)? Creating default data.
I20211124-16:49:31.694(-10)?   Adding: John (john@foo.com)
I20211124-16:49:31.776(-10)?   Adding: L&L Hawaiian Barbecue (vendor@foo.com)
I20211124-16:49:31.779(-10)?   Adding: Lasoon (vendor@foo.com)
I20211124-16:49:31.781(-10)? Creating default Vendors.
I20211124-16:49:31.782(-10)?   Adding: Panda Express (john@foo.com)
I20211124-16:49:31.879(-10)?   Adding: Lasoon (john@foo.com)
I20211124-16:49:31.884(-10)? Creating default data.
I20211124-16:49:31.885(-10)?   Adding: Chicky Sandy (john@foo.com)
I20211124-16:49:32.096(-10)?   Adding: Stew Beet Macaroni (john@foo.com)
I20211124-16:49:32.097(-10)?   Adding: Meat Salad (admin@foo.com)
I20211124-16:49:32.244(-10)? Monti APM: completed instrumenting the app
=> Started your app.

=> App running at: http://localhost:3000/
```


### Note regarding "bcrypt warning":

You might also get the following message when you run this application:

```
Note: you are using a pure-JavaScript implementation of bcrypt.
While this implementation will work correctly, it is known to be
approximately three times slower than the native implementation.
In order to use the native implementation instead, run

  meteor npm install --save bcrypt

in the root directory of your application.
```

On some operating systems (particularly Windows), installing bcrypt is much more difficult than implied by the above message. Bcrypt is only used in Meteor for password checking, so the performance implications are negligible until your site has very high traffic. You can safely ignore this warning without any problems during initial stages of development.

### Viewing the running app

If all goes well, the template application will appear at [http://localhost:3000](http://localhost:3000).  You can login using the credentials in [settings.development.json](https://github.com/kanak-attack-manoa/kanak-attack-manoa/blob/master/config/settings.development.json), or else register a new account.

### ESLint

You can verify that the code obeys our coding standards by running ESLint over the code in the imports/ directory with:

```
meteor npm run lint
```

## Deployment
A link to our deployed application on Digital Ocean 

## Team Members
* Nicholas Carr
    * [Portfolio](https://nicholasbcarr.github.io/)
* Feimei Chen 
    * [Portfolio](https://feimeichen.github.io/)

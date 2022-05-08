---
title: UH Manoa Meteorites
---
* [Uh Manoa Meteorites Organization](https://github.com/uh-manoa-meteorites)
* [M1 Project Board](https://github.com/uh-manoa-meteorites/nonprofit-project-template/projects/1)

## Table of contents
* [Overview](#overview)
* [User Guide](#user-guide)
* [Login Page](#login-page)
* [Milestones](#milestones)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Deployment](#deployment)
* [Team Members](#team-members)

## Overview

We are aiming to create an application that better links volunteers with organizations. This app will better display relevant information with regards to volunteer work specifically and put volunteers in touch with the right people, rather than navigating complicated organization websites. We also plan to be able to filter a map of the island in order to better display more convenient opportunities for users. 

## User Guide

This is a user guide for Volunteer Ally.

### Landing Page

When arriving at the landing page, the user has the option to login to an existing account or create a new one. It also displays general information about the app in case the user is contemplating creating an account.

### Index pages


#### Login Page

To log into a pre-existing account, or to create an account, click the LogIn/SignUp button at the top right corner.
<img src="./images/loginFinal.png">
Login to an account here, or click register to sign up!
<img src="./images/loginFinal.png">

#### Signup/Register Page:

To create an account, enter the following information and be sure to be older than 16 years of age!
<img src="./images/signUpTop.png">
Continue by filling out the information, anything marked with a red asterisk is required. Choose special interests, upload a profile picture, and pick special skills to be displayed on a profile page.
<img src="./images/signUpMiddle.png">
Make sure to agree to the terms and conditions and select any availability or environmental preference of note.
<img src="./images/signUpBottom.png">
Finally click Sign Up to finalize an account
<img src="./images/signUpSuccess.png">
Log in with the new credentials [Login Page](#login-page) and the default profile page can now be viewed by the My Profile button on the top right corner (view.
<img src="./images/viewProfileButton.png">

### Admin Home Page

Hold the ability to include admin functionality.


### Browse Organizations

A page where the organizations will be listed equally as not to make one look better than the other

### Home page

Possibly the users home page where they might update any of their information.

### Add Event

A page that will hold the ability to add an event to a google calender or something similar

### Share on Social Media

A page that will enable the user to share an event to linked social media accounts.

### Notice for Logging Hours

We want to be able to have a verification system for those that need to keep track of how many hours of service they do. This would be a toggle via email to the organizations volunteer manager.

### Badge System

Render profile badges to reflect certain amount of volunteer hours put in.

## Milestones

* In Milestone 1, we will create mockups for the site pages. [M1 Project Board](https://github.com/uh-manoa-meteorites/nonprofit-project-template/projects/1)

## Community Feedback


## Developer Guide

### Installation

First, [install Meteor](https://www.meteor.com/install).

Second, install package...

Then, cd into the app/ directory of your local copy of the repo, and install the required libraries with:

```
$ meteor npm install
```

## Development History


## Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file]:

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
data to be populated....
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

If all goes well, the template application will appear at 

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
* Justin Loi
    * [Portfolio](https://justin-loi.github.io/)
* Su Lao
    * [Portfolio](https://sulao1999.github.io/)
* Irene Ma
    * [Portfolio](https://irene-ma.github.io/)
* Gerald Lee
    * [Portfolio](https://glee25.github.io/)
* Tri Pham
    * [Portfolio](https://tricpham.github.io/)
* Tracy Bui
    * [Portfolio](https://tbui00.github.io/)


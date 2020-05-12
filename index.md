Buying and selling textbooks, made easy.

## The site:

[http://textrealm.meteorapp.com/#/](http://textrealm.meteorapp.com/#/)

## Team: 
* [Chan Ung Jeong](https://chan-jeong98.github.io/)
* [Sang Nguyen](https://sanngu68.github.io/)
* [Sola Takahashi](https://soratsky.github.io/)
* [Sophia Elize Cruz](https://sophiaelizecruz.github.io/)

## Table of Contents
* [Overview](#overview)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Project Development History](#project-development-history)
  * [Milestone 1](#milestone-1)
  * [Milestone 2](#milestone-2)
  * [Milestone 3](#milestone-3)
* [Mockups](#mockups)

## Overview 

TextRealm is a web application where UH students can easily buy and sell their textbooks to other UH students. We hope to 
develop a working application, in which the student can login to their account, or sign up for an account, and fill out the 
necessary information for their profile. The user can buy textbooks by searching for textbooks based on their ISBN number, 
title, or author, and contacting the seller, or they can set up offers for textbooks that they plan to sell by supplying the 
ISBN number which will be used to match up buyers and sellers as well as other information about the textbook. If the user 
wants to save textbooks so that they can reference it later, we plan to implement a wishlist/favorites page where the user can 
click an icon to save it and click the wishlist page in the navigation bar to access it later.

We plan to implement the following items:

* A landing page that asks the user to sign-up or login
* A rating system that allows buyers and sellers to rate each other based on their experience
* A profile page that lists the textbooks that the user is selling
  * Includes user's name, a description, a way for other users to contact them, and profile picture
* Users will be able to apply tags and notes to their entries, such as the class it can be used for, details on the condition, 
and any other information related to the textbook
* A search page that allows the user to search for the textbook based on the either the author, ISBN number, or title
* A wishlist/favorites page that allows users to save textbooks and access them at a later time
* Admin role, which will allow them to ban users for inappropriate behavior

We plan to make this application using:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

## User Guide

This section provides a walkthrough of the TextRealm user interface and its capabilities so far.

### Landing Page

You can find our landing page [here](http://textrealm.meteorapp.com/#/).
The landing page is presented to users when they visit the top-level URL to the site.
<img class="ui medium floated rounded image" src="/progress-shots/LandingPageFinal.png" length="800" width="1000">

### Register Page

The user can register an account if they are not already registered by clicking the 'Sign Up' option in the Nav Bar.

<img class="ui medium floated rounded image" src="/progress-shots/RegisterPage.png" length="800" width="1000">

### Login Page

Returning users can login to the system by clicking on the 'Login' option in the Nav Bar, and inputting their email and 
password.

<img class="ui medium floated rounded image" src="/progress-shots/Login.png" length="800" width="1000">

### Edit Profile

Once you are logged in, you can edit/update your personal.

<img class="ui medium floated rounded image" src="/progress-shots/EditProfile.png" length="800" width="1000">

### Sell A Textbook

Once you are logged in, if you are selling a textbook, you must click on the 'Sell A Textbook' option in the Nav Bar, and you 
must fill in the fields for a textbook that you plan on selling. 

<img class="ui medium floated rounded image" src="/progress-shots/SellATextbook.png" length="800" width="1000">

## Developer Guide
This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation

First, install Meteor.

Second, visit the TextRealm application GitHub page and click the “Use this template” button to create your own repository 
initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the 
repo. Then, download a copy of the repo to your local computer.

Third, cd into the text-realm/app directory and install libraries with:

```$ meteor npm install```

Fourth, run the system with:

```$ meteor npm run start```

If it all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

## Project Development History:
### [Milestone 1:](https://github.com/textrealm/text-realm/projects/2)
- Copied application template
- Created TextRealm logo
- Implemented About/FAQ page
- Designed database
- Implemented Landing Page
- Deployed to Galaxy
- Finished Mockups

### Landing Page

You can find our landing page [here](http://textrealm.meteorapp.com/#/).
<img class="ui medium floated rounded image" src="/progress-shots/LandingPageFinal.png" length="800" width="1000">

### [Milestone 2:](https://github.com/textrealm/text-realm/projects/3)

- Start and Design the Admin Page
- Implement the Add/Sell a Textbook page, and the page to edit entries
- Start rating system
- Start User profile page
- Finish the Registration/Login page
- 'Not found' page, and loading components

### Register Page

The user can register an account.

<img class="ui medium floated rounded image" src="/progress-shots/RegisterPage.png" length="800" width="1000">

### Login Page

Returning users can login to the system by inputting their email and password.

<img class="ui medium floated rounded image" src="/progress-shots/Login.png" length="800" width="1000">

### Edit Profile

The user can edit their profile when they are registered.

<img class="ui medium floated rounded image" src="/progress-shots/EditProfile.png" length="800" width="1000">

### Sell A Textbook

The registered user must fill in the fields for a textbook that they plan on selling.

<img class="ui medium floated rounded image" src="/progress-shots/SellATextbook.png" length="800" width="1000">

### [Milestone 3:](https://github.com/textrealm/text-realm/projects/4)

* Finish search
* Finish all Profile components
* Fix any bugs in the database
* Finish rating system
* Check for any ES-Lint errors
* Finish Results page after search

## User Feedback

### We allowed five UH Manoa students to test out our application. This was their feedback:
- Clearer instructions for adding/editing user reviews and textbook entries (need Image URL, specific image sizes)
- Background/color scheme too plain
- Would like to see other user's profiles/provide a link to a seller's profile
  - Make seller information more prominent when viewing an entry
- Creating a textbook entry to sell: Provide a field to specify what majors the book falls under
  - "Search by major should be an option."
  - "Maybe a dropdown? It'll be easier."
- Check user emails upon signing up to make sure that they are registered 'hawaii.edu' accounts.

## Mockups

## Search Page

The user can search for a desired book for purchase. The search will be based on title, author, or ISBN-10.

<img class="ui medium floated rounded image" src="/mockups/LandingPage.png" length="800" width="1000">

## Landing Page 

The page that the user sees when they open up the application.

<img class="ui medium floated rounded image" src="/mockups/LandingPage.png" length="800" width="1000">

## Login Page

The user can login to the site via this page.

<img class="ui medium floated rounded image" src="/mockups/LoginPage.png" length="800" width="1000">

## Register Page

If the buyer/seller does not have account, they can register for the site here.

<img class="ui medium floated rounded image" src="/mockups/RegisterPage.png" length="800" width="1000">


## Selling a Textbook

The user enters the required information to upload a textbook that they plan to sell. 

<img class="ui medium floated rounded image" src="/mockups/AddTextbook.png" length="800" width="1000">

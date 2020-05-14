Buying and selling textbooks, made easy.

## The Site:

* Update! The site may no longer be active. We apologize for the inconvenience. *
You can find our deployed site [here](http://textrealm.meteorapp.com/#/).

## The Team: 
* [Chan Ung Jeong](https://chan-jeong98.github.io/)
* [Sang Nguyen](https://sanngu68.github.io/)
* [Sola Takahashi](https://soratsky.github.io/)
* [Sophia Elize Cruz](https://sophiaelizecruz.github.io/) 

## Table of Contents
* [Overview](#overview)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Project Development History](#project-development-history)
  * [Mockups](#mockups)
  * [Milestone 1](#milestone-1)
  * [Milestone 2](#milestone-2)
  * [Milestone 3](#milestone-3)
* [Next Steps and User Feedback](#next-steps-and-user-feedback)

## Overview 

TextRealm is a web application where UH students can easily buy and sell their textbooks to other UH students. We hope to 
develop a working application, in which the student can login to their account, or sign up for an account, and fill out the 
necessary information for their profile. The user can buy textbooks by searching for textbooks based on their ISBN number, 
title, or author, and contacting the seller, or they can set up offers for textbooks that they plan to sell by supplying the 
ISBN number which will be used to match up buyers and sellers as well as other information about the textbook. 

We plan to implement the following items:

* A landing page that asks the user to sign-up or login
* A rating system that allows buyers and sellers to rate each other based on their experience
* A profile page that lists the textbooks that the user is selling
  * Includes user's name, a description, a way for other users to contact them, and profile picture
* Users will be able to apply details and notes to their entries, such as the class it can be used for, details on the 
condition, and any other information related to the textbook
* A search page that allows the user to search for the textbook based on the either the author, ISBN number, or title
* Admin role, which will allow them to delete entries and ban users for inappropriate entries
* A page listing user reviews on their buying experience with another user

We plan to make this application using:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

## User Guide

This section provides a walkthrough of the TextRealm user interface and its capabilities.

### Landing Page

You can find our landing page [here](http://textrealm.meteorapp.com/#/).
The landing page is presented to users when they visit the top-level URL to the site.
<img class="ui medium floated rounded image" src="/progress-shots/LandingPageFinal.png" length="800" width="1000">

### Register Page

The user can register an account if they are not already registered by clicking the 'Sign Up' option in the Nav Bar. From 
there, they must fill out the required fields to create an account. Only students in the UH system may be able to register.

<img class="ui medium floated rounded image" src="/progress-shots/RegisterFinal.png" length="800" width="1000">

### Login Page

Returning users can login to the system by clicking on the 'Login' option in the Nav Bar, and inputting their email and 
password.

<img class="ui medium floated rounded image" src="/progress-shots/LoginFinal.png" length="800" width="1000">

When the user is logged in, they will land on the page that will allow them to sell their textbooks.

### Sell A Textbook

Once you are logged in, you will be redirected to the 'Sell A Textbook' page where you can start selling your textbooks! If 
you are selling a textbook, you must click on the 'Sell A Textbook' option in the Nav Bar, and you must fill in the fields for 
a textbook that you plan on selling. 

<img class="ui medium floated rounded image" src="/progress-shots/SellATextbookF.png" length="800" width="1000">

<img class="ui medium floated rounded image" src="/progress-shots/Added.png" length="800" width="1000">

Upon adding an entry, the entry will appear on your profile. You have the ability to either edit an entry, or delete an entry.

<img class="ui medium floated rounded image" src="/progress-shots/WithBook.png" length="800" width="1000">

### Edit Entry 

You can edit the information on the textbooks that you are selling.

<img class="ui medium floated rounded image" src="/progress-shots/EditEntryFinal.png" length="800" width="1000">

### Edit Profile

Once you are logged in, you can edit/update your information on your profile.

<img class="ui medium floated rounded image" src="/progress-shots/EditProfileFinal.png" length="800" width="1000">

### Search 

To search for the textbook that you want to buy, clicking on the 'Search For Books' option in the menu bar will take you to 
the search page which lists available books. You can search by author, ISBN-10, and by title, and the search will display 
books whose information is relevant to your search. The following screenshots show how you can narrow down your search by 
searching for the author, ISBN-10, or title of the book.

The search page:

<img class="ui medium floated rounded image" src="/progress-shots/Search.png" length="800" width="1000">

For example, searching by author:

<img class="ui medium floated rounded image" src="/progress-shots/SearchAuthor.png" length="800" width="1000">

Or, you can search by ISBN-10:

<img class="ui medium floated rounded image" src="/progress-shots/SearchISBN.png" length="800" width="1000">

Or, you can search by title:

<img class="ui medium floated rounded image" src="/progress-shots/TitleSearch.png" length="800" width="1000">

If there are no entries pertaining to your search, then you will be greeted by a 'No results.'

<img class="ui medium floated rounded image" src="/progress-shots/NoResults.png" length="800" width="1000">

### Profile of a Book

When you see the book that you need, you can click on the 'View More' option, which will pull up all of the information about 
the book. If this is the book that you are looking for, you can email the seller as their email is listed with the entry.

<img class="ui medium floated rounded image" src="/progress-shots/BookProfile.png" length="800" width="1000">

### User Reviews

When you purchase a book from a user on the site, you can comment about and rate your experience! By going to the 'Add A User 
Review' option in the menu bar, you can rate your experience with buying from a user by scoring it out of 5 stars and 
providing comments about your experience.

<img class="ui medium floated rounded image" src="/progress-shots/AddComment.png" length="800" width="1000">

You can view all of the user reviews in the 'User Reviews' option in the menu bar, which displays reviews from users about 
purchases done with other users on the site.

<img class="ui medium floated rounded image" src="/progress-shots/UserReviews.png" length="800" width="1000">

### Admin Role

Users with the admin role will have access to all of the textbooks in the database. If there is an entry that is deemed to be 
inappropriate, the admin can delete the entry. Admins can email the owners of these inappropriate entries and ban them for any 
inappropriate conduct on the site.

<img class="ui medium floated rounded image" src="/progress-shots/TextRealmAdminFinal.png" length="800" width="1000">


## Developer Guide
This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own 
development tasks.

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

### Initialization

The config directory is intended to hold settings files. The repository contains one file: config/settings.development.json.

This file contains default definitions for Users, Textbook Entries, and Ratings/Reviews and the relationships between them.

The settings.development.json file contains a field called “loadAssetsFile”. It is set to false, but if you change it to true, 
then the data in the file app/private/data.json will also be loaded. The code to do this illustrates how to initialize a 
system when the initial data exceeds the size limitations for the settings file.

### Quality Assurance

#### ESLint

TextRealm includes a [.eslintrc](https://github.com/textrealm/text-realm/blob/master/app/.eslintrc) file to define the coding 
style adhered to in this application. You can invoke ESLint from the command line as follows:

```meteor npm run lint```

ESLint should run without generating any errors.

It’s significantly easier to do development with ESLint integrated directly into your IDE (such as IntelliJ).

## Project Development History:

## Mockups

The following items are some of the mockups of pages that we had planned for this application.

### Search Page

The user can search for a desired book for purchase. The search will be based on title, author, or ISBN-10.

<img class="ui medium floated rounded image" src="/mockups/LandingPage.png" length="800" width="1000">

### Landing Page 

The page that the user sees when they open up the application.

<img class="ui medium floated rounded image" src="/mockups/LandingPage.png" length="800" width="1000">

### Login Page

The user can login to the site via this page.

<img class="ui medium floated rounded image" src="/mockups/LoginPage.png" length="800" width="1000">

### Register Page

If the buyer/seller does not have account, they can register for the site here.

<img class="ui medium floated rounded image" src="/mockups/RegisterPage.png" length="800" width="1000">


### Selling a Textbook

The user enters the required information to upload a textbook that they plan to sell. 

<img class="ui medium floated rounded image" src="/mockups/AddTextbook.png" length="800" width="1000">

## Project Milestones:

### [Milestone 1:](https://github.com/textrealm/text-realm/projects/2)

- Copied application template
- Created TextRealm logo
- Implemented About/FAQ page
- Designed database
- Implemented Landing Page
- Deployed to Galaxy
- Finished Mockups

<img class="ui medium floated rounded image" src="/progress-shots/M1.png" length="800" width="1000">


### [Milestone 2:](https://github.com/textrealm/text-realm/projects/3)

- Started and Designed the Admin Page
- Implemented the Add/Sell a Textbook page, and the page to edit entries
- Started rating system
- Started User profile page
- Finished the Registration/Login page
- 'Not found' page, and loading components

<img class="ui medium floated rounded image" src="/progress-shots/M2.png" length="800" width="1000">


### [Milestone 3:](https://github.com/textrealm/text-realm/projects/4)

* Finished search
* Finished all Profile components
* Fixed any bugs in the database
* Finished rating system
* Checked for any ES-Lint errors
* Finished Results page after search

<img class="ui medium floated rounded image" src="/progress-shots/M3.png" length="800" width="1000">

## Next Steps and User Feedback

### We allowed five UH Manoa students to test out our application. This is a summary of their feedback:
- Clearer instructions for adding/editing user reviews and textbook entries (need Image URL, specific image sizes)
- Background/color scheme too plain
- Would like to see other user's profiles/provide a link to a seller's profile
  - Make seller information more prominent when viewing an entry
- Creating a textbook entry to sell: Provide a field to specify what majors the book falls under
  - "Search by major should be an option."
  - "Maybe a dropdown? It'll be easier."
- Check user emails upon signing up to make sure that they are registered 'hawaii.edu' accounts.
- Include character limits
- Fix price/any number fields by setting a limit

Thank you again to Jewel R., Michael S., Alex N., Jathryn R., Osiris S., Charlie D., and Arleigh R. for your feedback on the 
application!

### Community Feedback

We want to hear from you! We are interested in your experience using TextRealm! You can contact us directly by direct 
messaging any of our members via GitHub or through one of us [here](#the-team).

### Our Next Steps
If we were to add to our project, we would:
* Add a wishlist option: if the user wants to save textbooks so that they can reference it later, we plan to implement a 
wishlist/favorites page where the user can click an icon to save it and click the wishlist page in the navigation bar to 
access it later.
* Set up a function/component where a default email can be sent to the seller about a buyer who is interested in the book that 
they are selling.
* Indicate that a book was sold.
* Allow users to visit other users' profiles.
* Give admins the power to delete reviews and send out default warning emails for those that post inappropriate content.
* Filter out swear words, slurs, inappropriate phrases by implementing a function that warns and prevents the user from 
posting a book or a review if they are using inappropriate words
* Improve upon the aesthetics and accessibility, such as back arrows and other aids for users.

Buying and selling textbooks, made easy.

## The site:

http://textrealm.meteorapp.com/#/

## Team: 
* Chan Ung Jeong
* [Sang Nguyen](https://sanngu68.github.io/)
* Sola Takahashi
* [Sophia Elize Cruz](https://sophiaelizecruz.github.io/)

## Table of Contents
* [Overview](#overview)
* [Project Development History](#project-development-history)
  * [Milestone 1](#milestone-1)
  * [Milestone 2](#milestone-2)
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

- Implement the Admin Page
- Implement the Add/Sell a Textbook page, and the page to edit entries
- Finish rating system
- Implement User profile page
- Implement the Registration/Login page
- 'Not found' page, and loading components

## Mockups

As of now, these are our current mockups.

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


## Profile Page

Includes the user's name, rating, a profile picture, their email, as well as the textbooks that they are currently selling.

<img class="ui medium floated rounded image" src="/mockups/ProfilePage.jpeg" length="800" width="1000">

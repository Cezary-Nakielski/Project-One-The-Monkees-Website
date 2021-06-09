# Table of Contents

- [Table of Contents](#table-of-contents)
- [Project 1 - HTML & CSS - The Monkees Website](#user-centric-development-website-for-the-monkees)
- [UX](#ux)
    - [Strategy](#strategy)
    - [Scope](#scope)
    - [Structure](#structure)
    - [Skeleton](#skeleton)
    - [Surface](#surface)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)


# User Centric Development. Website for The Monkees

This static (front-end only) website is made for "The Monkees" - 1960’s rock band that has around 50 years experience of performing live at numerous events around the world.

The main purpose of the website is to showcase the band's music and publicise their availability to perform at events.

Users of the site can use links to visit the band's social media sites, listen to their music, watch a video clip, view photographs, read about the band members, and check their availability ad book them for an event.

( This is as a milestone project for the HTML & CSS module of the Full Stack Web Development Course at Code Institute. )


## Demo


To access live demo, click <a href="https://www...com/" target="_blank"> here. </a>


# UX

## Strategy

Client's expectations:
- The website shall showcase the band's music - that already made and upcoming.
- The website shall present the band's availability to perform at events such as weddings and Christmas parties.
- The website shall contain information about the band and it's members, their pictures and a video recording of their performance.
- The website shall have links to the band's new Facebook, Twitter and YouTube pages. ( The band is in the process of creating a social media presence. )

Target Users:
* Fans
* Potential fans
* Someone who would like to book the band to perform at an event

User Stories:
* As a potential fan, I want to read about the band, see the band members' photographs & listen to their music, so that I can decide whether I like the band or not.
* As an existing fan, I want to sign up for a newsletter, so that I can receive news about the band.
* As an existing fan, I want to have the option to visit the band's social media pages, so that I can learn more about it and be able to follow it's next moves.
* As someone who would like to book the band for a performance, I want to see the band's availability.
* As someone who would like to book the band for a performance, I want to be able to make a booking request.


## Scope

### Content Requirements
* Images of the band
* Video of the band's performance
* Information about the band and it's members
* Information about the band's availability (Calendar)

### Functional Requirements
* Option to subscribe to a newsletter
* Contact form (Expected to be mainly used to book the band for a performance)
* Social media buttons - Icons serving as hyperlinks redirecting users to social media pages belonging to the band
* Navigation - Section of the page containing navigational buttons which - upon interaction/click - will take the user to a section of the page corresponding to the description given by the text on the button
* Information about Privacy Policy and Terms of Use


## Structure

### Interaction Design

* The Band's logo in the navbar acts as a hyperlink sending the user back to the homepage of the website.


* Social media logo icons placed in the navbar serve as links to corresponding social media pages belonging to the band (opened in a new tab).


* Newsletter sign-up: input field for e-mail address and a submit button.
* Newsletter sign-up form contains required fields: e-mail address 
    * Error messages inform the user if the required field has been left empty or format of the information entered is different than required.


* Initially, navigation menu is situated on the top of the page, in the navbar.
* Navigation menu stays fixed to the top of the screen at all times.
* Navigation menu changes into a burger menu on mobile devices.


* Contact form contains required fields: first name, last name, e-mail address, message
    * Error messages inform the user if the required fields have been left empty or format of the information entered is different than required.


* Hypertext links in the footer for viewing Privacy Policy and Terms of Use

### Information Architecture

* Arrangement and priority of content:

Sections of the web page are presented with Progressive Disclosure in mind.

Firstly, pictures and information about the band is shown, then samples of the band's work, then calendar informing the user about the band's availability, and lastly - a contact form.

Additionally, social media brand logo icons allow the user to visit the band's social media pages and a hyperlink in the footer allows the user to view Privacy Policy and Terms of Use (Since it's a project made for educational purposes, the links take the user to services where he/she can generate Privacy Policy and Terms of Use tailored to a specific website)


* Organisational and navigational schema:

Navigation menu stays fixed to the top of the screen at all times. The menu buttons - when clicked/interacted with - will take the user to a section of the page corresponding to the description given by the text on the button or a suggestive icon.
The menu changes into a burger menu on mobile devices.


## Skeleton

### Navigation Design

* Initially navigation menu is situated on the top of the page, in the navbar.
* Navigation menu stays fixed to the top of the screen at all times.
* Navigation menu changes into a burger menu on mobile devices.

* Social media brand logo icons placed in the navbar serve as links to corresponding social media pages belonging to the band (opened in a new tab).

* Privacy Policy and Terms of Use hypertext links in the footer take the user to external wensites (opened in a new tab).

### Interface design


* Nav Bar:
    * All devices:
        *   Logo 
        *   Social media brand logo icons
        *   Newsletter sign-up section: Input field for e-mail address + submit button
        *   Navigation menu - Buttons: Band, Watch & Listen, Availability, Contact
    * Mobile only:
        *   Navigation menu changes into a burger-style menu

* The Band:
    * Desktop & Tablet:
        *   Picture of the band - middle of the page
        *   Information about the band - middle of the page
        *   Picture of each of the band members - alternating sides - left , right, left, right
        *   Information about each of the band members - alternating sides - right, left, right, left
    * Mobile:
        *   Picture of the band - middle of the page
        *   Information about the band - middle
        *   Picture of each of the band members - middle
        *   Information about each of the band members - middle

* The Music:
    * Desktop, Tablet:
        *   Embedded audio player x 4 - left side of the page
        *   Embedded video player - right side of the page
    * Mobile:
        *   Embedded audio players x 4 - middle
        *   Embedded video player - middle

* Availability:
    * Desktop, Tablet:
        *   Text - left side
        *   Calendar - right side
    * Mobile:
        *   Text - middle
        *   Calendar - middle

* Contact:
    * All devices:
        *   Contact form - middle

* Footer:
    * All devices:
        *   Hypertext link: Privacy Policy
        *   Hypertext link: Terms of Use

### Wireframes

Wireframes for the project can be found <a href="...." target="_blank"> here. </a>


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


To access live demo, click <a href="https://cezary-nakielski.github.io/Project-One-The-Monkees-Website/" target="_blank"> here. </a>


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

Wireframes for the project can be found <a href="https://github.com/Cezary-Nakielski/Project-One-The-Monkees-Website/blob/master/assets/wireframes/The%20Monkees%20Website.pdf" target="_blank"> here. </a>


##  Surface

* Colours - Retro colours palette theme
* Typography - Musicals font by ©2000 Brain Eaters Font Co./Brad O. Nelson.
* Images - provided by Code Institute
* Logo - image downloaded from [imgbin.com](https://imgbin.com/png/fTucBHaP/the-monkees-logo-music-head-film-png), provided by lp3
* Audio player x 4 - mp3 tracks provided by Code Institute
* Video player - video clip provided by Code Institute
* Major elements/sections from top to bottom: Nav Bar, Sections (The Band, The Music, Availability, Contact), Footer


## Features

### Existing Features

- Social media logo icons - allow users to visit the band's social media pages, by having them press the icons. The pages will be opened in a new tab

- Embedded audio players - allow users to listen to the band's music, by pressing the play button.

- Embedded video player  - allows users to watch the band's video clip, by pressing the play button.

- Contact form - allows users to contecct the band/book the band for an event, by having them fill out: name, e-mail address, message input fields and press send button.

- Privacy Policy and Terms of Use hyperlink text links take the user to external websites 

### Features Left to Implement

- Scrollspy functionality for the menu
- Multiple use of parallax effect across the website
- Landscape view on tablet and mobile devices
- The Calendar in the "Availability" section could use actual information about the future events from a website like [www.ticketmaster.com](https://www.ticketmaster.com/the-monkees-tickets/artist/735678) through the use of an API

## Technologies Used

- [HTML]
- [CSS]
- [Bootstrap]

## Testing

Manual Testing Implemented:

- Continuous testing with Chrome Development Tools during development:
    - Reviewing the look and "feel" of the web page
    - Testing responsiveness to changes in screen size

- Testing that all features work properly (on all screen sizes):
        - Logo - when clicked/interacted with - take the user tot the top of the page.
        - Navigation menu buttons - when clicked/interacted with - take the user to a desired section of the page.
        - Hyperlinks - social media brand logo icons in the navigation bar - open desired pages in a new tab.
        - Hyperlinks in the footer take the user to external websites.

- Testing newsletter sign-up section & contact form:
    - Submit button works correctly.
    - Input fields are connected properly.
    - Error messages diplay correct information when input errors are detected.
    - The form is submitted only when all required input fields are filled in and are filled in with correct format input.

- Navigation menu stays fixed to the top of the screen at all times, on all screen sizes.

- Audio and video players work correctly.

- All text is readible on mobile, tablet and desktop screens and is not obscured by images or colors.

Official W3C validator services have been used to check the validity of the code, both HTML & CSS.

All goals of the users presented earlier in the User Stories section of this README can be achieved upon proper wiring of the newsletter form, calendar and contact form, which is out of the scope of this project.

- Tested using [Google Mobile Friendly Test](https://search.google.com/test/mobile-friendly) - reslt: Mobile Friendly 
- Tested using [Webpagetest](https://www.webpagetest.org/) 

## Deployment

The project is hosted on GitHub Pages. The repository can be found <a href="https://github.com/Cezary-Nakielski/Project-One-The-Monkees-Website" target="_blank"> here</a>. It is deployed from master branch the following way:
1. In the GutHub repository select Settings.
2. In the GitHub Pages section select Master Branch as a Source.

To run locally, type: git clone https://git@github.com:Cezary-Nakielski/Project-One-The-Monkees-Website.git into your IDE terminal.

## Credits

### Content

- Text for the landing view section was copied from the [Wikipedia article "The Monkees"](https://en.wikipedia.org/wiki/The_Monkees)
- Text for section "The Band" was copied from:
    - [Wikipedia article "Micky Dolenz"](https://en.wikipedia.org/wiki/Micky_Dolenz)
    - [Wikipedia article "Peter Tork"](https://en.wikipedia.org/wiki/Peter_Tork)
    - [Wikipedia article "Michael Nesmith"](https://en.wikipedia.org/wiki/Michael_Nesmith)
    - [Wikipedia article "Davy Jones (musician)"](https://en.wikipedia.org/wiki/Davy_Jones_(musician))


### Media
- Audio files, video files and photos of individual band members used on this site were provided by Code Institute
- Image used for the background of The Music section was provided by Code Institute
- Image used for the background of Landing View section obtained from - KING COLLECTION/PHOTOSHOT/GETTY IMAGES through the use of Google Advanced Image Search
- Image used for the background of Availability section was obtained from [www.flickr.com](https://www.flickr.com/photos/tonyshek/46759964564/in/album-72157677433451397/), provided by GabboT
- Image used for the background of Contact section obtained from Michael Ochs Archives through the use of Google Advanced Image Search
- Logo image has been downloaded from [imgbin.com](https://imgbin.com/png/fTucBHaP/the-monkees-logo-music-head-film-png), provided by lp3


### Acknowledgements

- I received inspiration for this project from lessons and material provided by Code Institute

- [Google Fonts](https://fonts.google.com/)
    - The project uses fonts provided by Google Fonts.

- [Font Awesome](https://fontawesome.com/)
    - The project uses icons provided by Font Awasome.

- Information and ideas used in building this website were obtained from:
    - [www.w3schools.com/](https://www.w3schools.com/)
    - [www.stackoverflow.com](https://stackoverflow.com)
    - [www.developer.mozilla.org](https://developer.mozilla.org/en-US/)

- w3c Validator services:
    - [HTML](https://validator.w3.org/)
    - [CSS](https://jigsaw.w3.org/css-validator/)


* This website was made for educational purposes
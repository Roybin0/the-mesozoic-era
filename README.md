# The Mesozoic Era

## Introduction

Welcome to The Mesozoic Era - a time when dinosaurs roamed the Earth!

And a website designed to give users a brief education on the Mesozoic Era and the creatures that lived on Earth then. The Mesozoic Era lasted for millions of years and so can be broken up into multiple time periods. This website takes a closer look at Earth's history during each time period and aims to inform users about how dinosaurs flourished and died during this time. The website has four pages: Home, Time Periods, Extinctions and Contact giving visitors multiple informational pages to choose from.

![](https://roybin0.github.io/the-mesozoic-era/assets/images/amiresponsive-mesozoic.png)

The link to the live website can be found here: [The Mesozoic Era](https://roybin0.github.io/the-mesozoic-era/index.html).

## Table of Contents

* [User Experience](#ux)
    * [User Stories](#user-stories)
    * [Strategy](#strategy)
    * [Scope](#scope)
    * [Structure](#structure)
    * [Skeleton](#skeleton)
    * [Surface](#surface)
* [Features](#features)
    * [Navigation](#navigation)
    * [History](#history)
    * [Slideshow of images](#slideshow-of-images)
    * [Video](#video)
    * [Contact form](#contact-form)
    * [Footer](#footer)
* [Testing](#testing)
* [Errors](#errors)
* [Validator Testing](#validator-testing)
* [Lighthouse Report](#lighthouse-report)
* [Deployment](#deployment)
* [Credits](#credits)
    * [Media](#media)
    * [Reference Material](#reference-material)
    * [Other Code](#other-code)
    * [Acknowledgements](#acknowledgements)
   

## UX

## User Stories

As a <strong>User</strong> I want:

1. To navigate a site quickly and easily
2. To see clear and concise information structured well
3. To have multiple options for learning - reading text, image slideshow, video
4. To use any device without seeing an impact on experience

As a <strong>Site Owner</strong> I want:

1. To provide a practical, well structured site
2. To ensure navigation is easy throughout each page
3. To meet accessibility minimum standards on all devices

## Strategy

* Project Purpose
    * The purpose of this website is to educate users about the history of Earth during the Mesozic Era, with particular focus on dinosaurs. It also gives users an option to submit a contact form through the website. 
    * This website is designed for use by anyone. Students learning about this period, or simply people with an interest in history and dinosaurs can easily access relevant information and see how to learn more.
   
## Scope

* Website features
    * Responsive design for multiple screen sizes
    * Visually pleasing and clear structure
    * Use of media - images & videos - in slideshows  
    * Ability to contact me via a contact form
    
    <br>
   
* Content features
    * Slideshow is fast to change to next image/video
    * Accurate content
   
## Structure

* Clear layout with easy to find information.
* Responsive design. 
* Colours, fonts, images and videos are accessible for all users.
* The Header and navigation can be seen on each page. 
* The Home page contains a brief history of Earth leading up to the Mesozoic Era and introduces the user to time periods.
* The Time Periods page looks at each time period of the Mesozoic Era and provides information on, as well as a slideshow of dinosaurs found during that period. It introduces us to mass extinction events.
* The Extinctions page discusses current theories for two extinction events during the Mesozic Era.
* The Contact Us page allows users to submita contact form.
* The Footer is clear on all pages and contains links to social media profiles and the sign up page.

## Skeleton

Figma was used to create wireframes of intial website design. In building the website and after discussion with my mentor, I decided to use different colours for accessibility purposes, and the hope of adding a dark mode in the future. The navigation was shortened and some layout changes made to the Time Periods page. 

### Home page 

 ![](https://roybin0.github.io/the-mesozoic-era/assets/images/figma-home.png)

 ### Time Periods page

 ![](https://roybin0.github.io/the-mesozoic-era/assets/images/figma-time-period.png)

 ### Extinctions page

 ![](https://roybin0.github.io/the-mesozoic-era/assets/images/figma-extinction.png)


### Contact Us page

 ![](https://roybin0.github.io/the-mesozoic-era/assets/images/figma-contact.png)

## Surface 

* Colour scheme was changed to a more contrasting black and white with blue highlights. This was to allow for accessibility and future development of dark mode. 
* Two [Google Fonts](https://fonts.google.com/) were chosen - Barlow Condensed (for headings) and Jost (for paragraphs).

## Features

* The site is laid out over four pages - Home, Time Periods, Extinctions and Contact. 
* Each page contains a header, navigation bar and footer. 
* The home page contains a brief history of Earth up to and including the Mesozoic Era 

## Navigation 

The navigation bar is found on all pages of the website, and includes links to the Home, Time Periods, Extinctions and Contact Us pages. it is fully responsive, changing to a hamburger menu on smaller screens. 

![](https://roybin0.github.io/the-mesozoic-era/assets/images/main-nav.png)

![](https://roybin0.github.io/the-mesozoic-era/assets/images/mobile-nav-closed.png)

![](https://roybin0.github.io/the-mesozoic-era/assets/images/mobile-nav-open.png)

## History

The history timeline on the home page was built using flex design to allow for a better responsiveness. 

![](https://roybin0.github.io/the-mesozoic-era/assets/images/history-homepage.png)

## Slideshow of Images



## Video

## Contact Form

## Footer

## Testing

## Errors 

* On deploying the website, there were issues with loading media on the site. The cause was determined to be an incorrect file path such as `/assets/images/dinosaurs.jpeg`. Removing the initial `/` resolved the issue. 
* Mobile navigation initially failed on all pages except index.html. It was found to be lying under other divs and was resolved by setting a `z-index` in the CSS. 

## Validator Testing

## Lighthouse Report 

## Deployment 

## Credits 

## Media 

## Reference Material

## Other Code 

* Manual slideshow was created with the help of W3 schools. Link to tutorial [here](https://www.w3schools.com/w3css/w3css_slideshow.asp).
* Mobile navigation was created with the help of [Adam Nagy](https://dev.to/javascriptacademy/) on DEV.to. Link to tutorial [here](https://dev.to/javascriptacademy/responsive-navigation-bar-with-mobile-menu-using-html-css-2hpd). 
* Social media links in footer were adapted from Code Institute's Love Running website. Link to code [here](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode/tree/main/06-site-footer/01-footer-main-structure).

## Acknowledgements 


My site was deployed via GitHub using the following steps:
GitHub repository, navigate to the settings tab.
Select the pages link in the setting menu.
Under the GitHub Pages from the source the section drop-down menu, select the master branch.
One the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
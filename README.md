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
* [Features]()
    * [Navigation]()
    * [History]()
    * [Slideshow of images]()
    * [Video]()
    * [Contact form]()
    * [Footer]()
* [Testing]()
* [Errors]()
* [Validator Testing]()
* [Lighthouse Report]()
* [Deployment]()
* [Credits]()
    * [Media]()
    * [Reference Material]()
    * [Acknowledgements]()
   

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
    * The purpose of this website is to educate users about the history of Earth during the Mesozic Era, with particular focus on dinosaurs. It also gives users an option to sign up for more information by email.
    * This website is designed for use by anyone. Students learning about this period, or simply people with an interest in history and dinosaurs can easily access relevant information and see how to learn more.
   
## Scope

* Website features
    * Responsive design for multiple screen sizes
    * Visually pleasing and clear structure
    * Use of media - images & videos - in slideshows  
    * Ability to sign up to a newsletter
    
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
* The Sign Up page allows users to sign up for a newsletter.
* The Footer is clear on all pages and contains links to social media profiles and the sign up page.

## Skeleton

Figma was used to create wireframes of intial website design. While building the website, I decided to use different colours for accessibility purposes, and the hope of adding a dark mode in the future. 

Screenshots of Figma 

## Surface 


## Bugs 

* On deploying the website, there were issues with loading media on the site. The cause was determined to be an incorrect file path such as `/assets/images/dinosaurs.jpeg`. Removing the initial `/` resolved the issue. 
* Mobile navigation initially failed on all pages except index.html. It was found to be lying under other divs and was resolved by setting a `z-index` in the CSS. 

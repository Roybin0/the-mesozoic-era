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
    * [Time Period Block](#time-period-block)
    * [Video](#video)
    * [Contact form](#contact-form)
    * [Footer](#footer)
* [Testing](#testing)
* [Errors](#errors)
* [Future Features](#future-features)
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

## Time Period Block

The time period block was built using flex display so that it is responsive and features a section for text content on one side, and a section for an image or video, or manual slideshow of images or videos on the other. 

A tutorial from W3 schools was followed to achieve this and it allows the user to read interesting facts about the time period, while browsing images of the dinosaurs mentioned in the text. 

![](https://roybin0.github.io/the-mesozoic-era/assets/images/slideshow.png)

## Video

Videos were added to give the user multiple formats for learning about extinction level events during the Mesozoic Era. 

Video does not autoplay and controls are available for users to play/pause as they need to. 

Videos are found only on the Extinctions page which utlises the time period blocks. 

![](https://roybin0.github.io/the-mesozoic-era/assets/images/video-extinctions.png)

## Contact Form

The contact form was adapted from Code Institute's Love Running website. It allows users to get in touch if they have questions or would like to learn more and allows them to choose a contact preference - email or phone. 

![](https://roybin0.github.io/the-mesozoic-era/assets/images/contact-form.png)

## Footer

The footer is found on every page and contains links to the Contact page to social media pages. It also contains a copyright section. 

![](https://roybin0.github.io/the-mesozoic-era/assets/images/footer.png)


## Testing

### Desktop

Google Chrome, Mozilla Firefox & Microsoft Edge; pages load successfully, all links and features working as expected. Responsive behaviour looks good. 

### Tablet & Mobile 

Huawei P20 Pro, Galaxy A40, Galaxy Tab; pages load successfully, all links and features working as expected. Mobile design in place. 

### Chrome Developer Tools 

Responsive behaviour tested thoroughly and looks good. All pages and links working as expected. 

## Errors 

* On deploying the website, there were issues with loading media on the site. The cause was determined to be an incorrect file path such as `/assets/images/dinosaurs.jpeg`. Removing the initial `/` resolved the issue. 
* Mobile navigation initially failed on all pages except index.html. It was found to be lying under other divs and was resolved by setting a `z-index` in the CSS. 

## Future Features 

* I would like to add a dark mode option for users who prefer dark mode. 
* I would like to add another section to the Time Period page with more dinosaur-specific facts and figures for each time period. This would need to act responsive like other elements and not add too much content to the overall page. A separate page could also be considered for this. 

## Validator Testing

### Wave Web Accessibility 

* Contrast errors were initially reported. This related to links found in paragraphs and was fixed by darkening the color for links. Reports are available for each page:
    * [Home](https://wave.webaim.org/report#/https://roybin0.github.io/the-mesozoic-era/index.html)
    * [Time Periods](https://wave.webaim.org/report#/https://roybin0.github.io/the-mesozoic-era/time-periods.html)
    * [Extinctions](https://wave.webaim.org/report#/https://roybin0.github.io/the-mesozoic-era/extinction.html)
    * [Contact](https://wave.webaim.org/report#/https://roybin0.github.io/the-mesozoic-era/contact.html)

### HTML 

* HTML was tested using the WS Nu HTML Checker. No errors found. Reports are available for each page: 
    * [Home](https://validator.w3.org/nu/?doc=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Findex.html)
    * [Time Periods](https://validator.w3.org/nu/?doc=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Ftime-periods.html)
    * [Extinctions](https://validator.w3.org/nu/?doc=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Fextinction.html)
    * [Contact](https://validator.w3.org/nu/?doc=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Fcontact.html) 

### CSS 

* CSS was tested using the W3C CSS Validation Service. No errors found. Reports are available for each page:
    * [Home](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    * [Time Periods](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Ftime-periods.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    * [Extinctions](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Fextinction.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    * [Contact](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Froybin0.github.io%2Fthe-mesozoic-era%2Fcontact.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)   


## Lighthouse Report 



## Deployment 

My site was deployed via GitHub using the following steps:
    1. In the GitHub repository, navigate to the settings tab.
    2. Select the Pages link in the left side menu.
    3. Under Source, change drop-down menu to select the main branch.
    4. Click Save
    5. The page will automatically refresh and display a banner to indicate the successful deployment.

## Credits 

## Media 

* Videos from YouTube - by History of Life, BBC Earth and Science Channel.

* Images from [wikipedia.com](https://wikipedia.com), [jurassicpark.fandom.com](https://jurassicpark.fandom.com/), [fossil.fandom.com](https://fossil.fandom.com/), [dinopedia.fandom.com](https://dinopedia.fandom.com), [dinosaurpictures.org](https://dinosaurpictures.org/) and [britannica.com](https://www.britannica.com/). 

## Reference Material

* Information on this website has been referenced from [Earth How](https://earthhow.com/earth-timeline-geological-history-events/), [National Geographic](https://www.nationalgeographic.com/science/article/dinosaur-extinction), [Wikipedia](https://en.wikipedia.org/wiki/Geologic_time_scale), [Britannica](https://www.britannica.com/science/end-Triassic-extinction), [dinopedia.fandom.com](https://dinopedia.fandom.com) and [dinosaurpictures.org](https://dinosaurpictures.org/). 

## Other Code 

* Manual slideshow was created with the help of W3 schools. Link to tutorial [here](https://www.w3schools.com/w3css/w3css_slideshow.asp).
* Mobile navigation was created with the help of [Adam Nagy](https://dev.to/javascriptacademy/) on DEV.to. Link to tutorial [here](https://dev.to/javascriptacademy/responsive-navigation-bar-with-mobile-menu-using-html-css-2hpd). 
* Social media links in footer were adapted from Code Institute's Love Running website. Link to code [here](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode/tree/main/06-site-footer/01-footer-main-structure).
* Contact page was created with help from Code Institute's Love Running website. Link to code [here](https://github.com/Roybin0/love-running/blob/main/signup.html). 

## Acknowledgements 

* A massive thank you to my mentor Rahul for the fantastic advice and guidance throughout this project 
* Further thanks to my mother for the endless supply of tea 

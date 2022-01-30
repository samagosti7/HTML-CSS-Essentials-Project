# HTML-CSS Essentials Project 1--riddlebank.com
##Introduction
I have always been a fan of riddles, so wanted to create a site which could be the starting point of a large bank into which users could submit their own favorite riddles, growing the bank past the small number of riddles I submitted originally.  

My objective in this project was to create a site in which one could read the question portion of a riddle, then reveal the solution portion in their own time after having tried to solve it. I also pushed to successfully implement several of the pieces we'd learned in the Code Institute to date, with particular emphasis on the HTML and CSS essentials sections.  

The live site can be found here:

![website preview](insert image link her ein assets)

## Table of Contents
<a name="table-of-contents"></a>
#Table of Contents
    [1. User Experience (#ux)
    -[User Goals](#user-goals)
    -[User Expectations](#user-expectations)
    -[Color scheme and font](#color-scheme)
    -[Wire frames (balsamiq)](#wireframes)
        -[Home page](#home-page)
        -[Riddles page](#riddles-page)
        -[Form page](#form-page)
    
    [2. Features](#features)
    [3. Technologies used](#technologies-used)
    [4. Testing](#testing)
    [5. Bugs](#bugs)
    [6. Deployment](#deployment)
    [7. Credits](#credits)

<a name="ux"></a>
#1. User Experience
[Go to Table of Contents](#table-of-contents)

<a name="user-goals"></a>
## 1.1 User Goals
The goal of this site is to provide enjoyable and challenging riddles to any who are interested in solving them, in a way that doesn't spoil the riddle by failing to hide the solution. 

<a name="user-expectations"></a>
## 1.2 User Expectations
--Site should be easy to navigate, separate pages should be clearly labeled and navigation between the three should be consistent and straightforward
--Layout of each individual page should make semantic sense
--General structure should remain the same across pages. Font, color scheme, header and footer style, etc.
--Text should be sensibly positioned on the page and easily legible
--The "add a riddle" process should be intuitively laid out and labeled, offering minimal obstacles to submitting the riddle
--Responsive design for all pages

<a name="color-scheme"></a>
## 1.3 Color Scheme
For reasons likely having to do with superheroes (or more accurately, supervillains), green and riddles often go hand in hand. All but two of the colors used came from a template for green shades and complimentary colors, from https://colors.dopely.top/inside-colors/green-color-palette-inspirations-with-names-hex-codes/.  

Colors Used: 
#01466f  Jade
#3a3a3a  Dark Gray
#75ce9f  Medium Aquamarine
#ffc05e  Chardonnay
Ghostwhite

<a name="wireframes"></a>
## Wire Frames
In coordination with the mentor of this project, we used Balsamiq (https//balsamiq.com/) to create the wireframes for this project. Three wireframe pages were created, all in mobile view, and these were then used as guidelines for the project.  

<a name="home=page></a>
### Home Page
(./assets/images/home-page)

<a name="riddles=page></a>
### Riddles Page
(./assets/images/riddles-page)

<a name="form=page></a>
### Form Page
(./assets/images/form-page)

<a name="features"></a>
# 2. Features
[Go to Table of Contents](#table-of-contents)

### Across entire site:
--Title of the site, riddlebank.com, is located in the same header at the top of the page for all 3 pages. 
--Opacity of site header and all main page headers was edited to 80% make their appearance gentler. 
--Navigation bar is located in a header across the top of the page. Nav list elements were given a border-radius, hover and transition effect for improved aesthetic when the user moves to select them. 
--Gradient background added to header section containing nav bar.  
--hr elements with a solid border were used to divide sections of the page on all pages, specifically separating the nav bar from the content and then the content from the footer.  
--A footer element with social media links, located across a bottom section of the page, exists for all 3 pages. All 4 links (Facebook, Twitter, Instagram, Youtube) open in a new tab. 

### Home Page
--Background image of a black background with a chalk question mark stretches agross a large section of the top of the page, for most laptop sizes. Responsive design is used to replace this image with a dark gray background consistent with the color scheme for all device sizes 1024px and below.  
--Small description blurb is provided to inform the users of the goal of the site, give basic navigational instructions, and let them know they can add their own riddles.  
--About Us section and site description are pushed to the left side of the site, so they don't clash with the question mark which is located on the right side of the background image.  For smaller device sizes, when there is no issue of text overlay on top of the background image, the About Us header and text description are centralized.  

The screenshot of the home page is below:
![home page screenshot](./assets/images/home-page-ss)

### Riddles Page
--Centralized header.
--Small instructional p element added below header to inform users how to reveal solutions, be they on desktop, mobile, or tablet. 
--Dark gray border added around each individual riddle to help separate one riddle from the next.  
--Riddles initially have the same text color as their background, so they are invisible unless the pesudo class of .hover is triggered, in which case the text color changes to be visible on the green background. On mobile deivces, this classes is triggered with a click as opposed to a hover.  

The screenshot of the riddles page is below:
![riddles page screenshot](./assets/images/riddles-page-ss)

### Form Page
--Centralized header.
--Dark gray border added around entirety of the form content.
--Form input elements centralized and separated by br elements to make each input on its own line. This ensures that the form remains more responsive across device sizes.   
--Placeholder text added to username, riddle, and solution section to provide basic input instructions. 
--Large submit button provided at the end of the form, which takes you to a page validating form submission.

The screenshot of the form page is below:
![riddles page screenshot](./assets/images/form-page-ss)



























































Table of Contents:
    Project Overview:  Line 
    Project Motivation: Line
    Directions/Description:  Line
    Validation Screenshots:  Line
    Bugs:  Line
    Credits:  Line

#Milestone Project 1--HTML-CSS essentials project

The ability to create a website is a key skill for web developers. This project is the first of what will hopefully be many sites built in my coding career.  

##Motivation
I love riddles myself, and wanted to create a page that would serve as an online bank of riddles ready to be used whenever the user needed.  While 5 riddles isn't exactly a bank, it is a reasonable start and sufficient within the scope of the project.  Going forward, I would look to increase the riddle count, and possibly add a way to create a group of user-favorited riddles, to appear in a specific section or page of the site.  This mini-bank of favorited riddles is the initial vision I'd had for the site, and was my motivation for creating it.  

##Directions
Any initial link should take you directly to the landing page, titled home.  This features a hero image, and a small about us section.  At the top, as will be present on all site pages, there is a nav element that can take you to the two other pages.  

Page 2, titled Riddles, is the main content page, featuring 5 riddles and their solutions.  The solutions were given a pesudo class of hover, such that in order to see the solution the user must hover over the relevant area.  The hoverable area isn't the entire width of the page, instead it stays closer to the center of the page where the answer will appear--this is to lessen the chances of a user prematurely revealing an answer accidentally.  

The final link will lead you to page 3, the form page where a user would theoretically be able to submit their own riddles to the site. At the moment, of course this won't happen, as the form is being sent only to this URL: https://formdump.codeinstitute.net, the default form practice URL provided to us. However one can test the inputs on this page as if they were submitting their own riddle for consideration.  

##Validation Screenshots--before and after

##Bugs
At the very bottom of the page, there are two small margin-like areas of green surrounding the social media footer. The area at the top of the footer is intentional, however the area at the bottom is not, and I consider it a bug. I entered 0 margin and padding for the overarching html and body elements, and inspecting the area on dev-tools yielded no hints to where it comes from.

Mysterious small grey border around the dividing line (i.e., the styled hr with id "hero-hr") separating nav bar from hero image/header on home page. Less noticeable grey semi-border on the more general styler hr, not there by design.  



##Credits
Code on lines 160-163 and 174-183 were taken from google searches on the subject of placeholder text.  Credit to https://stackoverflow.com/questions/47357063/vertically-align-an-input-placeholder-with-css-or-set-line-height?noredirect=1&lq=1

Header content closely follows the header laid out in the Code Institute Lesson "Creating your first gitpod project. Credit to https://codeinstitute.net/se/

Footer content closely follows and is copied from the footer created in the Love Running project, which was a quasi-project to help us learn the basics of creating a website, completed just before starting this project. Credit to https://codeinstitute.net/se/

Background gradient for nav bar taken from https://cssgradient.io/

Overall complemenetary color scheme taken from https://colors.dopely.top/inside-colors/green-color-palette-inspirations-with-names-hex-codes/





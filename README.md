# DARK FLAME ( a fictitious cover band)

Dark Flame is a cover band of the hugely popular 70's band 'The Band'.<br>
 Aswell as performing in regular gigs in venue's throughout Ireland the
band are also available for private functions<br> such as weddings and 
corporate events.


## Table of Contents
> - [Description](#description)
> - [Ux](#ux)
> - [User Stories](#user-stories)
> - [Features](#features)
> - [Technologies Used](#technologies-used)
> - [Testing](#testing)
> - [Deployment](#deployment)
> - [Credits](#credits)
> - [Acknowledgments](#Acknowledgements)

# Description

This website for the band provides information of the band, gig information,
clips of the band live<br> and a booking form to book the band. The website is intended
to be accessible on all types of devices<br> mobile phone, tablet, laptop and desktop.

# UX

### Strategy

This project is a website for this band to inform fans of up and comming gigs
and to attract new fans to learn more<br> about the band and its members through
the bands biography section on the main page.
Visitors to the site can also<br> get a feel for the band by visiting the sites 
Live sample page which shows video snippets of live performances.<br>

A person or a business can book the band for private functions or corporate 
events through the sites Contact page.<br>

The site is easy to navigate and is made up of multiple web pages.

# User Stories

# Features

This project is a multiple page website with four web pages. All pages have a 
navigation menu is relative to viewport.<br> On the footer of each page there is 
social media icons which when click connect to the relevant social network service.<br>

For mobile phone device’s the navigation menu changes to a hamburger menu as
a responsive layout, site pages such as<br> live sample site videos list layout changes 
to provide the best viewing experience.<br> 

Likewise tablet devices have been accomodated where the layout changes to provide best 
viewing experience.<br> This was done entirely in html and css for good user experience.<br>

* Main Page – Has a small paragraph with band biography information and that the band 
is available for private and <br> corporate functions and an exampple customer testimonial. 
There is a section for gig event timetable – which shows<br> dates and venues of upcoming gigs. 

* Live Samples Page – There is sample youtube videos of the band live which show the 
different musical styles of the<br> band which the user can view. There is a prompts to 
click on Testimonials for customer feedback of those who has seen <br> the band live and to click on Contact 
if visitor to site is interested in booking the band. 

* Testimonial Page – This page list customer testimonials who have booked the band for
functions or have seen the band<br> at live venues. The page broken into section and articles 
outlining each customers testimonials.

* Contact Page –  Is a web form so visitors to the site can book the band for a function 
by filling our a form which includes<br> customer name,email, date of function and a text area 
for special requirement. The is validation on these input fields.

# Technologies Used

* HTML
    * For basic website page structure / markup

* iframe
    * For playing youtube videos

* CSS3
    * CSS3 for styling the website pages aligning elements with padding, margins and I used Float for positioning elements 

* Font Awesome
    * To provide social media icons for the page footer and for rating stars for Testimonial page. Accessed fontawsome from<br>
      its url as a link in the head of site Pages.
    
* Google Font
    * to make Paragraph Heading on Home page look  clearer I used Abril font-family referencing https://fonts.google.com/ CDN<br>
      in the style css.

# Testing

Testing was done manually by me and also by members of my family.

* Forms testing:<br>
   I tested the Contact page form on different devices and browsers. 
   This was done by clicking the form submit button on the <br>Contact page
   with the form fields empty to make sure it resulted with the desired response of 'Please fill out this field'.

The following bug was found early on
Issue:<br>
There was an issue in the Social Media Links  - 1 out of the 4 social media were clickable
this is part of an un-ordered<br> list Item where each social media name showing would be clickable
this bug appeared in initial commit

original code in initial commit was
```html
<li><a href="https://www.twitter.com" target="_blank"></a>Twitter</li>
<li><a href="https://www.youtube.com" target="_blank"></a>Youtube</li>
<li><a href="https://www.instagram.com" target="_blank"></a>Instagram</li>
```

Resulted in the Names not being clickable!!

fixed code with:
```html
<li><a href="https://www.twitter.com" target="_blank">Twitter</a></li>
<li><a href="https://www.youtube.com" target="_blank">Youtube</a></li>
<li><a href="https://www.instagram.com" target="_blank">Instagram</a></li>
```
tested and issue was fixed, commited change to github.

Another issue:<br>
I encountered an issue playing youtube video within iframe when 
I included the youtube link as the iframe source it<br> failed to display I
got the message 'www.youtube.com refused to connect'<br>
It turns out iframe only plays youtube videos on embed urls.

Original code with standard youtube url:
```html
iframe src="https://www.youtube.com/watch?v=IYPVyJwzerM"
```
fixed by include youtube embeded link instead:
```html
iframe src="iframe src="https://www.youtube.com/embed/IYPVyJwzerM"
```


This project site is completely responsive with different layout on iphone5, ipad and desktop device views.<br> This was 
done using media queries.

iphone5 - view: <br>
* menu : is a burger menu icon on the top right- when clicked opens with menu options (home, live, testimonials, contact) 
below the site title.<br> When you click any of the menu option it directs you to the relevant site page and menu options disappears back to burger menu
icon.

* Home page: The page layout sections are organized stacked below each other (sections image, Bio, gig event wrapper, footer social icons)

* Live page: The page layout sections videos are stacked below each other, below this is paragraph text and below this is footer social icons.

* Testimonial page: The page layout sections are organized stacked below each other (section site rating, customer review scroll section,Image,footer social icons. 
* Contact page: The page layout sections are organized stacked below each other (sections Booking form,Image,footer social icons)

ipad - view:<br>
* menu: standard menu same style as the one in desktop view with menu options on the top right of the site page with options below:

* Home page: The page layout sections are organized .....(sections image, Bio, gig event wrapper, footer social icons)

* Live page: The page layout sections videos in a quad view, below this is paragraph text and below this is footer social icons.

* Testimonial page: The page layout sections are organized section site rating, customer review scroll section,Image,footer social icons. 

* Contact page: The page layout sections Booking form,Image,footer social icons


# Deployment
Local git repository was initated in the begining of this project and several commits were made during 
the development. <br> Project was pushed to remote repository on https://github.com

# Feature would like:
Features we would like is a Store page where merchandise such as music and cloths(eg band t-shirts) can 
be purchased.<br> Discussed with Mentor he says to leave it out as not needed for this project.

# Credits
## Media
  * The photos used on: 
    * Testimonial Page – you are what you listen to image<br>
      Sourced from : https://medium.com/the-post-grad-survival-guide/you-are-what-you-listen-to-but-what-if-you-change-the-song-accb18740f2b
 
    * Contact Page - Flaming Guitar<br>
      Sourced from : https://media.istockphoto.com/photos/guitar-on-fire-with-black-background-picture-id147712563?k=6&m=147712563&s=612x612&w=0&h=crIy_S-juGaAMNr9SDOnJKqi20dvP3xnDvVnhZOKFCA=

    

## Acknowledgements

   * Home Page gig guide was taken from the following youtube video https://www.youtube.com/watch?v=iOrJ63dQ9eE 

   * I resolved the youtube playing in the iframe issue (for full explanation see the Testing section above) from<br>
     the following site: https://www.youtube.com/watch?v=9YffrCViTVk 
    
   * For the Mobile phone Burger menu I drew inspiration from the following site https://www.youtube.com/watch?v=xMTs8tAapnQ 




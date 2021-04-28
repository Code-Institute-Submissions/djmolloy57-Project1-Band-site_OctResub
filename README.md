# DARK FLAME ( a fictitious cover band)

Dark Flame is a cover band of the hugely popular 70's band 'The Band'.
Aswell as performing in regular gigs in venue's throughout Ireland the
band are also available for private functions such as weddings and 
corporate events.

# UX

This project is a website for this band to inform fans of up and comming gigs
and to attract new fans to learn more about the band and its members through
the bands biography section on the main page.
Visitors to the site can also get a feel for the band by visiting the sites 
Live sample page which shows video snippets of live performances.

A person or a business can book the band for private functions or corporate 
events through the sites Contact page.

The site is easy to navigate and is made up of multiple web pages.

# Features

This project is a multiple page website with four web pages. All pages have a 
navigation menu is relative to viewport. On the footer of each page there is 
social media icons which when click connect to the relevant social network service.
For mobile phone device’s the navigation menu changes to a hamburger menu as a 
responsive layout, site pages such as live sample site videos list layout changes 
to provide the best viewing experience. Likewise tablet devices have been accomodated 
where the layout changes to provide best viewing experice. This was done entirely in 
html and css for good user experience.

* Main Page – Has a small paragraph with band biography information and that the band 
is available for private and corporate functions and an exampple customer testimonial. 
There is a section for gig event timetable – which shows dates and venues of upcoming gigs. 

* Live Samples Page – There is sample youtube videos of the band live which show the 
different musical styles of the band which the user can view. There is a prompts to 
click on Testimonials for customer feedback of those who has seen the band live and to click on Contact 
if visitor to site is interested in booking the band. 

* Testimonial Page – This page list customer testimonials who have booked the band for
functions or have seen the band at live venues. The page broken into section and articles 
outlining each customers testimonials.

* Contact Page –  Is a web form so visitors to the site can book the band for a function 
by filling our a form which includes customer name,email, date of function and a text area 
for special requirement. The is validation on these input fields.

# Technologies Used

* HTML

* CSS3

* Font Awesome

# Testing

Testing was done manually by me and also by members of my family

The following bug was found early on
Issue:
There was an issue in the Social Media Links  - 1 out of the 4 social media were clickable
This was part of an un-ordered list Item where each social media name showing would be clickable
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

This project is completely responsive with different layout on iphone5, ipad and desktop device views. This was 
done using media queries.

# Deployment
Local git repository was initated in the begining of this project and several commits were made during 
the development. Project was pushed to remote repository on https://github.com

# Feature would like:
Features we would like is a Store page where merchandise such as music and cloths(eg band t-shirts) can 
be purchased. Discussed with Mentor he says to leave it out as not needed for this project.

# Credits
## Media

## Acknowledgements





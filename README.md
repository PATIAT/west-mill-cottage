<h2 align="center"><img src="assets/readme-images/west_mill_cottage_logo.png"></h2>

# West Mill Cottage  

## Code Institute Milestone Project 1 – Static Front End Project  

*  West Mill Cottage is a blissfully tranquil riverside cottage set in rural countryside where England meets Scotland. The objective of the website is to appeal to prospective and returning tenants. The website is designed to be fully responsive so that the users experience is consistent across any device.   

* This website has been developed for the Milestone Project 1 submission as part of the Diploma in Web Application Development course facilitated by Code Institute and City of Bristol College.  

* This static front end website has been built using the different programming languages learned during the course, including HTML and CSS. The website has also utilised the Bootstrap framework technology.  

## Live Project  

[You can view the live project here.](https://patiat.github.io/west-mill-cottage/)

## GitHub Repository  

[You can find the project repository here.](https://github.com/PATIAT/West-Mill-Cottage)

# Contents  

- [User Experience](#user-experience)  

  * [User Stories](#user-stories)  

    + [Prospective tenants](#prospective-tenants)  

    + [Returning tenants](#returning-tenants)  

    + [Business owners](#business-owners)  

- [Design](#design)  

  + [Colour scheme](#colour-scheme)  

  + [Typography](#typography)  

  + [Imagery](#imagery)  

  + [Icons](#icons)  

- [Structure](#structure)  

  + [Information Architecture](#information-architecture)  

  + [Navigation Bar](#navigation-bar)  

  + [Back To Top Button](#back-to-top-button)  

  + [Buttons](#buttons)  

  + [Page Heading & Sub Navigations](#page-heading-and-sub-navigations)  

  + [Footer](#footer)  

# User Experience  

## User Stories  

### Prospective Tenants  

*The website users that fall into this category are considering visiting the area and are already looking for appropriate accommodation.*  

* As a prospective tenant, I would like to have an overview of the holiday cottage to determine if it is suitable for my requirements.  

*  As a prospective tenant, I would like to know the details of the holiday cottage including its attributes such as; number of bedrooms, bathrooms etc...  

* As a prospective tenant, I would like to know what activities and attractions are available in the local area.   

* As a prospective tenant, I would like to be able to contact the owners if I have any questions or special requests.  

### Returning Tenants  

*The website users that fall into this category are people or families that have previously stayed and enjoyed the holiday cottage and are looking to return.*  

* As a returning tenant, I would like to know if the holiday cottage has any new attributes, such as additional facilities etc...  

* As a returning tenant, I would like see genuine reviews from other people and families that have stayed at the holiday cottage.  

* As a returning tenant, I would like to know if there are any upcoming events in the local area that I could attend on my visit.  

* As a returning tenant, I would like to be able to let the owners know I am returning tenant so I can receive potential discounted rates.  

### Business Owners  

*The business owners are the owners of the holiday cottage and of the website*  

* As the business owner, I would like my website to be user friendly across all devices and accessible to visually impaired users.  

* As the business owner, I would like the website to promote the quality of the cottage and the activities and attractions in the local area.  

* As the business owner, I would like the website to emphasise the openness of us as owners and promote the asking of questions from users via the contact form and social media platforms.  

## Design  

### Colour Scheme  

#### Primary Colours
<h2 align="center"><img src="assets/readme-images/primary_colours.png"></h2>  

#### Secondary Colours
<h2 align="center"><img src="assets/readme-images/secondary_colours.png"></h2>  

 - A simple colour scheme has been used with three primary colours and three secondary colours. The colours are all relatively light with dark type being used in contrast to give a refined and clean appearance.  

- This colour pallette has been chosen with the website imagery in mind. This is because the images are going to be what catch the user's attention.  

- I used the [Material Design Colour Tool](https://material.io/resources/color/#!/?view.left=0&view.right=0) to decide on colour choices.  

### Typography  

- Headings are in Aboreto and normal text is in Lato. Aboreto is a cursive font which is eyecathing and sophisticated which is in keeping with the style of the holiday cottage. Therefore cursive is the fallback font should Aboreto be unavailable. Lato is a clean and legible font which is commonly used for websites all over the world. Sans serif is the fallback font should Lato be unavailable.  

### Imagery  

- The images have been provided by the business owners and offer a genuine representation of the standard of the holiday cottage. The images are therefore a very important feature of the website as they must be of high quality to portray the holiday cottage in the same light.  

- Each of the pages uses different image layouts, this is due to the focus and purpose of each page being different e.g., carousel on the home page to give a taste and more focused images on the property details page e.g., kitchen, bathroom etc.  

- Most of the images are in landscape orientation and the use of the same aspect ratio for all images allows for a consistent user experience.  

- Both ARIA roles and attributes as will as alt tags have been used to assist users with disabilities.

### Icons  

- All icons were sourced from Font Awesome and have been used sparingly across each page to allow for a more focused approach to catch the users attention.  

- Screen reader utilities such as sr-only have been utilised to assist users with disabilities.

## Structure  

### Website Architecture  

- This website has a home page and a further 5 pages, namely;    Property Details, Location, Activities, About and Contact.  

  - Home page – This is the landing page with a hero image and descriptions and navigation to the other pages.  

  - Property details - This page provides information about each room of the house which contains images and text.  

  - Location - This page provides information about where the holiday cottage is located, geographically and provides options on different modes of transport on how to get there.  

  - Activities - This page provides details on what activities are available to participate in within the local area of the holiday cottage.  

  - About - This page provides some brief and basic information from the owners of the holiday cottage to allow users to see the people behind the project.  

  - Contact - This page provides a contact form to allow users to contact the owners with questions regarding their potential stay or to enquire about returning as a tenant.  

  - Each page features a main ‘call to action’ which is achieved through a combination of images and buttons. The aim was to allow users to get to the information the page has to offer in as few steps as possible. 

  - The website utilises continuous scrolling pages and collapsible menus to display the majority of its information.

  - Visually impaired users and those with disabilities have been considered and a semantic layout has been utilised in combination with aria roles and attributes. 

### Headings and sub headings 

  - Each page of the website contains a heading to consistently show the user what to expect on each page. 
 
  - All of the pages have subheadings to clearly demonstrate a separation of content that helps the user experience when navigating the content. 

### Navigation Bar 

  - Each of the pages maintains the same navigation section which allows all users to easily navigate between the pages without having to use the browser or return to the homepage.  

  - The website utilises a collapsible navigation bar which shrinks as the screen size decreases until a hamburger icon is used to open and close the navigation menu.

  - The navigation bar was sourced from bootstrap documentation and has been customised using CSS to create a unique background, font and colour combination.

  - The active page is shown in a different colour to the rest of the navigation links and is underlined while active. Aria controls are in place to assist visually impaired users. This along with the hover changes were implemented with the use of CSS and bootstrap. 

  - Each page, except location.html and contact.html has a back to top of page button at the bottom of each page, just above the footer. This was implemented to improve user experience and reduce swipes and scrolls of screens. 

### Buttons 

  - The buttons used across the pages are consistent throughout using the colour palletes of the primary and secondary colours as details above.  

  - The text on each of the buttons is followed by a greater than sign to guide the user to follow the link. 

  - The buttons use a hover class so when the user hovers over it, it changes colour. Both colour variants were assessed and determined to be legible. 

  - Bootstrap buttons were used and customised with CSS.

### Footer 

  - The footer is consistent on each page and contains the logo, address, telephone, email and social media links. 

  - The telephone and email links have been added and tel and mailto links. 

  - All links to external social media sites open in a new tab. 

  - The social media icons were source from font awesome.

### Wireframes 

- [You can view my wireframes in PDF form here.](https://github.com/PATIAT/west-mill-cottage/blob/main/assets/wireframes/west-mill-cottage-wireframes.pdf) 

# Features 
 
## Current Features 
 
### Responsive on all device sizes 

  - The development of this website was mobile first, therefore the website is fully responsive on all device screen sizes. 

  - I have used the Bootstrap grid concept and adjusted the layout according to the size of the devices screen size. In some cases this was facilitated by the use of CSS media queries.

### User interaction 

  - Image carousels on the home page feature forward and backward buttons which the user is able to control. 

  - There is an accordian on the property details page which the user is able to click to show and hide the information.

  - A google maps iframe has been included on the location page to allow users to acquaint themselves with the geographical location of the holiday cottage. 

  - The navbar turns into a drop down (hamburger on smaller devices). 

## Future Features 

### Bookings 

  - A booking form which allows users to choose dates for a potential stay could be developed and included. 

### Affiliate program with local businesses 

  - Users who book with the site could benefit from discounts to local events and activities to promote other local businesses. 

### E-commerce 

  - The website could offer merchandise related to the holiday cottage or local area attractions for people to buy as souvenirs or gifts. 

# Technologies Used 
 
## Languages Used 
 
- [HTML5](https://en.wikipedia.org/wiki/HTML5) 
 
- [CSS3](https://en.wikipedia.org/wiki/CSS) 

## Frameworks Libraries and Programs 
 
- [Bootstrap 5.2](https://getbootstrap.com/)  
  - I used bootstrap throughout the site to make it responsive. The website uses Bootstrap's Containers, Grid System and Flexbox and Button classes. I sourced code from the Bootstrap documentation when building the Navbar, Carousel, Buttons and Contact Form,  
   
- [Google Fonts](https://fonts.google.com/) 
  - Two fonts were imported from google fonts. Aboreto for the headings, and Lato for the general text. 
   
- [Font awesome](https://fontawesome.com/) 
  - Icons were used from font awesome to add texture to some of the pages and styles.
 
- [Gitpod](https://gitpod.io/) 
  - Gitpod was used to create the folder structure and write the code and content. 

- [Git](https://git-scm.com/) 
  - Git was used for version control in the terminal. 
 
- [Github](https://github.com/) 
  - Github was used to create and store the project repository. 
  
- [jQuery](https://jquery.com/) 
  - jQuery is associated with the bootstrao cdn and assists in the navigation responsiveness. 
 
- [Balsamiq](https://balsamiq.com/) 
  - Balsamiq was used to create Wireframes for the project. 

- [Adobe Illustrator](https://adobe.com/) 
  - Adobe Illustrator was used to amend the colours of the vector art used on the navbar and footer. 

- [Vecteezy](https://www.vecteezy.com/free-vector/floral-pattern)
  - Vecteezy was used to source the floral pattern used in the navigation and footer sections.

- [Material Design Colour Tool](https://material.io/resources/color/#!/?view.left=0&view.right=0) 
  - The colour tool from Material Design was used to decide on the colour scheme for the website and the tools helped assess the legibility.

- [Techsini](https://techsini.com/multi-mockup/) 
  - Techsini was used to help check responsiveness and take screenshots of the page at different screen sizes.

- [IloveIMG](https://www.iloveimg.com/resize-image#resize-options,pixels)
  - I love IMG was used to re-size some of the images used.

- [Pexels](https://www.pexels.com/) 
  - Pexels was used to source images for the website which were not of the holiday cottage itself.

- [TinyPNG](https://tinypng.com/) 
  - TinyPNG was used to compress images for a faster loading time. 
 
- [WebFormatter](https://webformatter.com/html) 
  - WebFormatter was used to help beautify the code.

- [Google Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) 
  - Google Chrome's Dev Tools were utilised during the build of the project to test functionality, responsiveness and for debugging purposes.

- [Canva](https://www.canva.com/)
  - Canva was used to create the logo and the favicon used on the website and README documentation. I decided not to use the logo on the navbar as it was distracting and I felt the typography alone looks more visually pleasing.

# Testing 

- For all testing documentation, please [click here](https://github.com/PATIAT/west-mill-cottage/blob/main/TESTING.md) for more information.
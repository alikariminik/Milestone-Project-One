# Grizzo's Restaurant README

This is the website for the fiction London-based Restaurant called Grizzo's. It is designed to entice  potential customers enough to make a booking through the use of its various menus and images across a easily navigavle website. The website aims to be responsive and accessibile on a range of devices, making it easy to navigate for customers.

### The Strategy Plane
When beginning to think about what a website for a restaurant would require, I began by thinking about the business needs and the customer / user needs. 

## User Experience (UX)

 -   #### Customer Goals
    - Immediately understand what the website is trying to offer.
    - Easily be able to navigate the various pages on the site. 
    - Be able to access the site on a range of devices. 
    - Quickly find key business information such as Business Times, Location, Contact details etc.

 -   #### Business Goals
    - Showcase an attractive and user-friendly / navigable site. 
    - Inform the customer what's on offer through the use of downloadable menus.
    - Allow for users on all devices to access the page without issue.
    - Provide key information that customers may want before deciding to book or not as menus, business hours, location, images.

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to quickly understand the main purpose of the site.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content. Key information such as Location, Contact Details and Business Hours should be easily findable. 
        3. As a First Time Visitor, I want to see their menus, decide on whether there is anything I would like to have their, and if so, be able to book a table quickly and easily.

        #### Returninng Visitor Goals

        1. As a Returning Visitor, I want to be able to very quickly find how to book a table or if already have a booking, find a contact number in order to amend the booking.
    

-   ### Design
    -   #### Colour Scheme
        -   The Four main colours used are various shades of Yellow, Orange, White and Black. I have mainly avoided using absolute colours as I found these to be too harsh for the style I wanted to achieve.  
    -   #### Typography
        -   I used the  'Smooch' font for the Logo with 'Cursive' as the fallback font in case for any reason the font isn't being imported into the site correctly. I found 'Smooch' through Google Fonts and I felt as though this font when displaying the name of the restaurant "Grizzo's" gave a clear signature-like look to the site which I felt gave the feeling of a real restaurant.
        - Cursive was used on the Nav Bar as it produced a clean and legible output which is I thought was key for a Nav Bar.
        - 'Gentium Book Basic' was used as Headings across the various site pages to ensure legibility consistency with Sans-Serif used as a fallback font.

    -   #### Imagery
        -   Images over text. When someone visits a restaurant's website, they want to imagine themselves in that restaurant prior to going so that they know what they are potentially going to be spending a signifcant amount of money for. That is why the first thing you see when you access the page is a large back-ground hero image which showcases some of the elegant, eye-catching food that Grizzo's has to offer. This hero-image inconjunction with the the large image of the restaurant itself at the bottom of the Home page capture everything about this restaurant - delicious and elegant looking food in a beautiful, colourful environment.

    ### Wire Frames

-   ## Features

    - ###  Existing Features
        -   Responsive Elements
        -   Booking Form
        -   Gallery which showcases food, interior of the restaurant such as: tables, bar etc.
        -   Table of Business Hours
        -   NavBar with Responsive 'Burger Icon'
        -   Interactive elements - Hover.

    - ###   Features Which I Would Have Liked to Utilise
        -   Scrolling Gallery
        -   Google Maps Box displaying Restaurant Location.

-   ## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

-   [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
-   [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
-   [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Smooch' & 'Gentium' font into the style.css file which is used on throughout the pages of project - further details in Design > Typography section of this file.
-   [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used in the footer to add icons for which harbored links to the restaurant's false Social Media Pages (Links directed to the actual Social Media Homepage rather than any restaurant Social Media page). The Font Awesome Icons themselves were also added for aesthetic and UX purposes.
-   [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
-   [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.

## Testing

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to quickly understand the main purpose of the site.
            - Immediately when the site loads, you are greeted with the nav bar, hero image and the hero image text overlay. The combination of all 3 (primariliy hero image and hero image text overlay) convey the message that this is a fine dining restaurant. 

        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content. Other information such as Location, Contact Details and Business Hours should be easily findable. 
            - The Nav bar is visible straight away and the navigation destinations are clearly defined  through their titles on the nav bar: Menu directs the user to the menus, Gallery to the photos of the restaurant and Book Now to the booking form.
            - Location, Contact Details and Business Hours can all be found on the Home Page. However, on review, I feel as though this information should be included on a seperate page as well as in the footer just incase there are some users who are unaware to check the nav bar. This is something to remember for future projects.
        3. As a First Time Visitor, I want to see their menus, decide on whether there is anything I would like to have their, and if so, be able to book a table quickly and easily.
            - As mentioned above, the menus and booking form are included in the nav bar which allows for quick and easy navigation. 


### Validators
###### The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
-    [W3C HTML Validator](https://validator.w3.org/nu/) - 
    -   index.html: Needed to change "alt" to "title" to correctly give alternative text to images which were backgrounds of divs. There were 2 occurences of this.
    -   index.html: <script> was not included within the body. Moved into the bottom of the body.

    -   menu.html: Needed to change "alt" to "title" to correctly give alternative text to images which were backgrounds of divs. There were 4 occurences of this.
    -   menu.html: <script> was not included within the body. Moved into the bottom of the body.
    -   menu.html: Element h3 & h5 not allowed as child of element span in this context. Changed these Spans to Divs to overcome this error. Then  added IDs to these Divs which targetted their heights and widths (overiding "menu-blocks div" height and width which were causing responsiveness issues)
        Result was a better responsive text-overlay which sat in the center of the images regardless at whatever screen size.

    -   gallery.html: Section lacks heading. Changed Section to Div.
    -   gallery.html: <script> was not included within the body. Moved into the bottom of the body.

    -   booking.html: No space between attributes. 2 occurences.
    -   booking.html: The element button must not appear as a descendant of the a element. Removed.
    -   booking.html:Attribute placeholder is only allowed when the input type is email, number, password, search, tel, text, or url. Removed placeholder.
    -   booking.html:Attribute placeholder is only allowed when the input type is email, number, password, search, tel, text, or url. Removed placeholder.
    -   booking.html: Bad value 23/01/2022 for attribute min on element input. Removed.

    -   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - 
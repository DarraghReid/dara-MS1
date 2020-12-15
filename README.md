# DaRa Website
View the live project [here](https://darraghreid.github.io/dara-MS1/)

This website was created for Code Institute's Milestone 1 Project as part of the Diploma in Full Stack Web Development. 
The purpose of this project is to demonstrate the student's knowledge and skills aquired thus far in the course. 
This includes skills in HTML, CSS, as well as other User Centric Design skills as outlined in the Technologies section.

This site was created for the musician, DaRa. It is designed for those who wish to listen to his music and contact him, if they wish. 
The site has been designed to be fully responsive across most devices and browsers.

## User Experience (UX)
* User Stories
    * First Time User Goals:  
        1. As a first time visitor, I want to immediately understand the purpose of the site.
        2. As a first time visitor, I want to be able to easily navigate through the site to find what I'm looking for.
        3. As a first time visitor, I want to instinctively know what to do in order to listen to the site owner's music.
        4. As a first time visitor, I want to be able to easily contact the site owner from the site.
    
    * Returning User Goals:  
        1. As a returning user, I want to be able to check for new videos and music.
        2. As a returning user, I want to know the best ways in which I can follow and contact the site owner.
    
    * Site Owner Goals:

        1. As the site owner, I want to be able to showcase my work.
        2. As the site owner, I want to be able to provide a platform to followers where they can stay up to date with my music.
        3. As the site owner, I want users to be be able to contact me easily.
    
## Structure 

The site is designed as a single webpage with multiple sections. 
Each section is linked to in the home page as well as in call-to-action buttons throughout the site.
This should result in fast and intuitive navigation.

The navigation bar is structured from left to right in order of importance,
though the "about" and "listen" sections are swapped when scrolling for visual reasons.

## Design

* Colour Scheme
    * The colours used in this project are rgb(124, 124, 124)/dark grey, rgb(238, 229, 233)/beige-pink, and rgb(243, 178, 114)/orange-yellow.
    The beige-pink and orange-yellow compliment the colour scheme of the content (images and videos) while the dark grey offers a good dark constrast to the other two.

* Typeography
    * The fonts used throughout the site are Roboto and Big Shoulders Inline Text
    Big Shoulders Inline Text is used for the logo as well as all H1 headings,
    while Roboto is used in all other instances.

* Imagery
    * All imagery was supplied by the artist. 
    The images used in the homepage carousel were carefully chosen to give users immediate confirmation as to the type of site they are visiting.
    As mentioned in the User Stories section, it is important for users to immediately understand the purpose of the site.

    The image used in the "About" section was carefully chosen to represent who DaRa is as an artist.

## Wireframes

For a full PDF of this site's Wireframes click [here](). 

![Wireframe of Home Page](assets/images/wireframe-home)

![Wireframe of "Listen" section](assets/images/wireframe-listen)

![Wireframe of "Contact" section](assets/images/wireframe-contact)

### Differences between wireframes and final product.
* The most obvious difference between the wireframes and the finished site is the including of an "About" section.
I felt, in order to create a more rounded site for the artist, an about section where users can learn more about DaRa was important.

* The header of the site is more solid, and the logo is to the left rather than the center. 

* Also, since this is a single-paged site, there is just one footer.

* Instead of a single image in the homepage, I decided a manual carousel was a better option.

* The layout of the video section also deviates from the wireframe. 
The live site displays 3 videos per row on large screens, and two videos per row on medium and small screens.

* The live site also excludes horizontal lines in the "Contact" section, as opposed to the wireframes.

## Features

* Home Page 
    * The home page inclused a responsive navbar. 
    The menu items collapse into a single button on smaller screens.

    * Another feature of the Home Page is the image carousel. 
    This is one of two carousels in the site. 
    As opposed to the carousel in the "About" section, this carousel is made solely of HTML and CSS. 
    I wanted to demonstrate that a fully functional carousel could be made without the need for Javascript or Bootstrap.

        This slider, inspired by YouTuber [Web Decorator](https://www.youtube.com/watch?v=z74ExMz-cWU), was heavily edited for the DaRa site.
        It uses radio buttons and z-index to display a different image at a time.

        There are no stylistic similarities between Web Decorator's slider and the one you see in the finished DaRa site.
        The most obvious difference between my carousel and Web Decorator's is that my carousel is designed to take up the whole viewport width and height and act as an underlay for all other HomePage content.
        This took further playing around with z-index, displays and positions to pull off.
        
        Rather than clickable divs either side of the content to navigate to the next slide, I decided to condence them down into clickable arrows.
        I felt that this would be more intuitive for users. 
        I also elected to display navigation bars rather than dots as I felt this fit better with the layout of the site.

        I also made some changes to the HTML.
        Of course, classes, labels and ids were changed to suite the site. 
        There is also more content in my carousel, and so more code had to be added. 
        For this reason, the radio buttons were given a common class to be addressed in style.css to reduce code clutter.

    * A call to action button is also featured on the Home Page. 
    When clicked, the user is brought to the video section of the site where they can listen to the artist's music.

* About Section
    * The About section features a circular image of DaRa surrounded by three blank, circular divs with partially coloured borders.
    When hovered over, the colored parts of the borders alternate. The image also enlarges when hovered over.

    * Another feature of the About section is the information section which collapses into a carousel on smaller screens.
    For this carousel, I decided to use a Bootstrap 4 carousel template.

    Again, this carousel was heavily edited to suit the site.
    Firstly, my carousel is text based, whereas the Bootstrap carousel is imaged based. 
    Much tweaking was required here to get the text into the required positions.

    I removed the Bootstrap navigation arrows and inserted my own arrows to match the slider in the home page.
    The arrows on my carousel appear on the outside of the content rather than overlaying on top of the content, which is the case with the Bootstraps carousel.

    All styles including sizes and colours have been changed from the original Bootstrap carousel.
    The only remaining feature that bears are resemblance to the the Bootstrap template is the shape of the navigation bars at the bottom of the slider.

    There were extra slides in my carousel and so more code had to be added. 
    An extra div to contain the carousel was also needed to center the slider itself due to its modified dimensions.

    While most class names remained the same due to their built-in Bootstrap properties, the were extensively modified in the CSS.
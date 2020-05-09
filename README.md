# Roger Federer's Fan Page
---

### UX
--

This web page was designed to give fans of Tennis and especially Federer a chance to keep informed about his progress throughout each season. It was built to show three key features which are popular when looking into other professional athletes. These are; Biography, Achievements and a Schedule. My project is the best to obtain this information as it has all three features listed above, it is also very easy to use and has a join scheme to allow those who see fit to recieve email updates. This makes it easier to stay up to date even if they are not on the web page. 

If one wanted to see how many titles Roger has won in each major championship in his career this can easily be done by visiting the Achievements sections of the web page. This section clearly states each major championship with the amount of titles won. This was an aspect that I wanted to make as clear as possible since being a Federer fan myself I know that the easier it is to find out this information the more I will return.

An athetes upcoming Schedule for the year is hard to find especially on the Tennis circuit as there are hundreds of tournaments played per year and not all of them can be played by Roger. With that in mind, I have dedicated a section solely to his Tennis Schedule. A simple table format was used as it clearly states all the key information needed; Tournament, Location and Date. This aspect would be something worth checking regularly or signing up to recieve these by email.

Finally, it is important to briefly outline that Federer isn't just a professional Tennis player, he is also a father and a husband. Knowing that, I decided that this may be another aspect that would be of interest to those looking to find out about his story before Tennis and what his life is like off the court.

### Wirerframe
--

https://balsamiq.cloud/sctgv77/pxr7w1k/rE985


Also can be found in a separate directory labelled Wirerframe.

I created a Wirerframe to make it easier to visualize the direction I wanted to take when building the web page. There were parts I kept the same such as, the Biography section less the title. On the other hand, there were other aspects that I changed or got rid of such as the layout of the Achievemnts section. The section looked too thin so I put each logo in the formation of the number five side of dice. This way it spreads the content over the page as opposed to one line of content.

The form section was taken out and instead a modal was attached to each Join Today button. When designing the button I felt it was much nicer to view a modal rather than moving you to the bottom of the page to fill in the form.

### Features
--

Navbar - allows the user to click on each heading in the navbar to quickly jump to each section of the page.

Modal - allows the user to see a form that is used to join the fan page. I decided to use a modal rather than a form at the bottom of the page as I felt it was more asthetically pleasing.

Join Today button - allows the user to click and immediatley fill out a form to join the fan page. This button is found at the top and bottom of the page.

Dropdown arrows - allows the user to see each Major Championship logo and use the dropdown to see the wins. This was used to keep information hidden until directly requested.

Social links - allows the user to click on each icon in the footer to jump straight to Roger's social media sites. These were designed to open in a new tab to stop the user having to use the previous page button in the browser to return to the web page.

The feature that I would look to implement would be the functionality of the Join Today buttons. I know that this would be back end development but I feel this would be a good aspect to be intoduced sooner rather than later.

### Technology
--
HTML, CSS and Bootstrap: https://getbootstrap.com/

This project used Bootstrap to simplify responsive design, table, dropdown arrows, navbar and list formats.

### Testing
--

1 - Navbar:

    * Go to section where hero image is
    * Home link not working
    * Click Biography link and takes you to section
    * Click Achievements link and takes you to section
    * Click Schedule link and takes you to section
    * Tried with fixted top navbar but color scheme didn't work. Navbar wasn't visible in each section. Due to this didn't use fixed top
    * Fixed navbar color by adding background color using rgba to alter transparency, fixed to top of page when scrolling
    * Home link working now I have added the relevant id to the div holding container-fluid
    * All links work from each page to all pages
    
2 - Join Today buttons:

    * Hover over to see color change from white to black
    * Click to view modal form

3 - Modal:

    * Click join button to view modal
    * Try to submit empty form and verify that an error message about required fields appears
    * Try to submit form with an invalid email address and verify that the relevant error message appears
    * Modal not in center of page for all screen sizes
    * Added relevant media queries to modal class and solved the issue

4 - Biography images:

    * Adjusting images for all screen sizes
    * Decided to hide the bottom three images on mobile and tablets as it looked too crowded otherwise
    * Link to Roger's ATP Tour page works

5 - Achievements logos:

    * Try clicking on all links under each logo and they all take you to the relevant websites
    * Tested appearence of the logos positioning on all device sizes
    * Finished testing positioning

6 - Schedule:

    * Tried to even the table columns for mobile screen sizes but looks to crowded
    * Removed center column 'Location' as it is not essential as most Tournament names cover where they are in the world

7 - Footer:

    * Added Join Today button to footer and works the same as it does over the hero image

8 - Social links:

    * Tested all three links, they all go to each social media page for Federer

9 - Links:

    * Used links to go to relevant sites but they open on the same page as my websites
    * Added target-blank and they open on a new tab but again they open on the same new tab
    * Added target_blank and now all links open on new tabs and do not open on tabs already being used

10 - Background image:

    * Background image didn't scale very well for tablets and mobiles. Any adjustments made using media queries still didn't look good
    * Tried different size of the background image but the Biography section intruded into the hero image
    * Added alternate background image for tablets and mobiles. This image is a vertical image rather than horizontal like the desktop image is. This vertical image solved the issue with responsiveness on tablet and mobile screen sizes

### Deployment
--

Used GitHub Pages to deploy my project. The development and deployed versions both look the same and function the same without issues.

### Media
--

#### Below are the image names in my project and the links for each of them

bio-main - https://www.pinterest.co.uk/pin/643662971721065053/

trophy - https://www.pinterest.co.uk/pin/772015561111616928/

family - https://www.pinterest.co.uk/pin/791718809476765836/

french - https://www.pinterest.co.uk/pin/657666351815393886/

hero - https://www.tennis365.com/kevin-palmer/tennis365s-top-10-countdown-of-the-greatest-tennis-players-no-1-roger-federer/

a-open - https://i.pinimg.com/236x/5c/b6/8d/5cb68dae10b850f708153c5a3563b067.jpg

f-open - https://i.pinimg.com/236x/4b/60/01/4b60018622705620c2088048356a46ea.jpg

wimbledon - https://i.pinimg.com/236x/7e/85/f1/7e85f1d626613546ccff5d3240d31966.jpg

us-open - https://i.pinimg.com/236x/33/cc/98/33cc989ff7c370dfbf1159a23d05ad4c.jpg

tall - https://www.pinterest.co.uk/pin/629800329123453009/

atp - https://www.pinterest.co.uk/pin/162692605273993094/

### Acknowledgements
--

 The inspiration to design a project like this comes from my love for Tennis and admiration for Roger Federer. Growing up watching him play Tennis and seeing that there aren't any purpose built fan pages for Federer. The closest thing to one is Federer's personal website. I wanted to fill a gap that could be filled.
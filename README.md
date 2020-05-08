<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

Roger Federer's Fan Page
---

UX
--

This web page was designed to give fans of Tennis and especially Federer a chance to keep informed about his progress throughout each season. It was built to show three key features which are popular when looking into other professional athletes. These are; Biography, Achievements and a Schedule. My project is the best to obtain this information as it has all three features listed above, it is also very easy to use and has a join scheme to allow those who see fit to recieve email updates. This makes it easier to stay up to date even if they are not on the web page. 

If one wanted to see how many titles Roger has one in each major championship in his career this can easily be done by visiting the Achievements sections of the web page. This section clearly states each major championship with a handy dropdown arrow which outline how many he has won and the years in which they were won. This was an aspect that I wanted to make as clear as possible since being a Federer fan myself I know that the easier it is to find out this information the more I will return.

An athetes upcoming Schedule for the year is hard to find especially on the Tennis circuit as there are hundreds of tournaments played per year and not all of them can be played by Roger. With that in mind, I have dedicated a section solely to his Tennis Schedule. A simple table format was used as it clearly states all the key information needed; Tournament, Location and Date. This aspect would be something worth checking regularly or signing up to recieve these by email.

Finally, it is important to briefly outline that Federer isn't just a professional Tennis player, he is also a father and a husband. Knowing that, I decided that this may be another aspect that would be of interest to those looking to find out about his story before Tennis and what his life is like off the court.

Wirerframe
--

https://balsamiq.cloud/sctgv77/pxr7w1k/rE985

Also can be found in a separate directory labelled Wirerframe.

I created a Wirerframe to make it easier to visualize the direction I wanted to take when building the web page. There were parts I kept the same such as the Biography section less the title. On the other hand, there were other aspects that I changed or got rid of such as the layout of the Achievemnts section.The section looked too thin so I put each logo in the formation of the number five side of dice. This way it spreads the content over the page as opposed to one line of content.

The form section was taken out and instead a modal was attached to each Join Today button. When designing the button I felt it was much nicer to view a modal rather than moving you to the bottom of the page to fill in the form.

Features
--

Navbar - allows the user to click on each heading in the navbar to quickly jump to each section of the page.

Join Today button - allows the user to click and immediatley fill out a form to join the fan page. This button is found at the top and bottom of the page.

Dropdown arrows - allows the user to see each Major Championship logo and use the dropdown to see the wins. This was used to keep information hidden until directly requested.

Social links - allows the user to click on each icon in the footer to jump straight to Roger's social media sites. These were designed to open in a new tab to stop the user having to use the previous page button in the browser to return to the web page.

The feature that I would look to implement would be the functionality of the Join Today buttons. I know that this would be back end development but I feel this would be a good aspect to be intoduced sooner rather than later.

Technology
--

Bootstrap: https://getbootstrap.com/

This project used Bootstrap to simplify responsive design, table, dropdown arrows, navbar and list formats.

Testing
--

1 - Navbar:

    i.Go to section where hero image is
    ii.Click Biography link and takes you to section
    iii.Click Achievements link and takes you to section
    iv.Click Schedule link and takes you to section
    v.Tried with fixted top navbar but color scheme didn't work. Navbar wasn't visible in each section. Due to this didn't use fixed top.
    
2 - Join Today buttons:

    i.Hover over to see color change from white to black.
    ii.Click to view modal form.
    iii.
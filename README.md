# My First Portfolio

This assignment entails the creation of a primitive portfolio webpage using HTML, CSS, and other functionalities such as **media queries, pseudo classes, pseudo elements, CSS variables, and flexbox** to produce a reactive front-end interface. My project consists of a *nav bar, a hero banner, an "about me" section, a partition for projects that will be updated over time, and a contact information pane*.

## Deployed Project Link

https://austinjoo97.github.io/my-first-portfolio-gwuhw2/


## Nav Bar

The nav bar is a very simple block that has 2 parts; my name and a section with links that will direct a user to various parts of the page. The color scheme of the nav bar (and a majority of the webpage) are a neon pink and cyan as they are both highly visible and reflect my energetic personality. 

The nav bar itself is a simple unordered list displayed using the *inline-block* property but, using media queries, will shift to become a dropdown menu with the corresponding list elements as options. Clicking a list item will cause a *smooth scroll* down to the corresponding section of the webpage and allows for easy access to any section upon initial loading.

Addtionally, *pseudo classes* were utilized with regards to the nav bar list as hovering and/or clicking on each item will cause a change in color of the interacted item as well as causing a small increase in *font-weight*.

**Note**: As of 3:50pm on 2/26/21, the dropdown menu items cannot actually be selected to cause the page to scroll to the corresponding elements as, after research, it was found that JS functionality was required. To keep pace with the course, I have no implemented them using *onclick* functionality.

## Hero Banner

As I did not have an image of myself to upload for this section, I opted to use a piece of art from my favorite artist; Takashi Murakami. As with all other images implemented on this webpage, I used the CSS *background-image* property to render the visuals, thus there was no alt tag used. Additionally, a *h4* tag was utilized to provide credit to the artist.

## Main Content

The three sub-sections embodied by this section were divided into 2 parts; a title card and a body. Each title card is a div component with text that was sized for visibility and following the conventional color scheme of this page. The body serves as the information that pertains to the heading of the section itself.

### About Me

This section consists of information about myself, both personal and professional, as well as technologies that I have experiencing using in the development of full-stack software. It has relevant info regarding who I am as a person and employable professional as well as info about my hobbies and ways I bide my time outside of work. In this section, I have gained experience utilizing *pseudo elements* to add small graphics before certain sections as well as how to apply CSS properties to them to make a page more captivating.

Additionally, the CSS *overflow* property was utilized to the prevent the text body of this section from spilling into other portions of this webpage. As a result, upon resize the screen, the text will shift to becoming a contained element that has scroll functionality which allows the page to render in a clean way with no intrusive elements.

### My Projects

This section serves as a rudimentary showcase of projects that will be completed during my studies as well as early in my career. Currently only holding six projects, each partition has linked via *anchor* tags to lead the user to an external application in a new window. Additionally, *pseudo classes* were also utilized here to cause a glow effect upon hovering over any particular project. 

### Contact Me

This is a simple section with three methods in which users can contact me or view my work; a link to my github, my personal number, as well as my email. At full screen, the list of items will be displayed as an *inline* set of information but upon resizing the screen, the margins of the partition as well as other properties will shift; most notably, the list will change from being *inline* to *block* display. Additionally, *pseudo elements* identical to those implmeneted in the "about me" section were also used here.

## Other

The overarching color scheme utilized throughout this page were implmeneted using CSS variables for ease of recycling each color. Additionally, the colors will reverse upon changing the size of the interface, a feat achieved using *CSS flexbox properties*.

## Project Demo



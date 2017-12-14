# A Portfolio Website

##### Using CSS and SASS to build a template

#### By Cheryl Frankenfield, 12/8/17

## Description

_This website is a portfolio template using CSS and SASS elements with a focus on trying out animations. I will be implementing a template design from yesterday with three media breakpoints (desktop, table and mobile). This particular plan is to implement the circle animated navigation into a sidebar and see how that changes this design, which is minimalistic with a focus on showcasing a designer's work or portfolio within this site._

## Setup/Installation Requirements

* Navigate to your terminal.
* Perform Git clone command on the repo [here.](https://github.com/CherylFrankenfield/SASS-project.git)
* Perform Git atom . command to open all files in repo.
* View index.html in browser.
* No other setup or install necessary.

## Specs

_The site includes 4 sections, including: Navigation, Header, Footer and Main._
* _Example: Header contains Logo and 4 links for: Project Gallery, Experience/Resume, Bio/Mission Statement and Contact._

_The Footer section contains a sitemap, an anchor to the page and potentially repeats some of the Header links or Social Links._
* _Example: Footer's Sitemap contains more quick links to the rest of the portfolio._

_The Main section contains an animated navigation element, which when clicked, opens a modal of content for that section._
* _Example: Footer's Sitemap contains more quick links to the rest of the portfolio._

_The Navigation section contains an animated navigation element, which when clicked, opens a modal of content for that section._
* _Example: Navigation element links to 4 sections: Project Gallery, Experience/Resume, Bio/Mission Statement and Contact._

## SASS Use Cases

| Term                | Description                                                                         | Implementation  |
| --------------------|:-----------------------------------------------------------------------------------:|----------------:|
| For Loop - Grid | We did not use a framework so we used SASS and a for loop function to create a 12-col grid. | I will use the grid on the design more today as the design yesterday ended up taking 12 full columns.
| Nesting | We used nested styles when creating modals. | We nested a modal class for sibling elements inside the parent modal that would scroll vs. a header and image that did not scroll.
| Variables | We have a variable for size for our columns. | Use this variable for styling and referring to header and footer.
| Partials | We tried using the 7-1 theory with partials to organize our styles. | We used a modules partial inside each partial folder (abstracts, base, components, layout, pages) to link/import individual components within. That cut down on code and any ordering conflicts in our master.scss file by just importing the modules.
| @import | See description above. | We used this organization system to import just modules in our master.scss file and within individual folders, for example, abstracts -- and import variables, functions, and mixins to the module file inside.
| Mixins | We have a few mixins to group repeatable styles together to reuse. | We used a clearfix mixin for floats and a rounded borders mixin.
| Interpolation | #{} syntax or variable substitution. | We used this to concatenate strings when creating columns in our grid function. |

## Two-Day Project Thoughts and Feedback section

The two-day project this week allowed me to tap into the very-comfortable project management and creative side of my wheelhouse. I enjoyed sketching out template ideas and started to see visually, how and why modular design is so powerful. SASS seemed a bit confusing on Monday morning, but the exercise with creating a color palette/style guide was a fantastic kickstart to see how SASS functions can be used to create a grid system and color variables -- that tangible practice really helped with my learning this week. Another positive for Day 1 is that I enjoyed having freedom to explore SASS videos, tutorials, etc. We were really interested in keyframes and styling/manipulating types of animation effects. A suggestion for Day 1 is we seemed to have some extra time in the afternoon after wrapping up wireframes that most people did not start coding components but maybe we should have to have more time to build out a more complete site.

## Today's Approach

Today, I'll make use of our column structure more with a sidebar and how that implements into different media queries. I'd also like to create a series of variables for a color palette and build that out as well as style components like typography, icons, etc. I'm going to try and implement a %placeholder and see if I can experiment with that.

## Known Bugs

_Currently working on fixing media queries._

## Support and contact details

_If you have any issues, questions, ideas or concerns, please contact me._

## Technologies Used

* HTML
* CSS
* SASS

### License

*This is open source so feel free to grab and use.*

Copyright (c) 2017 **_Cheryl Frankenfield_**

# PortfolioWebsite

## Description

We were tasked with creating a portfolio website from scratch. This portfolio is pretty basic, as we were mainly tasked with creating the framework and usability of one to add portfolio examples to as the course progresses.

Portfolios are useful for employers and potential employees. Employers are able to sample the programmer's work and see if their style of design is the best fit for what they are looking for. They can also see what sort of background the programmer might have that would perhaps make them even more qualified for the position or project. For programmers, it's good to have a portfolio both to show employers what they can do, but also to keep aware of their own growth and how they can continue to improve and learn.

The portfolio website from scratch was a good opportunity to test out some of the things we have learned in a practical format, and see how they work together. It was very difficult to understand sometimes! It's easy to overlap values and CSS and not even realize that it happened. It was good practice.

[Deployed Website](https://ashleyaggie.github.io/PortfolioWebsite/)

![Top picture of website](./assets/images/websiteTop.png)

![Middle picture of website](./assets/images/websiteMid.png)

![Second middle picture of website](./assets/images/websiteMid2.png)

![Bottom picture of website](./assets/images/websiteBottom.png)

## Changes Made

GIVEN I need to sample a potential employee's previous work

WHEN I load their portfolio

THEN I am presented with the developer's name, a recent photo, and links to sections about them, their work, and how to contact them

    *Included full name in Header and in "home" section of body. Photo is also in "home" section. Links to about me, previous work, and contact details, are in the header.

WHEN I click one of the links in the navigation

THEN the UI scrolls to the corresponding section

    *Achieved with the use of id's.

WHEN I click on the link to the section about their work

THEN the UI scrolls to a section with titled images of the developer's applications

    *Work links to section with id Work.

WHEN I am presented with the developer's first application

THEN that application's image should be larger in size than the others

    *Achieved using block display and using classes to specify widths of each section (in this case, spans)

WHEN I click on the images of the applications

THEN I am taken to that deployed application

    *Each image has an a tag attached with a link, including the placeholders with a google link as a placeholder.

WHEN I resize the page or view the site on various screens and devices

THEN I am presented with a responsive layout that adapts to my viewport

    *Used media queries to edit formatting to change at two breakpoints for best use of the layout and screen size.


## Credits

Website code was written by myself (Ashley Wright)

Assignment is part of the SMU Coding Boot Camp

## License

Copyright (c) 2021 Ashley Wright

Covered by the [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)
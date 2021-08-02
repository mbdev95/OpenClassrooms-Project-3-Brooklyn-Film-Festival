# Brooklyn Film Festival Advertising Page Devolpment Explanation

#### To See Project 3 online click the link below:
https://mbdev95.github.io/OpenClassrooms-Project-3-Brooklyn-Film-Festival/

## Introduction
In project 3 of my OpenClassrooms course I had to create a web page advertising a film festival in Brooklyn, NY.  The main goal of the project was to use bootstrap to establish the layout and main components (ie movie cards, buttons, ect) for the web page.  Also, more advanced css (i.e. transitions and transforms) were used to create a well designed and effective advertising page.  Furthermore, I used bootstrap and custom media queries to ensure all parts of the page were responsive in all view port sizes. Below I will go over the main parts of the web page, and discuss how I used bootstrap, css3 and responsive web design to successfully create a well designed and convincing film festival web page.

## Header
!['header'](https://github.com/mbdev95/OpenClassrooms-Project-3-Brooklyn-Film-Festival/blob/master/img/Project-3-README-Images/Header.PNG)

The header in the image above was created using bootstrap components such a nav element and a jumbotron in conjunction with custom css.  

!['responsive header'](https://github.com/mbdev95/OpenClassrooms-Project-3-Brooklyn-Film-Festival/blob/master/img/Project-3-README-Images/Responsive-Header.PNG)

The header was made responsive in all viewport widths by using the bootstrap classes of navbar-expand-lg and navbar-collapse to allow bootstrap's stylesheet to expand the navbar when the viewport width is greater then bootstrap's large break-point.

## Movie Card Component
!['movie cards'](https://github.com/mbdev95/OpenClassrooms-Project-3-Brooklyn-Film-Festival/blob/master/img/Project-3-README-Images/Movie-Cards-Component.PNG)

Each movie was given a basic description in an organized way using bootstrap's card component. The cards were placed in responsive columns using the bootstrap grid with the columns going from 1 column in small viewports, to 2 columns in medium viewports, and finally 3 columns in bootstrap's extra-large viewport width.

## 3D Movie Image Cubes
!['3D movie image cubes'](https://github.com/mbdev95/OpenClassrooms-Project-3-Brooklyn-Film-Festival/blob/master/img/Project-3-README-Images/3D-Movie-Image-Cubes.PNG)

I added a more advanced css cube feature using a combination of css transitions, transforms, and translate 3d. Every time a user hovers over the movie image cube the css I programmed will cause the cube to spin in a counter-clockwise direction, revealing four movie images throughout the spin.  Upon the user hovering off the cube the cube spins in the reverse direction until the original movie image appears flat on the screen.

## Detailed Movie Explanation 
!['detailed movie section'](https://github.com/mbdev95/OpenClassrooms-Project-3-Brooklyn-Film-Festival/blob/master/img/Project-3-README-Images/Detailed-Movie-Section.PNG)

A section pertaining to more detailed information about each film is now presented including an embedded youtube video of the trailer of the film. The layout and responsiveness is achieved through bootstrap's grid and flex classes. I used the bootstrap feature of scrollspy to highlight each navigation section as the user scrolls down the page to visually alert the user to where they are on the web page.

## Form/Schedule Sections
!['form/schedule'](https://github.com/mbdev95/OpenClassrooms-Project-3-Brooklyn-Film-Festival/blob/master/img/Project-3-README-Images/Forms-Schedule.PNG)

I included a registration and film schedule form using bootstrap form and list components.  Both form and the film schedule sections were made responsive using the bootstrap grid and flex classes.

The next couple of sections before the footer include text pertaining to news updates and sponsors, as well as a map and about section.  These sections' layout and responsiveness is established using the bootstrap grid and also bootstrap's flex classes.

## Footer
!['responsive footer'](https://github.com/mbdev95/OpenClassrooms-Project-3-Brooklyn-Film-Festival/blob/master/img/Project-3-README-Images/Responive-Footer.PNG)

The bottom footer contains copyright information and social media links.  The footer layout is established using bootstrap's grid, bootstrap's flex classes and custom media queries.

## Conclusion
In conclusion, this project allowed me to further understand css, bootstrap and html in a more complex and indepth way. Additionally, I learned the importance of responsive design, and how to do responsive design in an efficient way using bootstrap and also custom media queries where required.

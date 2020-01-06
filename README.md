# Alex Szolkowski Portfolio

User-Centric Frontend Development - Milestone Project 1

This website is my portfolio for potential clients, employers and recruiters. The portfolio includes some information about myself and also displays my skills and recent work.
 
## UX
 
### User Stories

As a client I want to be able to see what I can expect through previous work from other clients.

As an employer I expect to see owners skill set and previous/current work.

### Strategy

The focus and goal for this website design is to showcase my recent work in a way that is easy to understand - including what I offer and and what they can expect from my work. I have created the landing page with particles.js to make make the design more interesting and engaging for users.

### Scope

For potential clients and employers, I have included some information on my background and skills. I want them to be able to  get to know a little about myself, what I do, and what techniques I use to build projects. I also want people that are interested in hiring myself as a developer to see a showcase of skills and projects I have worked on and a contact form if the want to get in touch.

### Structure

From the landing page people can promptly access my "work section" and "contact" through the two buttons below the heading. Also below to the bottom right of the screen is my full name and icons linking to both my Github page and Linked in profile. Further down the page is a small introduction about myself that then leads onto my skill-set which is displayed though icons of different languages. The portfolio section gives a top picture to every project card as well as a brief description on what the project is, technologies nad languages used to build it.



### Surface

The theme for this website has a dark style to it as well as a depth effect from the particle animation from the background. This website works with animations on scroll in attempt to make the user experience smoother and more engaging.  

## Technologies

1. HTML 5
2. CSS 3
3. JS - (Particles.js libray)
4. BootStrap 4.3.1





## Features



This site features a landing page which loads a lightweight javascrpt library called Particles.js built by Vincent ... this library creates an animated particles effect which can be easily modified through the .Json file and hosted through a CDN.

Another feauture I have added is the Animate-On-Scoll library. It allows you to easliy add attributes to any section to create a range of animated effects on scroll.

The "Skills" section feautures icons from DevIcons along with A-O-S library to display the different technoligies I use. 

The "Porfolio" section uses a card deck with images on top to display most recent projects/work with a project discription. 

The "My Services" sections gives a list of information on what differnt services I offer. Below is the contact form where users can submit their information and send me a message if they want to reach out.


### Features Left to Implement
- I want to implement a email database to the contact form
- Add finished projects that are deployed live with real source code

## Technologies Used

- HTML 5

- CSS 3
    - This project uses the framework **Bootstrap 4.3.1** - Used for quick implementation of CSS classes and styles

- JAVASCTIPT
    - The project uses **Particles.JS** to create a linked falling particle effect feautured on the landing page (https://github.com/VincentGarreau/particles.js/)

- A-O-S Animate on Scroll library
    - This project uses A-O-S for smooth scrolling effect on animation


## Testing


The Goal of the user stories was achieved through providing clients and employers with information on myself, my skill set, what I offer and how they can contact me by email. The landing page contains my title as a software developer with two buttons leading to  the "portfolio" section and  the "contact" section for quick view. The landing page also has my full name to the bottom right, and below, two icons href linked to my personal Github account and LinkedIn profile. My work is showcased in the "portfolio" section, which allows them to see my most recent projects and the technoligies used in development. The project cards give a brief description on what the project is or who for, with the functionality of two buttons ("View Live" & "Source") that leads them to either to the deployed project or it's GitHub reposistory in a new tab. 


To test the layout and responsivness of this design, it was first used chrome developer tools and then conducted tests throug a variety of web browsers and devices such as: 

1. Web Browsers 
    
    1. Google Chrome /DevTools
    2. Mozilla Firefox
    3. Safari - Background-attachment: fixed; property still needs to be changed to display fixed images correctly

2. Mobile Devices
    
    1. Iphone 4, 5, 6, 7, 8, X - Responsive bug with extra padding fixed with adding margin-left/right: 0px!imprtant; to row and container-fluid class
    2. Ipad/Pro
    3. Surface pro
    4. Samsung Galaxy S5

    
3. Desktop Resolution & Aspect Ratio
    - Different display types and aspect ratios affected the display of name and icons on the landing page. 
   
    - 1366x768	16:9
    - 1920x1080 16:9
    - 1280x800	8:5
    


4. Testing Particles.js
    1. To load this library and test this on a local machine you have to use a local server (I used live-server - installed through npm) which hot reloads for quick testing 
   
    2. Alternativly you can host the library through Vincents CDN
    
    3. Extensive testing and modifcation of the .json files to experiment with diffent effects available to suit this design. - Any bugs can be easily found in the chrome debug console in Devtools




## Deployment

I have used Github pages for the hosting and deployment of this website. Each time the master branch has a new commit, it will automatically updates to the live page.

Through the development process, the particles.js library was hosted through my local machine and now is hosted though a CDN on live deployment. 
If you want to run the whole page locally you will have to replace the Bootstap 4 CDN, AOS-Library CDN, and Particles.js with their local respositories 



## Credits
 

### Content
- The content in the about section, skills, cards & contact me where all written by myself.
- The Js library Particles.js was written by Vincent Garreau and cloned from https://github.com/VincentGarreau/particles.js



### Media
- The photos used on the landing and skills section were obtained from https://unsplash.com/ 
    Credit to John Towner - Red highlands

- The Photos for the project cards are only used for example purposes and were obtained through screenshots of relative sites.

- Icons in the "My Services" section were obtained through https://www.flaticon.com/packs/

### Acknowledgements

- The Js library Particles.js was created by Vincent Garreau and cloned from https://github.com/VincentGarreau/particles.js
- A-O-S Animate on Scroll was created by https://github.com/michalsnik/aos

# CamRaff - Milestone Project 1

![displays](assets/images/displays.png)

Here is a link to the deployed site: [Barca Tynemouth](https://camraff.github.io/milestone-project-1/ "Barca Tynemouth")

For my first Milstone Project on my course through Code Institute via UCP (University Centre Peterborough), I thought the best thing to do was to produce something I would be familiar with. I have worked at Barca in Tynemouth for around 6/7 years on and off. I had a little break where I tried my hand at Recruitment, however, this field of work wasn't for me. During my time in Recruitment I worked sourcing candidates adept in Salesforce, before moving to a different company where I worked sourcing talented individuals in the Games Industry. This is where I built more of a passion for IT myself and decided to try my hand at Developing. I found a bit of myself here and though I had no previous experience at all, I begun to enjoy working in this field and decided I wanted to make this into a career. So here is my first project. I have produced this project with only 2 months of experience overall in coding. This is just the beginning!

## Contents

- [User Experience](#user-experience-ux)
    
    - [User Stories](#user-stories)

- [Design](#design-and-development)
    
    - [Wireframes](#wireframes)

        - [Mobile](#mobile)
        
        - [Tablet](#tablet)

        - [Desktop](#desktop)

    - [Color Scheme](#color-scheme)

    - [Typography](#typography)

        - [Merriweather](#merriweather)

        - [Anton](#anton)
    
    - [Images](#images)

    - [Features](#features)

    - [Development](#development)

        - [Libraries, Websites and Programs](#libraries-websites-and-programs)

- [Deployment and Local Development](#deployment-and-local-development)

    - [Deployment](#deployment)

    - [Local Development](#local-development)

        - [Fork](#fork)

        - [Clone](#clone)

- [Testing](#testing)

    - [Automated](#automated)

- [Credits](#credits)

    - [Outside Code](#outside-code)

    - [Images](#images-1)

    - [Core Content](#core-content)

    - [Acknowledgements](#acknowledgements)
---

## User Experience (UX)

### User Stories

#### First Time Visitors

- I want to understand what the situation with Barca Tynemouth is, like opening times and location.
- I want to get a feel for the vibe of the venue and menu.
- I am interested in purchasing merchandise if possible.
- I want to be able to access and navigate the website easily regardless of which device I choose to use.

#### Returning Visitors

- I want to see if there is any new events or merchandise available on the site.

#### Frequent Visitors

- I want the option to reach out via socials to get updates on events and merchandise.

---

## Design and Development

### Wireframes

The below Wireframes were created with responsive design in mind. The main focus was to produce a view on various screensizes which would maintain an overall aesthetic and appeal.

#### Mobile

This is the initial mock-up for all 3 pages on a mobile device.

![mobile-wireframe](assets/images/wireframes/mobile-wireframe.png/)

#### Tablet

This is an initial mock-up for the view of the merch page on a tablet. My vision for a tablet view would be to have the Home and Menu page look the same as on mobile, so with the only real changes being to the Merch page, I created a mock-up for that.

![tablet-wireframe](assets/images/wireframes/tablet-wireframe.png/)

#### Desktop

Below are the mock-ups for each individual page when viewed on a desktop/laptop screen. 

- ##### Home page

![desktop-home-wireframe](assets/images/wireframes/desktop-home-wireframe.png/)

- ##### Merch page

![desktop-merch-wireframe](assets/images/wireframes/desktop-merch-wireframe.png/)

- ##### Menu page

![desktop-menu-wireframe](assets/images/wireframes/desktop-menu-fireframe.png/)

### Color Scheme

For the color scheme of the website, I decided to go with the original color palette from the logo you can see below.

![barca-logo](assets/images/barca-logo.jpg/)

I chose the green color for the body text, as well as the navigation menu, and decided to make it so that when you hover over the navigation links, they change to red. This is in keeping with the original logo with it being green to begin with, and then red at the end. I decided to also maintain the black backround, and this allows the text to stand out. 

For the green color, I went with the hexidecimal color `#a5b867`, as this was the closest I could get to the original green in the logo.

For the red color, I went with the hexidecimal color `#d96d4c`, as I feel like this is the best match to the original logo.

I feel that these colors work well together as there is good contrast between the two, and they also stand out really well against a black background.

### Typography

After spending some time looking over some fonts, I decided to go with [Merriweather](https://fonts.google.com/specimen/Merriweather/) for the body of the site, and [Anton](https://fonts.google.com/specimen/Anton/) for the header and navigation text. Both fonts were acquired from Google Fonts.

- #### Merriweather

I chose Merriweather for the body text font as I think it has a very friendly and inviting vibe, and I think with the color being a shade of green, some fonts wouldn't look quite as nice in this color, however Merriweather does. 

![merriweather](assets/images/merriweather-example.png/)

- #### Anton

I chose Anton for the header and navigation text as I felt that this font had a similar kind of sharpness too it as can be seen in the image above where I chose the color scheme from.

![anton](assets/images/anton-example.png/)

### Images

The image used on the home page was created by John Christensen, a staff member at Barca Tynemouth. Each of the merchandise images were taken by Beth Simpson, also a staff member at Barca Tynemouth.

For the social media links in the footer I used Font Awesome, with a link acquired from Code Institute.

All of the images found on the menu page were taken by myself using my iPhone. 

### Features

The project I created consists of 3 pages: a Home page, a Merchandise page, and a Menu page. The idea was to have each page responsive and work across a variety of devices.

Several features are seen on all 3 pages, those being the main logo, the navigation tools and the social media links in the footer. I wanted to keep these features the same across all pages as it maintains the overall accessibility of the site, meaning when someone wants to access a certain page, they know exactly where to visit to get there! 

My reasons for having each page display as they are were as follows:

- #### Home Page

This page has a very straight forward layout, with an image of the front of the bar created by one of the bar staff, as well as a brief description, location information and links to social platforms. I felt that this was a great example of a home page, as it gives you everything you may need at a first glance of the website. The unique aspect of this page is the location information, utilizing an iframe to put the map on the page. The overall layout for this page should stay the same on smaller devices, with one change being the main image. For smaller screens, to give it a better user experience, I changed the image so that it shows the BARCA logo instead of the original bar image as I felt the bar image was just a bit too big to be displayed properly on a smaller screen.

- #### Menu Page

I wanted this page to look a bit like a menu from an actual bar or restaurant, with images of the thing you would purchase along with a description and pricing. I kept this one relatively simple again and made it so that the image and description alternated sides as you went down the products on the page (image left with its description right, then image right with its description left and so on). The unique part of this page is the layout and how it differs from the other two. The overall layout for this page should stay the same on smaller devices.

- #### Merch Page

For this page I had the idea of having the merchandise description and pricing appear when you hovered over the image with a mouse. I achieved this, and I think it looks good on the page. As it would be a lot harder to achieve this on smaller devices like tablets and smartphones, I decided to make it so that the description of the item fell below each image, and each image just fell in a linear fashion. 


### Development

For this project, as per the requirements, the languages I used to create this website were HTML and CSS. 

#### Libraries, Websites and Programs 

- I used [VSCode](https://code.visualstudio.com) as my IDE of choice. 
- I used [Git](https://git-scm.com/) for version control.
- I used [GitHub](https://github.com/) to commit and store all files relating to the project.
- I used [Balsamiq](https://balsamiq.com/) to produce the above wireframes.
- I used [Google Fonts](https://fonts.google.com/) to evaluate and decide which fonts to use throughout the website.
- I used [Font Awesome](https://fontawesome.com/) to acquire the icons used for the socials links.
- I used [Google Dev Tools](https://developer.chrome.com/docs/) as a means of testing the website throughout its production.

---

## Deployment and Local Development

### Deployment

This site is available for deployment via GitHub Pages. In order to deploy this site, you must:

1. Log in to Github (or sign up).
2. Go to the repository for this project - <https://github.com/CamRaff/milestone-project-1>
3. Click the "Settings" button above the project name.
4. Select "Pages" from the navigation bar at the left of the screen.
5. From the source dropdown, select "Deploy from a branch", and then "main".
6. The site is now deployed. This may take a few moments, but upon completion you should be able to acquire the link and visit the site via the top of GitHub Pages.

### Local Development

#### Fork

In order to Fork this repository, you must:

1. Log in to GitHub (or sign up).
2. Go to the repository for this project - <https://github.com/CamRaff/milestone-project-1>
3. Click the "Fork" button on the right, on the same line as the project name.

#### Clone

In order to clone this repository, you must:

1. Log in to GitHub (or sign up).
2. Go to the repository for this project - <https://github.com/CamRaff/milestone-project-1>
3. Click on the "Code" button above the number of commits. 
4. Select whether you would like to clone with HTTPS, SSH or GitHub CLI, then copy the given link.
5. Open the terminal in your desired IDE, then select your desired location for the cloned directory.
6. Type 'git clone' into the terminal, paste the link you copied in step 4 and press enter. 

---

## Testing

### Automated

#### W3C

In order to conduct testing on both the HTML and CSS within my site, I used the [W3C Validator](https://validator.w3.org/). The results for both the HTML and CSS testing can be seen below.

- HTML 

    - Home initial test
![w3c-home](assets/images/testing/w3c-html/w3c-home.png)

    - Menu initial test
![w3c-menu](assets/images/testing/w3c-html/w3c-menu.png)

    - Merch initial test
![w3c-merch](assets/images/testing/w3c-html/w3c-merch.png)

Following the tests, I went through the HTML for all of the pages and fixed the errors. The results were as follows:

- Home 

    I went into the home HTML and changed some of the sections to divs which worked well, rectified the warnings and did not impact the responsiveness of the page. I removed the trailing "/" from the stylesheet, rectifying that and cleaning the code. Fixing the error was a little more work to figure out but I edited the style of the iframe which fixed the error and produced the following result when tested:

![w3c-home-final](assets/images/testing/w3c-html/w3c-home-final.png) 

## Credits

### Outside Code

- I couldn't quite figure out how to get the images on the menu page to show the description and pricing when hovering, so I did a quick google and found a good bit of code on a website called [Stack Overflow](https://stackoverflow.com/questions/14263594/how-to-show-text-on-image-when-hovering). I copied this and edited it to make it work within my site.

### Images

- All of the images (except the social media icons, which are from [Font Awesome](https://fontawesome.com)) used in this project were either taken or developed by staff members at Barca. 

### Core Content

- All of the content, including drinks descriptions, was written by myself.

### Acknowledgements 

I would like to say a special thank you to several individuals:

- Ronan McClelland - my Code Institute mentor, for their helpful and kind manner in which they conduct themselves. They have made attempting a coding project like this a lot more pleasant with their knowledge and understanding.

- Mark Nevison - one of the students in my cohort. They were always extremely helpful whenever I asked, no matter how menial my issue may have been. 

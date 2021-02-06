![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

<h1 align="center">Include:Me</h1>

**This is my 3rd Milestone project covering: Data-Centric Development - Code Institute**

# Welcome to Include:Me Book Review

## Contents
- [Introduction](#joe-roberts-Include:Me--Thirds-milestone-project)
- [Demo](#demo)
- [UX](#ux)
    * [Strategy](#strategy)
    * [Scope](#scope)
    * [Structure](#structure)
    * [Skeleton](#skeleton)
    * [Surface](#surface)
- [Features](#features)
    * [Existing Features](#existing-features)
    * [Features Left to Implement](#features-left-to-implement)
- [Technologies Used](#technologies-used")
- [Testing](#testing)
- [Deployment](#deployment)
    * [Deployment on GitHub Pages](#deployment-on-github-pages)
    * [Cloning the Repository](#cloning-the-repository)
- [Credits](#credits)
    * [Content](#content)
    * [Media](#media)
    * [Acknowledgments](#acknowledgements)


## Introduction - Intro
Welcome to Include:me. This is a web application that enables the user to view and review books that they would personally recommend to other book readers
The application is customisable where the user can add book titles to the platform, search for titles and ideally be alerted to new titles.
The purpose of the Include:me is to raise the awareness of the users, authors and publishers interest in their particular genres.


## Conclusion

This is a book review and recommendation site.

## The learning outcomes
To use JavaScript and jQuery, both to manipulate the DOM and to.......cusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi

## Future Development - Features
Tech Stack: MySQL - MVC application
Make the site secure - by using Log in - Admin/User securtity development with Werzeug definitions.

## Current Issues

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus felis leo, egestas sit amet libero vel, porttitor varius ex.  **resolved**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus felis leo, egestas sit amet libero vel, porttitor varius ex.  **resolved**

## Demo

<h2 align="center"><img src="https://github.com/Benjamin144/include:me/blob/master/tab-land.PNG"></h2>

## User Experience (UX) - Intro

When I first looked at the idea of creating this type of idea, I immediately thought on how the CRUD functionality would play a core role with the users interactivity, because the user would be spending alot of their timme
looking at the available content, then adding their own recommendations, editing their own profiles and searching for new content. Keeping in mind that the best way to go about building the site would be to use
MonGoDB to help manage the data at the back end and have flask and python to deploy the site to Heroku. My initial thoughts were how I would be able to create front end functionality representations and functionality to work alongside
the back end. The best way to do this for me was to use a light framweork library in Startup Bootstrap along side Flask, and use HTML to hold it together. I was also very wary how I would overcome how I could get somthing like 
css grid vs flexbox vs bootstraps to behave in a way that would aid the structre of the site as I would need a 7 page site to make my idea work. Before I decided on what the the site would look like and how it would function, 
I ask my family members who are avid bookworms! to imagine what it would be like to surf a website to search for new book titles. Some of the answers helped me form an I dea of what I would need to add to the website. In reality though I was 
unsure wether or not I could fully complete the task or would it become a minimal viable product. So my overall aspiration was to keep the site as visually easy to use as possible and to add features that regular users on similar websites 
are familiar with in terms of navigating their way around the site


 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.
In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
******** As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file 
in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.*********

### Strategy

TSome questions you might ask about your content, your features, and your product is, "is the content culturally appropriate?" The product is intended for open learning and as it is based on books their 
is a limit to who can use the site, due to the potential of adult themes being posted. It's not really a corporate site but more geared to a people you love to read what other peoples interests are.
There would be a varied community of users that could attract people to the site, I like the colours that Facebook and Linkedin and various social media sites use because those themes draw a sense of community and belonging, 
so that is something that insppired me to build this site. One of the ideas for this site is to have immediate access to the site, wether the user would become a regular user and sign up or just be more of a casual user and browser
through limited avaiable content, now because of this I wanted to make the site as interactive as possible, with search, edit and delete funtions, uploading, up voting and down voting. (This may not have been achieved by the completion of the deadline for this project. But is is an aspiration)
So to conclude it is something that would be very useful those looking to manage their ideal ortfolio of books.

### Scope

At this point understanding the process of the site would be to reduplicate the function of adding a book title, having a way of displaying and presenting the book entry in such a way as to making the process simple,
minimal and relatable. Also being able to change the recommendation and then have overall control of wether the user wants to keep or remove the recommendation - From a publishers standpoint, it would be about branding 
or how closely associated they are to other brands. I would also imagine that this type of platform content might nake the user consider other ways of purchasing the content via electronic media such as eBooks or podcasts.
To get this done I will need front end frameworks to interpret the look and feel of the site. I will use MongoDB to maintain a scalable database, as the platform evolves.
So to conclude I mulled over some user stories based on some discussions I was having with friends and family nd various research based on  generic user, a publisher and a software developer wishing to collobotrate on the site.


-   ### User stories

    -   #### First Time Visitor Goals

        1. As a Developer              ||  I want to understand the global purpose of the site and learn more about the potential interest and overall usefulness of the site.
        2. As a Publisher              ||  I would be interested to see a list of Best Sellers for Adults and children
        3. As a User                   ||  I want to be able to search for best selling books

    -   #### Returning Visitor Goals

        1. As an Developer             ||  has the flow of functionality being properly understood by the user
        2. As a Publisher              ||  What authors are frequent users of the site recommending
        3. As a User                   ||  want to check back and see what ne titles have appeared

    -   #### Frequent User Goals
        1. As a Developer              ||  look to update the site by alerting users of new include:me book recommendations, via podcasts or online classroom environments, including YouTubw, Google Meet e.t.c
        2. As a Publisher              ||  Cras vitae purus metus. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam s
        3. As a User                   ||  What what kind of book titles are available, via genre,..i.e Sci Fi, Fantasy, e.t.c

    
### Structure

When you take a first look at the site, it may have a familiar look to it because of the soft pale blue theme. I wanted to keep the navigational elements and functions consistent through various screen sizes. The correlation between 
the mobile view and the desk top view would be more of a challenge as it would not be possible to get all of the functions to work,  for example utilising the admin profile where more books can be viewed. It might be that on a mobile 
version the imges would have to be vertically aligned rather than horizontlly. 

1) Never the less the flow would start with the option of registering your first name, last name, email & password, before signing up. Once you hit the sign up
button the status changes your profile and you are given confirmation of a succesful registrtion

2)Wether you are signed in or not you can view a single book profile of a previously uploaded book title, author, and description 
and image of the book title as illustrated in diagram 4. 

In diagram 5 your status would be signed in, here the app allows you to view your portfolio of books, when you click on the by book, author or the by genre bars
these actions then navigate to diagram 7 of the wireframe illustration, before looking at diagram 7 in more detail, in diagram 5 the user can also add & include books and authors via an input text field, 
their choices will then be updated on their profile, the user can then view their list of books that are in their portfolio, edit and delete them as they wish as shown in diagram 7.
Should the user wish to add more titles, they can then use the + button icon which will navigate the user back to diagram 5

3) If you are signed in though you can hit any edit option in the nav bar to open up a new editing page where you can go back to your profie age 

4) Wether you are signed in or out of the site you are able to use the search method that opens up a new page and gives the user three searchable options, by book, authors or genres

5) Finally there is an option to add in SUPER_USER functionality that allows the user global access across the site. - (Tentative)

As part of the process I am looking to use the 5 planes to work through how the structure of this site can be organised and made as intuitive as possible. At this point the site is under development could be subject to change in appearence.

**Consistent** **Predictable** **Learnable** **Visable** **Feedback** - (Useful points from the 5 planes of success video - 'Code Institute')

### Skeleton - (Complete this post code input - for now based in wire framing)

-   ### Design - example write up
    -   #### Colour Scheme
        -   I have used the following global palette of colors for this project: --evergreen: #38855d; --text-gray: #112d60; --text-light: #686666da; --bg-color: #0e3746; --white: #fffaf2; --midnight: #104f55; --sky: linear-gradient(120deg, #a1c4fd 0%, #c2e9fb 100%);
    -   #### Typography
            I have used light font themes to add a friendly non formal appearence: "Carter_One", "Josefin", "Livvic", "Roboto".
        -   The Livvic font=family for nav links across the site & Carter_One commonly used across the site, with Josefin secondary font, which is light non invasive, 
            
    -   #### Imagery
        -   The imagery for this site is very minimal and reflects transparency and not flashy. The images of the urpis. Morbi molestie rutrum tincidunt. Ut nulla dolor, suscipit at augue eget, sodales posuere dui. convert well on all screen sizes
 
### Wireframes:
[Mobile View](https://github.com/Benjamin144/include:me/blob/master/Mobile%20View.png)
[Tablet View](https://github.com/Benjamin144/include:me/blob/master/Tablet%20View.png)
[DeskTop View](https://github.com/Benjamin144/include:me/blob/master/Desktop%20View.png)

### Surface -  (Complete this post code input - for now based in wire framing)

*** Sample write up - My site has a simple, unassuming, look and feel. And the functionality is smooth and engaging. Praesent interdum viverra augue eu aliquam

## issues, that needed further development 
- Integer sed diam felis. Nullam vitae malesuada dolor.  
- Integer sed diam felis. Nullam vitae malesuada dolor. 
- Integer sed diam felis. Nullam vitae malesuada dolor. 
- Integer sed diam felis. Nullam vitae malesuada dolor. 

<p align="right">
  <a href="joseph-roberts-include:me-app---third-milestone-project">Back to Top :arrow_heading_up:</a> 
</p>

## Features

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.......

MongoDB Driven - non relational database
???Email JS driven Subscription Service
Tec Stack: [Bootstrap] [HTML], [CSS], [Javascript], [Jquery],[Python] [Jinja], [Flask], [Mongo], [Heroku], [Matierialize] [Flash], [Werzeug], [Javascript].[Dot-notion]
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Features II

-   Responsive on all device sizes

-   Interactive elements, such as, pull down nav bars, carousel, modals, maps API and email functionality. 

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


All of the Features within the Super Arenas website  using  Javascript, Jquery CSS & HTML core, 'OWL' and 'Bootstrap' Front-end Component Libaries, GoogleMaps API, and EmailJS.

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [JS](https://en.wikipedia.org/wiki/JavaScript)
-   [JQ](https://en.wikipedia.org/wiki/jQuery)



### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Owl.Carousel 2:](https://owlcarousel2.github.io/OwlCarousel2/)
    - Touch enabled jQuery plugin that lets you create a beautiful responsive carousel slider.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Paint 3D:](https://www.microsoft.com/en-gb/p/paint-3d/9nblggh5fv99)
    - Paint 3D s a built-in creative application that comes free with Windows 10*.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

    <p align="right">
  <a href="joseph-roberts-super-arenas---second-milestone-project">Back to Top :arrow_heading_up:</a> 
</p>

## Testing - Intro

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


## Testing - Write up

## when using Gitpod 

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

I have tested my project using Chromes developer tools, and Light House
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

## Updates Since The Instructional Video

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.


-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)


## lighthouse

-   [Home pages](https://github.com/Benjamin144/include:me/blob/master/Homepage.PNG)
-   [About Pages](https://github.com/Benjamin144/include:me/blob/master/About.PNG)
-   [Map Pages](https://github.com/Benjamin144/include:me/blob/master/Map.PNG)
-   [Subsribe Pages](https://github.com/Benjamin144/include:me/blob/master/subscribe.PNG)



## Further Testing#
#Check site UX for navigational completeness - make sure links work - log links in readMe that are in development. 
#Check site UI - Ensure ease of use (does the site make sense).
#Check rating with lighthouse (screenshot results and use in readMe)
#Check responsiveness on all devices
#Check responsiveness on all web browsers
#Clear bugs - reference, the Slack community, tutors & online support, i.e console log.
#Run the code through (W3C) validators

#Testing Errors - Struggling to get past these...type of error sample below:

    **resolved by changing the order of content in the main.js file - **resolved**
    **resolved uncaught not defined type error in console for modal by moving JS to index.html file under modal because te complier was not reading the request from the js file **resolved** 
    

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the Website.

        1. Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        2. Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        3. Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
    
    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1.  Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        2.  Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        3.  Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        4.  Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        5.  Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        

    3. As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.
     

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find out more about  the organisations brand and social awareness

        1. Would like to see alot of membership engagement and available content in the for Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc atm of popular posts, blog posts, various articles, and newsfeeds
      

    2. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.


        1. The visitor can then  fill out a form on the page or are told that alternatively they can message the organisation on social media.
        2. The footer contains links to the organisations Facebook, Twitter Reddit, Google, YouTube and Pinterest page as well as the organization's email.
        3. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.
        4. The personal information section is set up to autofill 

    3. As a Returning Visitor, I want to find the links to various social media groups so that I can join and interact with others in the community.

        1. Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        2. Aliquam nisi felis, posuere sed dui et, facilisis facilisis dolor. In hac habitasse platea dictumst. Donec pellentesque massa at tristique aliquet. Vestibulum ultricies nunc at
        
-   #### Frequent User Goals

    1. As a Frequent User, I want to check to see if there are any newly added content to the site which furthers the interest of the business.

        1. The user can use search components in the navigation bar and updates to the development of the site

    2. As a Frequent User, I want to check to see if there are any new information as I now have access to an intranet site linked to Super Arenas.

        1. The user would already be comfortable with the website layout and can easily click on links for further developments of the site



### Further Testing

-   The Website was tested on Google Chrome. Internet Explorer, Firefox and Opera, the screen sizes were good and images appeared to scale well
-   The website was viewed on a variety of devices such as Desktop, Laptop, iphone6 iPhone7, iPhone 8 iPhoneX, iPad, iPad Pro and Pixel 2XL
-   A large amount of testing was done to ensure that all pages were linking correctly.'#'was used where page links were not developed to their final resolution.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.



### Known Bugs

-  When switching from mobile view to desktop or tablet, the nav bar function remains extended if user forgets to toggle the menus
    bar to close it in mobile screen sizes.????????????????????????????????????????????????????????

## Deployment - Intro

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## Deployment

The site is deployed published at https://benjamin144.github.io/include:me/ from my GitHub Pages

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Benjamin144/Europes-Favorite-Arenas)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   [https://courses.codeinstitute.net/courses] - Flask rudimentary code snippets used to initial Framework for Flask ongoing functionality

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library template used for subscribe.html page, additional styling was used by me to change appearence

-   [Stackoverflow)](https://stackoverflow.com/questions/19827605/change-bootstrap-navbar-collapse-breakpoint-without-using-less) : Change bootstrap navbar collapse breakpoint without using LESS

-   [Perishable Press](https://perishablepress.com/a-killer-collection-of-global-css-reset-styles/) : Killer Collection of CSS Resets

-   [w3schools](https://www.w3schools.com/howto/howto_css_modals.asp) : code snippets for modal function.

-   [Stackoverflow](https://stackoverflow.com/questions/3059044/google-maps-js-api-v3-simple-multiple-marker-example) : code idea and snippets for google markers and info windows functionality.

-   [Daily Tuition](https://www.youtube.com/watch?v=CrSC1ZA9j0M) : Guide to creating jQuery driven interactive nav bar menu items



### Content - Intro
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Content

-   Also credits to the Stack Overflow community for snippets 

-   

### Media - Intro
- The photos used in this site were obtained from ...
### Media

-   (https://stock.adobe.com/uk) resource images. https://stock.adobe.com/uk/images/.............. - Landing page image

### Acknowledgements - Intro

- I received inspiration for this project from X

### Acknowledgements

-   My Mentor Dick Vlaanderen for continuous helpful feedback.

-   Tutor support at Code Institute for their support.

-   The Code Institute Slack community for their ongoing support.


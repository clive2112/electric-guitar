# Electric Guitar 
 
This Electric Guitar website is a website for people who are interested in electric guitars, including a brief history, main electric guitar types and an artist gallery.
Users of this website will be able to view various electric guitar types, read some information about types of electric guitar. They can read information on guitar manufacturers.
There is an artist gallery of images with links to further information on each guitarist. This site is targeted towards people who have an interest in the electric guitar.

# **Table Of Contents**
* [User Stories](#user-stories)
    * [First Time Visitor Goals](#first-time-visitor-goals)
    * [Structure](#structure)
* [Design](#design)
    * [Colour Scheme](#colour-scheme)
    * [Typography](#typography)
    * [Imagery](#imagery)
    * [Wireframes](#wireframes)
* [Features](#features)
    * [Navigation](#navigation)
    * [About Section](#the-about-section)
    * [History Section](#the-history-section)
    * [Artist Section](#the-artist-section)
    * [Sign Up](#newsletter-form)
    * [Footer](#the-footer)

* [Testing](#testing)
    * [Lighthouse Testing](#lighthouse-testing)
    * [Validator Testing](#validator-testing)
    * [Manual Testing](#manual-testing)
    * [Bugs Identified During Development](#bugs-identified-during-development)

* [Technologies Used](#technologies-used)
* [Deployment](#deployment)
    * [Project Creation](#project-creation)
    * [GitHub Pages](#deployment-to-github-pages)
    * [Run Locally](#run-locally)

* [Credits/References](#creditsreferences)
    * [Content & Media](#content--media)
    * [Code](#code)
    * [Achknowledgements](#achknowledgements)



# User Stories
## First Time Visitor Goals
* As a first time user, I want to understand the purpose of the site & learn some basic information about the electric guitar.
* As a first time user, I want to navigate throughout the site to find different types of content.
* As a first time user, I want to sign up to the "Newsletter".
* As a first time user, I want to learn about the guitar manufacturers.
* As a first time user, I want to learn about the different types of electric guitar.
* As a first time user, I want to learn about different guitar players and the types of guitar they use.


# Structure
This is a single page website, all information is positioned in a specific order, making it easier for users to navigate the website and consume the content in a precise order. There is a navigation bar at the top of the page that seamlessly scrolls/directs users to each section. This allows users to navigate the site easily.
> As a first time user, I want to navigate throughout the site to find different types of content.

The first section that the user sees is the about section. This contains images and basic information about the four dominant types of electric guitar. It contains links to each manufacturer and the individual types of guitar listed.
>As a first time user, I want to understand the purpose of the site & learn some basic information on the electric guitar.

The Sign Up section contains a form where users can sign up to the 'Newsletter' to stay up-to date with some fictional news. A user needs to provide their name & email address. As JavaScript is not part of this project stack, data submitted within the form is not stored.
>As a first time user, I want to sign up to the "Newsletter".

The History section contains some basic information about the history of the electric guitar coupled with vintage guitar image.
>As a first time user, I want to learn some basic information about the history of the electric guitar.

The Artist section contains images of various guitarists and the guitars they play. Each is linked to more detailed information about said guitarist.
>As a first time user, I want to learn about the different guitarists and their preferred guitars.

# Design
## Colour Scheme
The two main colours used throughout the website are a pastel green (#CAD2C5) for background, a dark green (#354F52) for text, and purple (#800080) for links, as these colours compliment each other and are .
pastel
## Typography
The headers throughout the website are using the Playfair-Display font and the main body text is using the Roboto font.

## Imagery
All images are related to the electric guitar and guitat players. The main image is of a music shop, which is where a lot of guitars reside. The size of the logo image varies on screen size. All artist images are of famous guitarists designed to capture visual interest of the user and keep a consistent theme.

## Wireframes
These were inital designs, I refactored these throughout development.

![image](https://user-images.githubusercontent.com/111641748/196057326-c42a69f5-36ad-4d4b-9418-e44f88e4889d.png)
![image](https://user-images.githubusercontent.com/111641748/196057359-33926760-ad4c-451e-8907-a8859f3d2efe.png)



# **Features**


## Navigation
* At the top of the page, is the main heading and title of the page with the navigation links below.
* The navigation links are positioned below the main heading in the centre of the screen: About, History, Artists & Sign Up which link to different sections on the same page.
* The navigation has a dark green text colour and to make it visible over the pastel green background colour.
* The navigation indicates the website's topics and makes the different sections of information easy to locate.
![image](https://user-images.githubusercontent.com/111641748/196044654-4fed4d74-2398-400b-8d52-51b52aa4d9af.png)

## The About Section
* The movie section gives the user basic details about different types of guitar.
* The title and images of guitar are displayed, with links provided to the guitar brand and model.
![image](https://user-images.githubusercontent.com/111641748/196045436-b2900bb4-a628-42d5-a8f3-71f3feee4261.png)


## The History Section
* The history section gives the user details a very brief overview of the history of the electric guitar, coupled with an image of a vintage guitar. Contained within the text are links to specific personnel and model.
![image](https://user-images.githubusercontent.com/111641748/196045765-de842ec2-81ff-46b9-94f7-60189cc6df52.png)

## The Artist Section
* The artist section has a gallery of guitar players with their chosen guitar. When the user clicks on an image, a link to additional image on the artist is provided.
![image](https://user-images.githubusercontent.com/111641748/196046486-a30993fb-f7ff-46ea-ad4c-ef6d63cf6cd0.png)

## Newsletter Form
* The sign up form allows user to sign up to the fictional Newsletterb which proposes to keep them up-to date with musings on the electric guitar. When the form is submitted, the user is brought to a page where they have the option to return to the website. Form validation is implemented, the form cannot be submitted if the fields are left empty and if the user does not provide valid syntax for an email address.

![image](https://user-images.githubusercontent.com/111641748/196046952-9687e5f8-aa09-4b6b-9fa0-92c03c473a4c.png)

## The Footer
* The footer section includes links to social media sites that may be relevant to the electric guitar. The links open a new tab to allow easy navigation for the user.
* The footer encourages users to keep up to date and connected via social media.

![image](https://user-images.githubusercontent.com/111641748/196047221-51ccf104-95e1-4e98-8615-cacd842208d3.png)


# **Testing**

## Lighthouse Testing
* The Lighthouse tool in Chrome DevTools is used to test a websites performance & accessibility. It is an open-source automated tool used to improve the quality of webpages. 
When I tested my website, I had poor performance as the landing image file size was over 2mb, I compressed the image to reduce the overall file size. This increased the performance significantly.
![image](https://user-images.githubusercontent.com/111641748/196058080-96f6166f-8b97-4501-a5ed-3fded3280c8f.png)

## Validator Testing
* To verify that the HTML code written following the expected standards, I conducted validator
testing with the W3C Markup Validator. I fixed the errors and warnings, most of my errors were missing closing tags.
![image](https://user-images.githubusercontent.com/111641748/196054625-7c05310c-2f41-4ac6-9053-3347fe93e0e5.png)


* CSS styling was validated using the W3C CSS Validation Service. I had one error where I was using a redundant styling element, I removed this from my code.
![image](https://user-images.githubusercontent.com/111641748/196054658-3967467b-0fb9-4d37-9dc9-60387ad8ef9c.png)

## Manual Testing
| Feature                 | Expect                                                 | Action             | Result            |
| -------------           | -------------                                          | ------------------ | -------           |
| About Navbar Button    | When clicked the page scrolls to the 'about' section  | Clicked 'about' button on navbar      | Page scrolled to 'about' section             |
| History Navbar Button    | When clicked the page scrolls to the 'history' section  | Clicked 'history' button on navbar      | Page scrolled to 'history' section             |
| Gallery Navbar Button    | When clicked the page scrolls to the 'gallery' section  | Clicked 'gallery' button on navbar      | Page scrolled to 'gallery' section             |
| Sign Up Navbar Button    | When clicked the page scrolls to the 'sign up' section  | Clicked 'sign up' button on navbar      | Page scrolled to 'sign up' section             |
| About section - les paul link    | When the 'Les Paul' link is clicked, site with additional information opens in a seperate tab  | Clicked 'LES PAUL' link in about section      | Page with additional information opened in a new tab.             |
| About section - les paul link    | When the 'Les Paul' link is clicked, site with additional information opens in a seperate tab  | Clicked 'LES PAUL' link in about section      | Page with additional information opened in a new tab.             |
| About section - stratocaster link    | When the 'stratocaster' link is clicked, site with additional information opens in a seperate tab  | Clicked 'STRATOCASTER' link in about section      | Page with additional information opened in a new tab.             |
| About section - sg link    | When the 'sg' link is clicked, site with additional information opens in a seperate tab  | Clicked 'SG' link in about section      | Page with additional information opened in a new tab.             |
| About section - telecaster link    | When the 'telecaster' link is clicked, site with additional information opens in a seperate tab  | Clicked 'TELECASTER' link in about section      | Page with additional information opened in a new tab.             |
| Responsive Navbar    | When the screen size is reduced, the nav elements should be aligned beside eachother & readable| Used ChromeDev Tools to reduce page size gradually      |  Nav elements and navbar was responsive            |
| Form Submission   | When the submit button is clicked, the user is brought to a new page  | Typed 'clive' in the  name input field. Typed 'clive@email' in the email field. Clicked the submit button     | Brought to a new page, form submitted successfully            |
| Form Validation - email    | When an invalid email is entered, the form does not submit  | Typed 'clive' in the  name input field. Typed 'test email' in the email field.      | Form did not submit, received pop up warning that email was invalid           |
| Form Validation - empty fields  | When a field is left blank, the form does not submit   |  Typed 'clive' in the name input field. Typed '' in the email field.    | Form did not submit, received pop up warning that the field is required            |

## Bugs Identified During Development
* Image would not load as the file type was a gif. Changed image to JPG to resolve.
* I used an input type 'text' instead of 'email' in sign up form.
* I originally used inline block to style the nav element. I updated this to use flexbox as it is more responsive.
* I originally used inline block to style the footer element. I updated this to use flexbox as it is more responsive.
* As this is my first time using HTML / CSS, I found it difficult to differentiate the various sections, divs etc. As a temporary solution, I added garish colors to make the sections more identifiable. I removed the colours once each section/div was clear to me.
* When linking the different IDs in the navbar, I was missing a '#' in the form href attribute, meaning the link was not working correctly. I added the '#' to identify the form section.
* I attempted to add text to the artist gallery, I got bogged down trying to find the correct format for the HTML code & eventually discarded this idea.
* I removed radio buttons from the form as I could not validate these using pure HTML & CSS.
* It took me awhile to figure out how to overide the default purple on the 'a' tags. I eventually targeted the correct selector in css & solved this issue.
* At this stage, I am not fully comfortable coding correctly to ensure responsive design.

# Technologies Used
* [HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) 
* [Google Fonts](https://fonts.google.com/)
* [Github](https://github.com/clive2112/electric-guitar)
* [GitPod](https://gitpod.io/)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator)
* [W3C HTML Validator](https://validator.w3.org/#validate_by_input)
* [Font Awesome](https://fontawesome.com/)
* [Image Compressor](https://www.img2go.com/result#j=098a3003-d39c-474f-8a44-1387375ed506)

# **Deployment**
## Project Creation
This project was created using Gitpod, Gitpod provides prebuilt development environments with a variety of IDEs. 

To use Gitpod, install the Gitpod extension on either Firefox or Chrome. When the extension is installed, it adds a green Gitpod button to Github, where we can click to create a workspace in Gitpod.

For this project, I used the Visual Studio IDE. I used the prebuilt environment provided by [Code Institue](https://github.com/Code-Institute-Org/gitpod-full-template) to start this project. I clicked the 'use this template' button and named my repository 'electric-guitar'. I then created a Gitpod workspace by clicking the green gitpod button in my [electric-guitar](https://github.com/clive2112/electric-guitar) repository.

I used the following commands throughout the development of this project:
* **python3 -m http.server**  - This command runs a local webserver to view the project.
* **git add .** - This command adds all the changes that have been in the working directory to the staging area. Ready to be committed.
* **git commit -m ""** - This command is used to write descriptive messages of what changes have been made to the code and commits the changes to the local repository.
* **git push** - This command pushes all the committed changes to the Github repository.

## Deployment to GitHub Pages
1. Navigate to [GitHub Repository](https://github.com/clive2112/electric-guitar)
2. Click the 'Settings' tab.
3. Scroll down to the 'pages' tab on the navigation bar.
4. Open the 'Pages' tab.
5. Select 'main' branch as the source.
6. Click 'save'.
7. Click the link provided to go to the deployed website.
8. The live link can be found here - [electric-guitar](https://github.com/clive2112/electric-guitar).

## Run Locally
1. Locate the [GitHub Repository](https://github.com/clive2112/electric-guitar).
2. Click the 'Code' dropdown button.
3. Copy the git URL from the HTTPS text bar.
4. Open a terminal window and locate the directory where you want to store the project.
5. Type the 'git clone' command in the terminal, then paste the git URL. Click return on your keyboard to enter the command.
6. A clone of the project will be created locally on your machine.
**Note** - git commands only work if git is installed on your machine. Find installation documentation [here](https://git-scm.com/).

# **Credits/References**
## Content & Media
I used 'Wikipedia' for all Guitar, Guitar manufacturer and individual artist links.
The Les Paul image is from [www.nstuffmusic.com] using the link ( https://www.nstuffmusic.com/images/product/medium/ae00-50087.jpg)
The Stratocaster image is from [www.suredone.com] using the link ( https://assets.suredone.com/2163/media-pics/ss3284-fender-custom-shop-60-stratocaster-heavy-relic-aged-olympic-white-guitar-4.jpeg)
The SG image is from [www.gearnews.com] using the link (https://www.gearnews.com/wp-content/uploads/2018/03/Gibson-Gary-Clark-Jr.-Signature-SG-in-Vintage-Cherry-with-three-P90sjpg-425x425.jpg)
The Tele image is from [www.reverb.com] using the link (https://images.reverb.com/image/upload/s--H_2Pd4Fw--/f_auto,t_large/v1542321851/ob5w4pggq5cda4zgr3ac.png)
The history text  is from  [www.mentalitch.com] using the link (https://mentalitch.com/a-brief-history-of-the-electric-guitar/)and [www.yamaha.com] using the link (https://www.yamaha.com/en/musical_instrument_guide/electric_guitar/structure/)
The vintage strat image is from a standard image browser using the link (https://duckduckgo.com/?q=relic+1957+fender&t=newext&atb=v248-1&iar=images&iaf=size%3ALarge&iax=images&ia=images&iai=https%3A%2F%2Fimages.reverb.com%2Fimage%2Fupload%2Fs--RkZZ6WcC--%2Fa_exif%2Cc_limit%2Ce_unsharp_mask%3A80%2Cf_auto%2Cfl_progressive%2Cg_south%2Ch_1600%2Cq_80%2Cw_1600%2Fv1447799284%2Fdhrhi4uipmsjeni0d9bk.jpg)


## Code
* [W3Schools](https://www.w3schools.com/) was referenced throughout my project for different tags & syntax.
* [W3Schools Flexbox](https://www.w3schools.com/csS/css3_flexbox.asp) was referenced throughout my project for different tags & syntax.
* [Love Running](https://github.com/clive2112/love-running) was referenced throughout development.
* [Youtube - Image Overlay](https://www.youtube.com/watch?v=exb2ab72Xhs&t=343s) referenced in the gallery section.
* [Youtube - a tag](https://www.youtube.com/watch?v=ztNR3FqdNzU&t=61s) to understand the anchor tag.
* [Youtube - Flexbox Gallery](https://www.youtube.com/watch?v=QmZNFnqwu74) referenced when creating the gallery.
* [Code Institute](https://learn.codeinstitute.net/ci_program/diplomainsoftwaredevelopmentecommerce) HTML & CSS module.


## Achknowledgements
My daughter is a student on this course & was of great inspiration.
I referenced some of her [previous projects](https://github.com/emmaC11).




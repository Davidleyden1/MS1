## Table of content
* [Introduction](#introduction)
* [User experience](#user-experience)
* [Design](#design)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

## Introduction
David Leyden hysiotherapy is targeted at individuals seeking physiotherapy treatment. The aim of this website is to provide information about the lead physiotherapist, the services provided. Another aim of the website is to allow people to get in touch via a form that could in time be linked to a booking system.

## User experience
### User story

* Goals for a first time visitor
  * I want to know about the background of the physiotherapist
  * I want to know what services are provided
  * I want to know if the problem I am having is covered
  * I want to know if this is a professional, experienced service
  * I want to be able to contact the clinic and move towards arranging an appointment

* Goals for a returning visitor 
  * I want to remind myself of the physiotherapists skills
  * I want to refamiliarise myself with the clinic

* Goals for a frequent visitor  
  * I want a quick overview to make sure nothing has changed with the service

* The website owner's goals
  * I want to attract new clients
  * I want to inform clients of services provided.
  * I want to ensure clients can contact me and make steps towards booking
  * I want to get across that this is professional clinic
  * I want to ensure customers can access our online presnce

## Designgit
The design of the website is divided into three separate areas for easy navigation. The upper section is the About section, which details professional qualifications and what clients can expect from the service. The second section is a portfolio section which highlights some of the main treatments provided. This helps clients to better unstand services offered and what they entail. The third and final section is a form section which allows clients to contact the clinic as a step towards arranging appointments.

### Wireframes
The layout of the website was initially sketched on a piece of paper. A wireframe of each page was then created in
[Balsamiq](https://balsamiq.com/).
#### ***Home page***
![Homepage](assets/images/WireframeHome.png)
#### ***Gallery page***
![Gallery](assets/images/WireframeGallery.png)
#### ***Join us page***
![Join Us](assets/images/WireframeJoinus.png)
#### ***Success page***
![Success](assets/images/WireframeSuccess.png)

### Fonts and colour theme
The font that was chosen was Lora, with Serif as a backup.

![First image](assets/images/52867.sm.jpg)

The image on top of the home page was selected first. By using [Colorpicker](https://imagecolorpicker.com/en) a color palette was created based on the colors in the image.
 
 ![Colour palette](assets/images/colourspalette.png)
 
 From the color palette, four colors was choosen as a color theme.

 1. Petrol #516c72
 2. Dark brown #42352c
 3. Light blue-grey #a3acb9
 4. Light greyish #9d8b86

 ### Images
 All images are downloaded from [Freepik](https://www.freepik.com/). They were all selected to match the content of the website as well as the color theme. All images are downsized to fit the purpose of the website.


 The logo was created by [ChatGPT](https://chatgpt.com/).  
 ![C&CLogo](assets/images/c&clogo.jpg)

 A [Favicon](https://favicon.io/) was created based on the letters C and C with the color theme in mind. 

 ### Text
 The five reasons to do crochet, were also created by [ChatGPT](https://chatgpt.com/). The rest of the text was written by the author.

 ## Features
 ### Navigation bar
 ![Navigationbar](assets/images/navigationbar.png)

The navigation bar is located at the top of every page. In the navigation bar, you can find links to the sections ***Home, Gallery*** and the ***Join Us*** form. On the left - hand side, there is a Coffee & Crochet logo that takes visitors back to the top of the home page. On devices with a width of 768px or less, the menu is changed to a hamburger dropdown menu.

### Footer
In the footer there are social media icons. By clicking on the icons the visitor is being linked to Coffee & Crochet's *Facebook, Twitter, YouTube* or *Instagram*. The links open in a new tab.

### Form
By clicking on the button ***Join Us*** in the navigation bar, visitors access a form. To submit the form, *Name, Email*, and *Phone* need to be filled in correctly. A confirmation page appears when the form has been successfully submitted. This page contains a button that takes the visitor back to the homepage when clicked.

### Future features
Some ideas about the future:
*  to expand and have meetups in other citys nearby.
* to add meetups for other type of needlework such as knitting.
* to share patterns online.
* to add tutorials to the website

## Technologies Used
### Languages
*  HTML
*  CSS

### Frameworks & Tools
* [Am I responsive?](https://ui.dev/amiresponsive) 
* [Balsamiq](https://balsamiq.com/)
* [Bootstrap v5.3](https://getbootstrap.com/)
* [Colorpicker](https://imagecolorpicker.com/)
* [ChatGPT](https://chatgpt.com/)
* [Favicon.io](https://favicon.io/)
* [Font Awesome](https://fontawesome.com/)
* [Freepik](https://www.freepik.com/)
* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [Gitpod](https://www.gitpod.io/)
* [Google Fonts](https://fonts.google.com/)


## Testing
### Validation
* [HTML Validator](https://validator.w3.org/) has been used frequently throughout the project. Syntax errors have been identified and resolved. Before submission, no errors were found.
![HTML Validator](assets/images/screenshot_2024-11-07_at_19.04.26.png)
![HTML Validator](assets/images/screenshot_2024-11-07_at_19.04.56.png)
![HTML Validator](assets/images/screenshot_2024-11-07_at_19.05.27.png)
* [CSS Validator](https://jigsaw.w3.org/css-validator/) has also frequently been used. Every identified error was corrected prior to submission.
![Validator](assets/images/screenshot_2024-11-07_at_19.06.04.png)
* Lighthouse testing show good results for speed, accessibility, and SEO.

![Lighthouse results](assets/images/screenshot_2024-11-07_at_19.11.35.png)
 
### Responsiveness
The website has been tested on several devices, mobiles, tablets and laptops. It responds as expected on all tested screen sizes. The same applies to different browsers such as Chrome, Microsoft Edge and Safari. 
### User stories
Each user story was tested as follows:

| User story    | Steps |  |Result|
| ------------- | ------|----------------- | -----|
|I want to know what happens at the meetups| In the introduction you can read what happens at the meetups. People are drinking coffee, socialising and doing crochet. Thery are also exchanging patterns, yarn and experiances.|      | Achieved
| I want to know when and where the meetups take place| At the buttom of the homepage there is a section called Meetup Times. Here the visitor can read when and where the meetups is scheduled.|     | Achieved     |
|I want to know why I should join this community   | Five benefits with crocheting are written in the section *Why crochet?* This is five reasons why the visitor should join the community. |    | Achieved
| I want to know if I need to be a professional crocheter to join. | In the introduction it clearly states that everyone is welcome regardless of prior experiance of crocheting.|  | Achieved|
| I want to easily navigate on the website | On top of each page there is a navigation bar. The visitor is linked to the desired section by clicking on it in the navigation bar.|    |Achieved|
| I want to easily check what time the meetup is scheduled for a specific day| In the section *Meetup Times*, the visitor find time and location for the meetups.|  | Achieved|
| I want to see images from previous meetups. | There is a Gallery page filled with images from prior meetups.|   | Achieved|
| I want a quick overview to ensure that no changes have been made.| Time and location are easily to find on the buttom of the home page.|    | Achieved|

|The website owner's goal | Steps  | Result |
| -------- | ------- |---------|
| I want to build a community for the people in the area who crochet.  | In the introduction it says that everyone in the area, is welcome.  |  Achieved
| I want to encourage people to crochet. | The stated benefits to do crochet, and the images is the Gallery are meant to inspire people to crochet. | Achieved
| I want to support the local Cafés.| By having the meetups at the local cafés, it contributes to their business.| Achieved
| I want to spread knowledge about crocheting.| By sharing several benefits with needle work, knowledge is being spread.| Achieved|
| I want to make use of patterns and yarn that aren't being used.| At the meetups people are encouraged to exchange patterns and yarn.|Achieved|


### Manual testing
The Join Us form and all links on all the pages have been tested. The results were satisfactory. More details are shown in the table below.

| What's being tested   | Expected outcome |Actual outcome
| -------- | ------- |-------|
| **Navigation bar**  |   |
| C&C logo | By clicking the logo the visitor will return to the top of the home page  |Works as expected
| Home   | By clicking **Home** in the navigation bar, the visitor will return to the top of the home page   |Works as expected
| Gallery | By clicking on **Gallery** the visitor will get to the gallery page |Works as expected|
| Join us | By clicking **Join us** the visitors get to av form |Works as expected|
|   |   |   |
| **Footer** |     |    |
| Facebook | By clicking the Facebook icon, Coffee & Crochet's facebook page opens up in a new tab |Works as expected|
| Twitter | By clicking the Twitter icon, Coffee & Crochet's twitter page opens up in a new tab |Works as expected |
| YouTube | By clicking the YouTube icon, Coffee & Crochet's YouTube channel opens up in a new tab |Works as expected |
| Instagram | By clicking the Instagram icon, Coffee & Crochet's instagram opens up in a new tab |Works as expected|
|      |     |    |
| **Join Us form** |     |    |
| Name | The visitor needs to fill in a name to be able to submit the form |Works as expected|
| Email | The visitor needs to fill in an email that includes an @ to submit the form |Works as expected|
| Phone number| An number combination needs to be filled in to subit the form |Works as expected|
| Submit -button | When the button is being pushed, the form is being submitted and a confirmation page appears |Works as expected|
| Return to homepage -button | When clicking the button, the visitor returns to the home page|Works as expected|

### Bugs
One bug that was discovered during the project concerned the navigation bar. At this point, the navigation bar included a link to the section ***Meetup Times***. The link worked fine while the visitor was on the home page, however, if the visitor clicked the link on any of the other pages, it did not work as expected . 

The bug was resolved by removing ***Meetup Times*** from the navigation bar.

### Unfixed bugs
All identified bugs were resolved.

## Deployment

### Version Control
The website was created using Gitpod, and pushed to GitHub to the remote repository. Througout the project the following git commands were used,
* **Git add .** *-Adds a change in the working directory to the staging area.*
* **Git commit -m "message"** *-Commits changes to the local repository.*
* **Git push** *-Uploads the commited changes to the remote repository in Github.*


### Deployment to GitHub Pages
1. Go to the **Settings** tab of your GitHub repo.
2. On the left-hand sidebar, in the Code and automation section, select **Pages**.
3. Make sure:
   * Source is set to 'Deploy from Branch'.
   * Main branch is selected.
   * Folder is set to / (root).
4. Under Branch, click **Save**.
5. Go back to the Code tab. Wait a few minutes for the build to finish and refresh your repo.
6. On the right-hand side, in the Environments section, click on **'github-pages'**.
7. Click **View deployment** to see the live site.

The link to the live website: [Coffee & Crochet](https://emelie-nilsson.github.io/Milstone-project1/)

### How to clone the repository
1. From the list of repositories, click the repository you want to clone. 
2. Click the green button **Code**.
3. Choose **HTTPS** followed by **Open with GitHub Desktop**.
4. Click **Choose** and navigate to a local directory where you want to clone the repository.
5. Click **Clone**

### How to fork the repository
1. From the list of repositories, click the repository you want to fork.
2. Click on the **Fork** button in upper right hand corner.

## Credits
### Code
All code is inspired by various lessons and modules in Code Institute's LMS (Learning Management System). 
### Content
The font family is from [Google Fonts](https://fonts.google.com/).

The icons in the footer and in the benefits section, were taken from [Font Awesome](https://fontawesome.com/).

The instructions under [Deployment](#deployment) were taken from the module *Love running -Essentials Project* and [GitHub Docs](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop).  
### Media
The images of the project on different devices, are created using a website called [Are you responsive?](https://ui.dev/amiresponsive)

The logo is made by [ChatGPT](https://chatgpt.com/) and the favicon by [Favicon](https://favicon.io/).

The rest of the images are all downloaded from [Freepik](https://www.freepik.com/).
### Acknowledgements
A special thank you to my mentor for his advice, guidance and support. I also want to thank my brother for his patience and his feedback.
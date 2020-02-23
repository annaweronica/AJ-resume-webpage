![image](/assets/images/backend-image-md.png)


# Resume webpage

[Anna Janiak](https://annaweronica.github.io/AJ-resume-webpage/)

Aim of the **resume webpage** is to represent skills and competences which will lead Anna to get a programming job within IT. 


## UX

Target audience of the **resume webpage** is a recruiter and/or potential employer looking for a full stack developer.

**Layout:**

Minimalistic, simple design in  white and black style including images. 
>The only exception is for google map in Contact sub-page.

- [Desktop, iPod and mobile wireframes overview](/wireframes/all-Desktop-iPad-mobile-view.png)

***Main page:***

At the top of the browser windows there is a menu with logo on the left size and three sub-pages: TECH, Agile and Contact.
Under the menu the user can see main image with female touch. Following underneath we have there colums of the text with descriptions of previous professional experience and simply styled button under each of the section redirecting the user to a previous employer website.<br>

> Please note: main page and landing page refers to home page. The names may be used interchangeably.

***TECH sub-page:***

In this section the user can get fammilar with programming skills and certifications relating to previous IT experience.
There are two columns with description of a Front End and Back End coding experience. By each column of the text there is the image.
At the bottom of the section there is a progress skill bar. The procentage referts to overall confidance in certain coding language.

***Agile sub-page:***

In this section the user can recognize that I have already short experience within IT as Scrum Master and proxy Product Owner in Agile Frameworks.
There are two columns white and black style including images. The only exception is for google map in Contact sub-page.

***Contact sub-page:***

The user has few posibilities to reach out to Anna:<br>
  1. via phone numer and/or e-mail adress which activets a model when pressing a button "Contact me!"<br>
  2. via Conatct Form which is available on the page under a heading "Drop me a message". The inputs of name and email are mandatory to fill up otherwise the toolip will pop up requires the recruiter to do so.<br>
  3. via links to social media which are in footer section. When the user click the social media icon the social media webpage opens in next tab window.<br>

Next to the button "Contact me!" there is a button "CV.pdf" from where the user can open and potentially download Anna CV in pdf form. 
There is also a google map with location of Anna's address.

**Wireframes:**
- [Desktop overview](/wireframes/all-desktop.png)
- [iPod overview](/wireframes/all-iPad.png)
- [Mobile overview](/wireframes/all-mobile.png)


## Featuers 

This is one page website with three sub-pages once the user [scroll down](https://getbootstrap.com/docs/4.3/components/scrollspy/) he will go throught all the sub-pages without need clicking on items in menu.<br>
When the user scrolls down the items of menu actives with white hover letting the user know on which page he is.

**Main page**

1. MENU<br>
At the top of the main page there is a logo in the left-top side.<br>
In the right-top side there are menu sub-pages TECH > Agile > Contact.<br>
All menu items are clickable >*including logo*< and redirectes you one of the above section.<br>
The menu always stays at the top of the windowd browser no metter on which page the user is right now.

2. Typewriting effect<br>
On desktop and iPod the feature's role is to drag more attention to the job title.<br>
On mobile the job title stays in the same style however static.

3. Content buttons<br>
On the main page there are three tetx columns referring to Anna's previous professional experience. Under each ot the colum the user can click on the button which will open in a seperate window browser a previous empolyer's webpage.

**TECH sub-page**

1. Portfolio and certification buttons<br>
Under each of the text colum there are two buttons.<br>
Clicking on *Portfolio* button the future *to be* website will open in the new browser window .<br>
Clicking on *ISTQB* or *IREB* button the website with the officail web page will open in the new browser window. 

**Agile**

1. Frameworks and video buttons<br>
Under each of the text colum there are two buttons.<br>
Clicking on *Official website* button the officail website of the Scrum organization will open in the new browser window .<br>
Clicking on *Video Hint* button the youtube video will pop up in the model. The video stops playing once the model is closed.

**Contact**
1. Contact button<br>
The recruiter has the posibility to click on the *Contact me!* button and the model with contact details will pop up

2. CV button<br>
The recruiter ha sthe posibility to click on the *CV.pdf* putton and the CV in the pdf form will open in the new browser window.

3. Google map<br>
The recruiter can easily find up where Anna is located and what area of the city she lives in. The map has an option of larger view. Then the map open in google maps in the new browser window.

4. Contact form<br>
The recruiter can contact Anna via Contact Form. The Contact Form has three inputs: Name, Email and Message. The first two are required. If there are not filled out the tooltip it will pop up with the message *Please fill out this filed*. Athe the button of the Contact Form there is a *Submit* button.

***USER STORIES***

- As a recruiter or potential employer, I want to learn what professional previous background Anna has.
- As a recruiter or potential employer, I want to learn who is Anna and what skills and competences she has for programming role.
- As a recruiter or potential employer, I want to see what experience and knowledge she has in Agile frameworks.
- As a recruiter or potential employer, I want to has a posibility to contact Anna via phone, email or contact form.
- As a recruiter or potential employer, I want to have a posibility of downloding CV in pdf form.


## Technologies

- HTML/HTML5
- CSS/CSS3

Frameworks:
- [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/)

External sources imported to the project:
- [BootstrapCDN](https://www.bootstrapcdn.com/)
- [jQuery](https://jquery.com/)
- [popper.js](https://popper.js.org/)
- [Google fonts](https://fonts.google.com/)
- [Font awesome](https://fontawesome.com/)

Online IDE:
- [GitPod](https://gitpod.io/workspaces/)

Hosting service:
- [GitHub](https://github.com/annaweronica/AJ-resume-webpage)

Knowledgeable resources which supported Anna during her work:

- [www3school](https://www.w3schools.com/default.asp)
- [stackoverflow](https://stackoverflow.com/)
- [Code Institute lerning materials](https://courses.codeinstitute.net/program/FullstackWebDeveloper)

External code sources implemented and modified:

- [Typewriting effect for an eye catching job title](https://css-tricks.com/snippets/css/typewriter-effect/ "Typewrter effect")
- [Navbar template with logo](https://startbootstrap.com/snippets/navbar-logo/ "Nvabar with logo")
- [Template for a fixed footer with little content](https://stackoverflow.com/questions/16679146/force-footer-on-bottom-on-pages-with-little-content/16679198#16679198 "Fixed footer")
- [Responsive goole map for a Conatc sub-page](https://bootsnipp.com/snippets/or0ZB)
- [Simple contact form](https://codepen.io/formbucket/pen/xEKYoX)
- [Animated Skills Bar which I finally removed - not match to the webpage style](http://cssdeck.com/labs/animated-responsive-skills-bar)
- [Static but minimalistic Skills Bar applied instead](https://codepen.io/robinselmer/pen/RarLQK)

External code sources which helped to solve issues:

- Issue: still palying the youtube video in the background when the model was closed [stackoverflow.com](https://stackoverflow.com/questions/13598423/stop-all-playing-iframe-videos-on-click-a-link-javascript)
- Issue: Bootstrap uses offset to resolve spying only, not scrolling. [stackoverflow.com](https://stackoverflow.com/questions/9288482/how-do-i-set-the-offset-for-scrollspy-in-bootstrap/12606867#12606867)


### Testing

---

**HTML Validator**

- [validator.w3.org](https://validator.w3.org/#validate_by_input)<br>
  [No errors or warnings to show.](/wireframes/HTML-validated.png)

**CSS Validator**

- [jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/)<br>
  [No Error Found.](/wireframes/CSS-validated.png)

**Manual Testing**

Webpage and its responsiveness was tested on follwoing browsers:
- Chrom
- FireFox
- Edge
- Internet Explorer<br>
[Exception: the webpage is not supported on Internet Explorer](/wireframes/Internet-explorer-error.png)

**TESTING THE FEATURES**

Webpage and its responsiveness was tested for Desktop, iPod and Mobile through 320 (and smaller) to large desktop sizes.
No bugs or problems detected.

MENU:<br>
Main page > Tech > Agile > Contact:<br>

1. On desktop and iPod:
- Each of these pages leads the recruiter scrolling down through next page to Contact page and the footer at the bottom with also posibility of contact. In some places the recruiter may wanto to be back to another page and he can easily do it clicking on one of the sub-page name on the manu. 
- Clicking on TECH will lead him back to the TECH sub-page. 
- Clicking on Agile sub-page will lead him back to the Agile.
- Clicking on Contact sub-page will lead him back to the Contact. 
- Clicking on logo >Anna Janiak< in menu will lead him back to the main page.

2. On mobile devices:
- The path happens as follows but the menu collapses into a burger. Once cklicking on the burger it will lead the recruiter to the items of the menu and the order happens as the steps above. There is one more menu sub-page to be back to the main page on mobile devices: *Home* re-directing you to the main page. You can still be back to the main page clicking on logo.

Footer:

1. On desktop and iPod:
- The footer is always at the bottom of the scrollspy webpage and consist of three social media icons and underneath a copyright.

2. On mobile devices
- The footer is reduced to social media only.

Typewrter effect:

1. On desktop and iPod:
- The typewriter animation is showing (large and extralarge sizes od viewing window so 992px width and up)

2. On mobile and smaller iPod:
- The typewriter is hidden on all viewing windows smaller than 991px width viewing window. The static job title is showed instead.

**All other featuers remain the same and are fully responsive**


### Deployment

---

The webpage is hosted on github with one master branch:
[github.com/annaweronica/AJ-resume-webpage](https://github.com/annaweronica/AJ-resume-webpage)

> *Anna worked before on big, crossed-functional project within IT on many branches however being misled that I am working by myself on my own project I have been working on one master branch following*
> - git add .
> - git commit -m "name"
> - git push<br>

> **All commends were made as the work incrementation was made progressively and prevented from any code incrementation loss.** 

***GitHub Pages***

To deploy a website on GitHub Pages, follow these steps:

- [Go to Anna's repository](https://github.com/annaweronica/AJ-resume-webpage)
- Click on *Settings*
- Scrolling down you will find *GitHub Pages* 
- Click on the *Source* dropdown menu
- Select *master branch*
- Should appear a green message saying [Your site is published at](https://annaweronica.github.io/AJ-resume-webpage/)

To create a local development repository, follow these steps:

- [Go to Anna's repository](https://github.com/annaweronica/AJ-resume-webpage)
- Click on the *Clone or download*
- Click the check list icon on the right of the newly opened window to clone the repository using HTTPS
- Open Terminal
- Change the current working directory to the location where you want the cloned directory to be made
- Type *git clone* and paste the URL you copied in step 3 and run the command


### Credits

---

Anna have joined Code Institue to leran as much as I can from I believe best teachers, tutors and mentors and that will give Anna the opportuinity to join IT work environment after the graduation of CI programme. 

***Content***

Created by Anna Janiak<br>
Copy right @Anna Janiak

Exceptions:
>- The text in SCRUM & KANBAN in section was copied from official SCRUM website [scrum.org](https://www.scrum.org/resources/what-is-a-scrum-master) 
>- The text in SAFe section was copied from official SAFe website [scaledagileframework.com](https://www.scaledagileframework.com/product-owner/)

***Media***

The source of all legally licensed images come from [Adobe Stock](https://stock.adobe.com/ie/)<br>
Ale the wireframes were made by Anna using [balsamiq cloud](https://balsamiq.cloud/sxgoi9m/projects)

---

Enjoy!
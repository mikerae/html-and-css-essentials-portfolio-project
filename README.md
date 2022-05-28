# Enjoy Fire! Static Website: Code Institute Milestone Project 1
![Responsive screenshot](/assets/images/amiresponsive.png)

## Live Version of Enjoy Fire! Website
A live version of the Enjoy Fire! website can be found here - https://mikerae.github.io/html-and-css-essentials-portfolio-project/

## Contents
+ [User Experience Design - UXD](#user-experience-design "User Experience Design")
    + [Strategy](#strategy "Strategy")
        + Stakeholder Stories
    + [Scope](#scope "Scope")
        + Needs and Requirements
    + [Structure](#structure "Structure")
        + Website Flow Diagram
    + [Skeleton](#skeleton "Skeleton")
        + Wire Frames
    + [Surface](#surface "Surface")
        + Colours
        + Typography
        + Icons
        + Images
+ [Implemented Features](#implemented-features "Implemented Features")
    + Navigation Bar and Footer
    + Semantic HTML
    + Aria Provision
    + Progressive Reveal
    + Enjoy Fire Section
    + Light a Fire Section
    + Tools for Lighting Fire Section
    + Responsible Firelighting Section
    + Stay In Touch Section
    + Response Page
+ [Future Development](#future-development "Future Development")
    + Club Membership Area
    + Camp Fire Cookout Events
    + Training Meet-ups
    + Community Gatherings Gallery
    + Bug Fixes
+ [Technologies Used](#technologies-used "Technologies Used")
    + HTML5
    + CSS3
    + GitPod and demonstrates rudimentary competence in its use.
    + Git
    + GitHub
+ [Testing and Resulting Issues](#testing-and-resulting-issues "Testing and Resulting Issues")
    + Human Testing
    + Developer Tools
    + Amiresponsive site
    + Validator Testing
    + Lighthouse Accessibility Testing
+ [Known Issues](#known-issues "Known Issues")
+ [Development and Deployment](#development-and-deployment "Development and Deployment")
    + IDE
    + Version Control
    + GitHub
    + GitHub Pages
    + External Resources
    + Development Issues
+ [Credits](#credits "Credits")
    - Content
    - Media
    - Code
    - Feedback

# User Experience Design
[Back to Top](#contents "Contents")           

## Strategy
[Back to Top](#contents "Contents")
### Stakeholder Stories

#### Users
Users want to find information on how to light a fire.
They want to develop their firelighting skills, to use their firelighting skills, to meet with like-minded people and enjoy using their skills together.
#### Site Owner
The Site Owner would like to provide and promote responsible firelighting knowledge, to promote training in firelighting techniques and to promote enjoyment of and respect for the outdoors.

#### Wider Members of the Community
Members of the Wider Community would like to prevent damage to land and property, and to promote responsible enjoyment of the countryside.

## Scope 
[Back to Top](#contents "Contents")          
Here is a summary of the needs and requirements of the stakeholders. Priority was given to features which were implementable within the timeframe of the project, and using technology available. Some features were noted for future release.
![UXD Scope](/assets/images/uxd-scope.png)

## Structure           
[Back to Top](#contents "Contents")
This flow chart describes the information flow of the site.
![UXD Structure](/assets/images/uxd-structure.png)

## Skeleton           
[Back to Top](#contents "Contents")
Wireframes were created in the Balsamiq Wireframes app. These represent the project design intentions. The current build was modified by build experience, feedback from testers, my Mentor and the results of other testing procedures.
### Enjoy Fire! Section (Home Section)           
[Back to Top](#contents "Contents")
![Enjoy Fire! Section](/assets/images/enjoyfire-home-wireframe-uxd.png)
This 'home' section strongly suggests the enjoyment of a camp fire with friends. It offers an easily accessible summery of the site whilst progressively revealing more content. Each of the four areas are linked to the navbar, and also to the associated text titles. The pop-out on-hover progressive reveal design was abandoned in this version for time and complexity reasons.
In the build for smaller screens, the links in the nav bar were replaced by a 'hamburger menu'.
### Light a Fire! Section           
[Back to Top](#contents "Contents")
![Light a  Fire! Section](/assets/images/lightfire-wireframe-uxd.png)
This section contains a scrolling article containing tips on Lighting a Fire. It also contains a contents sidebar which remains visible whist the article contents are scrolled. The contents items are linked to the relevant article sections. For smaller screens and tablets, the sidebar was made invisible.
### Tools for Firelighting Section           
[Back to Top](#contents "Contents")
![Tools for Firelighting](/assets/images/tools-wireframe-uxd.png)



The three recommended tools are displayed with a short description. A button inviting the purchase of each tool opens an external link to the Ray Mears Bushcraft shop where the tools can be purchased.
### Responsible Firelighting Section           
[Back to Top](#contents "Contents")
![Responsible Firelighting](/assets/images/responsiblefire-wireframe-uxd.png)
This section reinforces the need for and benefits of responsible firelighting using imagery and a popular quotation from Chief Seattle. It provides external links to further information.
### Stay In Touch Section           
[Back to Top](#contents "Contents")
![Stay in Touch](/assets/images/stayintouch-wireframe-uxd.png)
An image celebrating the social benefits of camp-fire camaraderie compliments a form inviting the user to submit relevant information enabling them to stay in touch with the site owners. This is a dummy form since this is a static website. A server response is simulated by the 'Stay In Touch' button being linked to a second response.html page shown below.
### Response Page           
[Back to Top](#contents "Contents")
![Response Page](/assets/images/response-wireframe-uxd.png)
A simple response 'thank you' is offered to inform the user that their submission has been received. The user may return to any section of the site using the same navbar elements common throughout the site. 

## Surface           
[Back to Top](#contents "Contents")
### Colour Palette
![Colour Pallet](/assets/images/colour-pallet.png)
The Colour Pallet was generated at the [Coolers website](https://coolors.co/palette/D4C2B6-C38E71-BD9792-60414A) using the hero (Enjoy Fire) image.

NB: There is doubt that these provide sufficient contrast and accent  To be reviewed in testing.

This indeed proved to be the case. The colour 'cornsilk' rgb(255,248,220) was used in 'call-to-action' and responsive elements to provide additional contrast to  the pallet.

![Cornsilk used in responsive hover action](/assets/images/cornsilk.jpeg)

### Typography           
[Back to Top](#contents "Contents")
Fonts were chosen from the [Google Fonts website](https://fonts.google.com/).
The initial choice of fonts were EB Garamond for body text and Mitr for headings.
The script for these fonts was:
@import url('https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;0,700;1,400&family=Mitr:wght@400;500&display=swap');

After feedback, it was decided to change the body font to 'Roboto'.
The final font script used in css was:
@import url('https://fonts.googleapis.com/css2?family=Mitr:wght@400;500&family=Roboto&display=swap');

### Icons           
[Back to Top](#contents "Contents")
Icons were chosen from the [FontAwesome website](https://fontawesome.com/) using the following script:
 <script src="https://kit.fontawesome.com/7299876a46.js" crossorigin="anonymous"></script>

### Images           
[Back to Top](#contents "Contents")
Most mages were downloaded from the [Pexels Free Photos website](https://www.pexels.com/search/free/) under the appropriate creative commons copyright licence.

Each photographer was credited using the Figcaption element.
Where a photo was downloaded from a source other than Pexels, the source was indicated in the relevant figcaption element.

The one image not overtly credited was the hero image in the Enjoy Fire Section:
![Enjoy Fire! Hero Image](/assets/images/hero.jpg)
This photo (No. 344102) was taken by Oleksandr Pidvalnyi and downloaded from the Pexels website  and used under their creative commons licence.

# Implemented Features           
[Back to Top](#contents "Contents")
## Navigation Bar and Footer
### Navigation Bar
A navigation bar is fixed to the top of every display screen. This has links to each of the site sections on the right of the navigation bar. The Logo on the left of the navigation bar is linked to the Enjoy Fire! section (home section).

![Navigation Bar](/assets/images/navbar.png)

For smaller screens where there was insufficient space to display the links, the commonly accepted convention of a  'hamburger menu' was used to reveal the navigation links. The core code for the 'hamburger menu' was copied from https://codepen.io/alvarotrigo/pen/XWejzjR and modified for this project.

![Hamburger Menu: closed](/assets/images/hamburgermenu-closed.png)

![Hamburger Menu: open](/assets/images/hamburgermenu-open.png)

### Footer           
[Back to Top](#contents "Contents")
The footer is visible at the bottom of each of the two pages i.e. the main content page index.html and the form response page response.html. It contains external links to social media sites. The code for the footer was copied from the Code Institute 'Love Running' module and modified for this project.

![Footer](/assets/images/footer.png)

Each navigation and footer element is responsive, i.e. when hovered, the text changes colour to indicate a link.
The style of the footer and navbar were made consistent using the class '.bar'.
## Semantic HTML           
[Back to Top](#contents "Contents")
The following semantic html elements were used to facilitate engagement with the site for visually impaired users:
+ Sections: Each of the sections in the site are enclosed in this element. The section h2 element gives the section semantic content.
+ Nav: The elements enclosed in the navbar provide semantic content.
+ Footer: The elements enclosed in the footer provide semantic content.
+ Article: The content of the Light a Fire article are enclosed by this element ant can be understood across the web as a stand-alone unit.
+ Aside: The navigation content links in the Light a Fire section are enclosed in the aside element.
+ Figure: Almost all images are enclosed in the figure element.
+ Figcaption: Where the figure element was used, a figcaption element was used to describe the image.
## Aria Provision           
[Back to Top](#contents "Contents")
To assist visually impaired users, use of aria-labelledby and aria-label elements were used to describe elements who’s meaning might otherwise be unclear.
## Progressive Reveal           
[Back to Top](#contents "Contents")
Each section partially reveals the header of the next section, inviting the user to scroll down and explore the site further.
## Enjoy Fire Section           
[Back to Top](#contents "Contents")
This 'home' or 'landing' section is the first thing a user will see when arriving at the site. It promotes a warm, welcoming, social feeling. The user is progressively drawn into the content of the site using four responsive 'call to action' buttons which briefly describe the contents of the section of the site. These buttons are linked to each of the site sections. At the bottom of the viewed area, the header of the next section is partially revealed.

![Enjoy Fire Progressive Reveal](/assets/images/enjoy-fire-progressive-reveal.png)

## Light a Fire Section           
[Back to Top](#contents "Contents")
Tips for lighting a fire are found within the artcle in this section.
Further information is referenced using clearly marked external links.

![Light a Fire External links](/assets/images/lightfire-external-links.png)

The sections of the article were displayed using the Grid Display attribute.
For larger screens, three columns were used, for medium screens two columns, and for smaller screens, one column. This was achieved using the relevant media query sections in the css file.
The aside containing the article section buttons is constantly in-view whilst the article is being scrolled through. This was achieved using the 'sticky' display attribute.

![Light a Fire Aside](/assets/images/lightfire-aside.png)

The contents aside is only available for larger screens. The code to not display the aside was used within media queries in the css for smaller screens.

The individual sections of this article are linked to call-to-action buttons in the aside. When clicked, the section scrolls to the appropriate section.

![Light a Fire Aside offset](/assets/images/lightfire-contents-links-header-offset.png)

## Tools for Lighting Fire Section           
[Back to Top](#contents "Contents")
In this section, the user is introduced to three entry level fire-lighting tools. For each tool there is an image, a brief description and a call-to-action button inviting the user to buy a tool. The buttons are linked to the relevant areas in the external site for Ray Mears Bushcraft shop, where a fuller description of each tool can be found. If desired, the user may purchase each tool from the external shop. Whilst I have no affiliation to Ray Mears Bushcraft or his shop, I can recommend the site, the  shop and the tools.

For larger screens, three tools are displayed side by side. For medium screens, 
two are displayed, and for small screens one tool is displayed.

![Tools for firelighting: Large Screens](/assets/images/tools-large.png)

![Tools for firelighting: Medium Screens](/assets/images/tools-medium.png)

![Tools for firelighting: Small Screens](/assets/images/tools-small.png)

## Responsible Firelighting Section           
[Back to Top](#contents "Contents")
The main emotional thrust of this section is to invoke a sense that lighting fires responsibly is to be encouraged. This is achieved through the use of a suitable image and the familiar and helpful quotation from Chief Seattle to "Take only Memories, Leave only Footprints".
Anyone who has tried to achieve this whilst enjoying the countryside will quickly realise that significant thought and effort is required for this to be accomplished. Anyone who has encountered the devastation caused by thoughtless behaviour will readily warm to Chief Seattle's sentiments.
The three call-to-action buttons take the user to external sits where more in depth information may be found.

![Responsible Fire Lighting](/assets/images/responsible-firelighting.png)

## Stay In Touch Section           
[Back to Top](#contents "Contents")
In this section the user is invited to join our community, initially by indicating an interest in staying in touch. There is an optional opportunity to communicate the user's bushcraft interests and sign up for a news letter and information about upcoming events.
Basic contact information is required to be submitted. If a name input field is not filled in, or if a non-valid email address is entered the user is prompted to properly fill in these fields before the form will be submitted.

The name and email fields are responsive in that the background colour changes on-hover.
The submit button is responsive consistent with all the other call-to-action buttons on the site.

Since this project is limited to a static website it is beyond the scope of the project to handle any form data. A simulated server response is created by linking the submit button to a 'Response page' in which the user is thanked for their interaction.

The Stay In Touch section is the last on index.html so this section displays the footer at the bottom.

The section for large screens is here:

![Stay In Touch](/assets/images/stay-in-touch-large.png)

For small screens, the user scrolls to the bottom of the section to submit the completed form:

![Stay In Touch Upper](/assets/images/stay-in-touch-small1.png)

![Stay In Touch Lower](/assets/images/stay-in-touch-small2.png)

## Response Page           
[Back to Top](#contents "Contents")
This as a separate html document and simulates a response from a server upon receipt of data from the form on the Stay In Touch Section.
The look and feel are identical to the Stay In Touch Section. All the navigation links and footer links are consistent with the rest of the site so that the user may intuitively choose to return to any part of the site.

![Response Page](/assets/images/response.png)

# Future Development           
[Back to Top](#contents "Contents")
## Club Membership Area
Users can become members, and gain secure access to a members area in the site through a Django based authentication.
Here, there is scope for blog posts and event advertising.
## Camp Fire Cookout Events
Social Gatherings advertised on the site, and through the news letter will be held from time to time. Once there is server and database support, users may sign up for and attend these events. This was included in the scope analysis but excluded in the first release.
## Training Meet-ups
Interest in particular skill development can be gauges through blog posts and signup forms.
These events can then be scheduled and advertised, and members can sign up for them. This was included in the scope analysis but excluded in the first release.
## Community Gatherings Gallery
Members may post and display their photos of gatherings held. This was included in the scope analysis but excluded in the first release.
## Fix Currently Known Issues
Currently there are one or two bugs which have yet to be corrected. See the known issues section. These will be corrected in a future release.

# Technologies Used           
[Back to Top](#contents "Contents")
+ HTML5
+ CSS3
+ IDE: The project was created in GitPod and demonstrates rudimentary competence in its use.
+ Version Control: the project used Git to generate a 'Commit History'
+ The project was pushed to GitHub sequentially.

# Testing and Resulting Issues           
[Back to Top](#contents "Contents")
## Human Testing
### Links
+ All external links were tested manually to verify that they were live and that they all opened in a new browser tab or window.
No issues were found.
+ All internal links were tested manually.
After development, no issues were found.
### Consultation and feedback           
[Back to Top](#contents "Contents")
The site was reviewed by the four people and their feedback influenced the development of the project. I thank and gratefully acknowledge the feedback from the following people:
+ Martina Terlevic : Mentor Code Institute
+ Sarah
+ Emily
+ Annabel
### Google Chrome Browser Developer Tools: Responsive Layout           
[Back to Top](#contents "Contents")
Google Chrome Browser Developer Tools were used to develop and test various screen size layouts.
### Amiresponsive Site           
[Back to Top](#contents "Contents")
The site amiresponsive https://ui.dev/amiresponsive was used to test the responsiveness of the site. The image at the top of this readme.md file was generated from this site and demonstrates that the site is indeed responsive.
## Validator Testing           
[Back to Top](#contents "Contents")
### W3 HTML Validator
The HTML code was validated using the W3 HTML validator and passed with no issues.

![index.html Validation](/assets/images/w3-index-html-validator.png)

![response.html Validation](/assets/images/w3-response-html-validator.png)

### W3 CSS Validator           
[Back to Top](#contents "Contents")
The CSS code was validated using the W3 CSS validator and passed with no issues.

![CSS Validation](/assets/images/w3c-css-validator.png)

### Lighthouse Accessibility Validator           
[Back to Top](#contents "Contents")
The site passed the Lighthouse accessibility validator in both Desktop and Mobile modes.
#### Desktop Mode

![Lighthouse index.html Desktop](/assets/images/lighthouse-index-desktop-validator.png)

![Lighthouse response.html Desktop](/assets/images/lighthouse.response-desktop-validator.png)

#### Mobile Mode

![Lighthouse index.html Mobile](/assets/images/lighthouse-index-mobile-validator.png)

![Lighthouse response.html Mobile](/assets/images/lighthouse-response-mobile-validator.png)

# Known Issues           
[Back to Top](#contents "Contents")
+ The layout for small screens (mobile phones) in landscape mode is not correctly formatted. There was not sufficient time to make this correction before the project deadline. The formatting is acceptable for small screens in portrait mode. It was therefore decided to proceed to release in this minimum viable version.

# Development and Deployment           
[Back to Top](#contents "Contents")
## IDE
The project was created in GitPod.
## Version Control
The project used Git to generate a 'Commit History'.
## GitHub
The project was pushed to GitHub sequentially.
## GitHub Pages
The project was deployed to the internet for viewing by the public using GitHub pages.
A live version of the Enjoy Fire! website can be found here - https://mikerae.github.io/html-and-css-essentials-portfolio-project/
## External Resources
Throughout the development process, external resources were used. The following were frequently used:
+  MDN web docs html https://developer.mozilla.org/en-US/docs/Web/HTML
+ MDN web docs CSS https://developer.mozilla.org/en-US/docs/Web/CSS
+ Stack Overflow https://stackoverflow.com/
+ W3 Schools https://www.w3schools.com/
## Development Issues
A variety of developmental issues were encountered throughout this project, from design through to final deployment. Here are some of them.
### UXD: Wire Framing           
[Back to Top](#contents "Contents")
#### Fire Image as header
A fire image used as a background in the navbar was too distracting. It was replaced by a solid colour.
#### Hero image: Home Page           
[Back to Top](#contents "Contents")
Initially a hero image of a fire was used but the colour palette was not suitable. This was replaced with the 'Memories' image.
#### Using  one image in the the Enjoy Fire Section
[Back to Top](#contents "Contents")
To reduce clutter and conflicting messages, only one image was used on the home page.
#### Use of Popup Boxes with images and further progressively revealed contents
[Back to Top](#contents "Contents")
Popup Boxes were intended to be used to reduce clutter and too much information on the Home Page.The  boxes would appear on hover over key contents signposts to further invite the user to explore deeper into the site. The contents of the popup box signpost would progressively reveal more  contents of that particular area of the site. It was decided that implementation of this feature was beyond the scope of this project for this minimum viable release.
#### Colour Pallet UXD surface           
[Back to Top](#contents "Contents")
The chosen pallet did not have good accents. The accent colour 'cornsilk' rgb(255,248,220) was introduced at the design stage to provide an initial solution.
### Nav Bar elements don’t show Active Status
[Back to Top](#contents "Contents")
For internal page navigation , without using java script, it is not possible to set the ‘active’ status of a link, since this is hard-coded into the html of each linked page.
The work around was to not have an active status, but have an ‘onHover’ indicator , and rely on the user taking note of the clear headers to show where in the document they are.
### All images need a constant border radius            
[Back to Top](#contents "Contents")
CSS targeting the img element provided a solution.
### Header offset for internal links
[Back to Top](#contents "Contents")
Initially, the top of a linked section was obscured by the fixed nav bar. The source links in question were in the Lightfire aside Contents. This was resolved by applying an appropriate offset to the target equivalent to the height off the nav bar. This varies with screen size, so offsets were applied within media queries. The solution to this issue is credited to  Hrvoje Miljak/ Stack Overflow.
    Hrvoje Miljak's  solution is as follows:
```
    html
    <a class="anchor" ></a>

    css 
    a.anchor {
        display: block;
        position: relative;
        top: -250px;
        visibility: hidden;
    }
```
After testing and correction, no issues were found.
### Font Change           
[Back to Top](#contents "Contents")
It was suggested to change the body front from 'EB Garamond' to 'Roboto'.
### Light a Fire Aside menu clarity
[Back to Top](#contents "Contents")
Feedback from Sarah, Emily and Annabel suggested improved clarity for the Light a fire Aside menu. This was implemented by separating the elements a little
### Responsive Layout
[Back to Top](#contents "Contents")
The majority of development issues arose here. The following
issues were encountered and addressed:
#### Images display            
[Back to Top](#contents "Contents")
Images (particularly the hero image) does not stay still as viewport reduces. Their position, aspect and dimensions would change in unwanted ways. This was resolved by careful use of relative and absolute units of measurement. 
#### Hamburger Menu           
[Back to Top](#contents "Contents")
For very small screens, the navbar menu items would not fit.
The solution in principle was provided by my mentor Martina Terlevic: to use 'hamburger menus'. The initial code for this solution was copied from https://codepen.io/alvarotrigo/pen/XWejzjR and then modified for this project.
#### Navbar height for mid-range screens           
[Back to Top](#contents "Contents")
For screens in the tablet or mid-range screens, the text in the navbar would jump to two lines at the lower end of the range.
This was resolved by having an upper and lower midrange category of media query with adjusted css in the lower category to double the height of the navbar to accommodate the 2 lines for menu text. All related section css dimensions and offsets in this category were adjusted.
#### Responsible Fire Section           
[Back to Top](#contents "Contents")
Figure caption bleeds into Stay in touch section
Class content-right-wrapper was adjusted to reduce height of image/figure.
#### Phones in Landcape           
[Back to Top](#contents "Contents")
Formatting does not currently work. This is now an unresovled 'known issue'.
### Validator Testing           
[Back to Top](#contents "Contents")
#### Lighthouse
The following errors were revealed through Lighhouse testing.
+ Background and foreground colors do not have a sufficient contrast ratio.
    + The call-to-action colours were changed  to resolve this issue.
+ Failing Elements Example: several errors of this kind were found.
    h2.call-to-action
    + html structure was changed to remove these errors.
+ Form elements do not have associated labels:
    + Failing Elements: input
    + Labels were given to inputs to resolve this issue.
#### W3C CSS Validator           
[Back to Top](#contents "Contents")
+ 153 Value Error : display flexbox is not a display value : flexbox
    + Several errors of this kind were found.
    + replace flexbox with : flex block
+ There were multiple examples of the following error:
    + The solution was to use aria-labelledby in the parent element.

    area-label="This link takes you to the section called Light a Fire"
    + Error: Attribute area-label not allowed on element a at this point.
    From line 38, column 26; to line 38, column 113
```
    <a href="#tools" area-label="This link takes you to the Tools for Fire Lighting section">Tools<
```

# Credits           
[Back to Top](#contents "Contents")
## Content
+ Whilst the content is mine, the influence of Ray Mears is gratefully acknowledged.
His Bushcraft sight can by found [here](https://www.raymears.com/).
+ Firewood Lay by Connor Fitzgerald https://www.cabinlife.com/articles/the-5-best-campfire-lays-and-how-to-build-them).
+ The Complete Guide to Battening https://morethanjustsurviving.com/batoning/
+ Ray Mears Bushcraft Shop https://www.raymears.com/Bushcraft_Products/
+ The Countryside Code https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/1052574/Countryside_Code_A5.pdf
+ UK Law: Firelighting https://www.gov.uk/government/publications/the-countryside-code\
+ Ray Mears essential Bushcraft https://www.raymears.com/Bushcraft_Product/164-Ray-Mears-Essential-Bushcraft-Signed-Copy/
## Media           
[Back to Top](#contents "Contents")
### The following images were used from the Pexels website:
+ https://www.pexels.com/photo/two-women-sitting-on-ground-near-bonfire-344102/
+ https://www.pexels.com/photo/burning-wood-on-fire-pit-4316833/
+ https://www.pexels.com/photo/funny-kid-with-firewood-walking-in-yard-3849955/
+ https://www.pexels.com/photo/person-curving-wood-167708/
+ https://www.pexels.com/photo/
+ people-sitting-in-front-of-bonfire-in-desert-during-nighttime-1703314/
+ pexels-ivan-samkov-9630140
### The following images were used from other sites
+ https://morethanjustsurviving.com/batoning/
+ https://www.cabinlife.com/articles/the-5-best-campfire-lays-and-how-to-build-them
### The following images were used from the Ray Mears Bushcraft Shop
+ https://www.raymears.com/Bushcraft_Product/952-Morakniv-Companion-Heavy-Duty-MG-Knife/
+ https://www.raymears.com/Bushcraft_Product/76-Ray-Mears-Fire-Stick/
+ https://www.raymears.com/Bushcraft_Product/73-Bahco-Laplander-Folding-Saw/
## Code           
[Back to Top](#contents "Contents")
All copied and modified code is clearly marked with comments in both html and css files.
+ Footer code was copied and modified from the Love Running Project: Code Institute
+ Hamburger Menu code was copied and modified from https://codepen.io/alvarotrigo/pen/XWejzjR 
+ Lightfire aside Contents link position offset adjusting for navbar.
Solution from Hrvoje Miljak - Stack Overflow
## Feedback           
[Back to Top](#contents "Contents")
Feedback was gratefully received and played a significant part in the development of this project. Contributors were:
+ Martina Terlevic: Mentor - Code Institute
+ Sarah
+ Emily
+ Annabel

Mike Rae
28/05/2022
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
+ [Testing: And Related Bug Issues](#testing-and-related-bugs "Testing and Related Bugs")
    + Human Testing
    + Validator Testing
    + Lighthouse

+ [Unfixed Bugs](#unfixed-bugs "Unfixed Bugs")
+ [Development and Deployment](#development-and-deployment "Development and Deployment")
+ [Credits](#credits "Credits")
    - Content
    - Media
    - Code
    - Feedback
+ [External Resources](#external-resources "External Resources")

# User Experience Design

## Strategy
Stakeholder Stories

### Users
Users want to find information on how to light a fire.
They want to develop their firelighting skills, to use their firelighting skills, to meet with like-minded people and enjoy using their skills together.
### Site Owner
The Site Owner would like to provide and promote responsible firelighting knowledge, to promote training in firelighting techniques and to promote enjoyment of and respect for the outdoors.

### Wider Members of the Community
Members of the Wider Community would like to prevent damage to land and property, and to promote responsible enjoyment of the countryside.

## Scope
Here is a summary of the needs and requirements of the stakeholders. Priority was given to features which were implementable within the timeframe of the project, and using technology available. Some features were noted for future release.
![UXD Scope](/assets/images/uxd-scope.png)

## Structure
This flow chart describes the information flow of the site.
![UXD Structure](/assets/images/uxd-structure.png)

## Skeleton
Wireframes were created in the Balsamiq Wireframes app. These represent the project design intentions. The current build was modified by build experience, feedback from testers, my Mentor and the results of other testing procedures.
### Enjoy Fire! Section (Home Section)
![Enjoy Fire! Section](/assets/images/enjoyfire-home-wireframe-uxd.png)
This 'home' section strongly suggests the enjoyment of a camp fire with friends. It offers an easily accessible summery of the site whilst progressively revealing more content. Each of the four areas are linked to the navbar, and also to the associated text titles. The pop-out on-hover progressive reveal design was abandoned in this version for time and complexity reasons.
In the build for smaller screens, the links in the nav bar were replaced by a 'hamburger menu'.
### Light a Fire! Section
![Light a  Fire! Section](/assets/images/lightfire-wireframe-uxd.png)
This section contains a scrolling article containing tips on Lighting a Fire. It also contains a contents sidebar which remains visible whist the article contents are scrolled. The contents items are linked to the relevant article sections. For smaller screens and tablets, the sidebar was made invisible.
### Tools for Firelighting Section
![Tools for Firelighting](/assets/images/tools-wireframe-uxd.png)
The three recommended tools are displayed with a short description. A button inviting the purchase of each tool opens an external link to the Ray Mears Bushcraft shop where the tools can be purchased.
### Responsible Firelighting Section
![Responsible Firelighting](/assets/images/responsiblefire-wireframe-uxd.png)
This section reinforces the need for and benefits of responsible firelighting using imagery and a popular quotation from Chief Seattle. It provides external links to further information.
### Stay In Touch Section
![Stay in Touch](/assets/images/stayintouch-wireframe-uxd.png)
An image celebrating the social benefits of camp-fire camaraderie compliments a form inviting the user to submit relevant information enabling them to stay in touch with the site owners. This is a dummy form since this is a static website. A server response is simulated by the 'Stay In Touch' button being linked to a second response.html page shown below.
### Response Page
![Response Page](/assets/images/response-wireframe-uxd.png)
A simple response 'thank you' is offered to inform the user that their submission has been received. The user may return to any section of the site using the same navbar elements common throughout the site. 

## Surface
### Colour Palette
![Colour Pallet](/assets/images/colour-pallet.png)
The Colour Pallet was generated at the [Coolers website](https://coolors.co/palette/D4C2B6-C38E71-BD9792-60414A) using the hero (Enjoy Fire) image.

NB: There is doubt that these provide sufficient contrast and accent  To be reviewed in testing.

This indeed proved to be the case. The colour 'cornsilk' rgb(255,248,220) was used in 'call-to-action' and responsive elements to provide additional contrast to  the pallet.

![Cornsilk used in resposive hover action](/assets/images/cornsilk.jpeg)

### Typography
Fonts were chosen from the [Google Fonts website](https://fonts.google.com/).
The initial choice of fonts were EB Garamond for body text and Mitr for headings.
The script for these fonts was:
@import url('https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;0,700;1,400&family=Mitr:wght@400;500&display=swap');

After feedback, it was decided to change the body font to 'Roboto'.
The final font script used in css was:
@import url('https://fonts.googleapis.com/css2?family=Mitr:wght@400;500&family=Roboto&display=swap');

### Icons
Icons were chosen from the [FontAwesome website](https://fontawesome.com/) using the following script:
 <script src="https://kit.fontawesome.com/7299876a46.js" crossorigin="anonymous"></script>

### Images
Most mages were downloaded from the [Pexels Free Photos website](https://www.pexels.com/search/free/) under the appropriate creative commons copyright licence.

Each photographer was credited using the Figcaption element.
Where a photo was downloaded from a source other than Pexels, the source was indicated in the relevant figcaption element.

The one image not overtly credited was the hero image in the Enjoy Fire Section:
![Enjoy Fire! Hero Image](/assets/images/hero.jpg)
This photo (No. 344102) was taken by Oleksandr Pidvalnyi and downloaded from the Pexels website  and used under their creative commons licence.

## Implemented Features
### Navigation Bar and Footer
#### Navigation Bar
A navigation bar is fixed to the top of every display screen. This has links to each of the site sections on the right of the navigation bar. The Logo on the left of the navigation bar is linked to the Enjoy Fire! section (home section).

![Navigation Bar](/assets/images/navbar.png)

For smaller screens where there was insufficient space to display the links, the commonly accepted convention of a  'hamburger menu' was used to reveal the navigation links. The core code for the 'hamburger menu' was copied from https://codepen.io/alvarotrigo/pen/XWejzjR and modified for this project.

![Hamburger Menu: closed](/assets/images/hamburgermenu-closed.png)

![Hamburger Menu: open](/assets/images/hamburgermenu-open.png)

The footer is visible at the bottom of each of the two pages i.e. the main content page index.html and the form response page response.html. It contains external links to social media sites. The code for the footer was copied from the Code Institute 'Love Running' module and modified for this project.
#### Footer

![Footer](/assets/images/footer.png)

Each navigation and footer element is responsive, i.e. when hovered, the text changes colour to indicate a link.
The style of the footer and navbar were made consistent using the class '.bar'.
### Semantic HTML
The following semantic html elements were used to facilitate engagement with the site for visually impaired users:
+ Sections: Each of the sections in the site are enclosed in this element. The section h2 element gives the section semantic content.
+ Nav: The elements enclosed in the navbar provide semantic content.
+ Footer: The elements enclosed in the footer provide semantic content.
+ Article: The content of the Light a Fire article are enclosed by this element ant can be understood across the web as a stand-alone unit.
+ Aside: The navigation content links in the Light a Fire section are enclosed in the aside element.
+ Figure: Almost all images are enclosed in the figure element.
+ Figcaption: Where the figure element was used, a figcaption element was used to describe the image.
### Aria Provision
To assist visually impaired users, use of aria-labelledby and aria-label elements were used to semantically describe elements whos semantic meaning might otherwise be unclear.
### Progressive Reveal
Each section partially reveals the header of the next section, inviting the user to scroll down and explore the site further.
### Enjoy Fire Section
This 'home' or 'landing' section is the first thing a user will see when arriving at the site. It promotes a warm, welcoming, social feeling. The user is progressively drawn into the content of the site using four responsive 'call to action' buttons which briefly describe the contents of the section of the site. These buttons are linked to each of the site sections. At the bottom of the viewed area, the header of the next section is partially revealed.

![Enjoy Fire Progressive Reveal](/assets/images/enjoy-fire-progressive-reveal.png)

### Light a Fire Section
Tips for lighting a fire are found within the artcle in this section.
Further information is referenced using clearly marked external links.

![Light a Fire External links](/assets/images/lightfire-external-links.png)

The sections of the articicle were displayed using the Grid Display attribute.
For larger screens, three columns were used, for medium screens two columns, and for smaller screens, one column. This was achieved using the relevant media query sections in the css file.
The aside containing the article section buttons is constantly in-view whilst the article is being scrolled through. This was acheived using the 'sticky' display attribute.

![Light a Fire Aside](/assets/images/lightfire-aside.png)

The contents aside is only available for larger screens. The code to not display the aside was used within media querys in the css for smaller screens.

The individual sections of this article are linked to call-to-action buttons in the aside. When clicked, the section scrolls to the appropriate section.

![Light a Fire Aside offset](/assets/images/lightfire-contents-links-header-offset.png)

### Tools for Lighting Fire Section
In this section, the user is introduced to three entry level fire-lighting tools. For each tool there is an image, a brief description and a call-to-action button inviting the user to buy a tool. The buttons are linked to the relevant areas in the external site for Ray Mears Bushcraft shop, where a fuller description of each tool can be found. If desired, the user may purchase each tool from the external shop. Whilst I have no affiliation to Ray Mears Bushcraft or his shop, I can recommend the site, the  shop and the tools.

For larger screens, three tools are displayed side by side. For medium screens, 
two are displayed, and for small screens one tool is displayed.

![Tools for firelighting: Large Screens](/assets/images/tools-large.png)

![Tools for firelighting: Medium Screens](/assets/images/tools-medium.png)

![Tools for firelighting: Small Screens](/assets/images/tools-small.png)

### Responsible Firelighting Section
The main emotional thrust of this section is to invoke a sense that lighting fires responsibly is to be encouraged. This is achieved through the use of a suitable image and the familiar and helpful quotation from Chief Seattle to "Take only Memories, Leave only Footprints".
Anyone how has tried to achieve this whilst enjoying the countryside will quickly realise that significant thought and effort is required for this to be accomplished. Anyone who has encountered the devastation caused by thoughtless behaviour will readily warm to Chief Seattle's sentiments.
The three call-to-action buttons take the user to external sits where more in depth information may be found.

![Responsible Fire Lighting](/assets/images/responsible-firelighting.png)

### Stay In Touch Section
In this section the user is invited to join our community, initially by indicating an interest in staying in touch. There is an optional oportunty to communicate the user's bushcraft interests and sign up for a news letter and information about upcoming events.
Basic contact information is required to be submitted. If a name input field is not filled in, or if a non-valid email address is entered the user is prompted to properly fill in these fields before the form will be submited.

The name and email fields are responsive in that the background colour changes on-hover.
The submit button is responsive consisitent with all the other call-to-action buttons on the site.

Since this project is limited to a static website it is beyond the scope of the project to handle any form data. A simulated server response is created by linking the submit button to a 'Response page' in which the user is thanked for their interaction.

The Stay In Touch section is the last on index.html so this section displays the footer at the bottom.

The section for large screens is here:

![Stay In Touch](/assets/images/stay-in-touch-large.png)

For small screens, the user scrolls to the bottom of the section to submit the completed form:

![Stay In Touch Upper](/assets/images/stay-in-touch-small1.png)

![Stay In Touch Lower](/assets/images/stay-in-touch-small2.png)


### Response Page
This as a separate html document and simulates a response from a server upon receipt of data from the form on the Stay In Touch Section.
The look and feel are identical to the Stay In Touch Section. All the navigation links and footer links are consistent with the rest of the site so that the user may intuitively choose to return to any part of the site.

![Response Page](/assets/images/response.png)

## Future Development
### Club Membership Area
Users can become members, and gain secure access to a members area in the site through a Django based authentication.
Here, there is scope for blog posts and event advertising.
### Camp Fire Cookout Events
Social Gatherings advertised on the site, and through the news letter will be held from time to time. Once there is server and database support, users may sign up for and attend these events. This was included in the scope analysis but excluded in the first release.
### Training Meet-ups
Interest in particular skill development can be gauges through blog posts and signup forms.
These events can then be scheduled and advertised, and members can sign up for them. This was included in the scope analysis but excluded in the first release.
### Community Gatherings Gallery
Members may post and display their photos of gatherings held. This was included in the scope analysis but excluded in the first release.
### Bug Fixes
Currently there are one or two bugs which have yet to be corrected. See the bug section. These will be corrected in a future release.

## Technologies Used
+ HTML5
+ CSS3

## Testing and Related Bugs
### Human Testing
#### Links
+ All external links were tested manually to verify that they were live and that they all opened in a new browser tab or window.
No issues were found.
+ All internal links were tested manually.
    + Initially, the top of a linked section was obscured by the fixed nav bar. This was resolved by applying an appropriate offset to the target equivalent to the height off the nav bar. This varies with screen size, so offsets were applied within media queries.
    + After testing and correction, no issues were found.




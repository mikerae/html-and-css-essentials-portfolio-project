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
+ [Future Development](#future-development "Future Development")
+ [Technologies Used](#technologies-used "Technologies Used")
+ [Testing](#testing "Testing")
    + Validator Testing
    + Lighthouse
    + Human Testing
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
![Cornsilk used in resposive hover action](/assets/images/cornsilk.heic)
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
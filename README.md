# Student Resource and Annotated Tips Tool

This tool is intended for students to access curated material and daily tips. The curator can easily update the content.

## UX/UXD Process

## Project Goal

Create a minimal viable product (MVP) that is useful, usable and valuable

## Strategy Plane - User Needs and Business Objective

A minimal viable product that works well on a mobile device and desktop for students. Single page with topic sections selected for better user experience.

The content is easy to update by the curator.

Utilize the Bootstrap framework for faster development and easy code maintenance.

- [Conducted stakeholder interview using Slack CI #Pair Programming channel](https://code-institute-room.slack.com/archives/CJPLQ7D2P/p1586729359025700)
- Confirmation of the feasibility of a Minimal Viable Product (MVP)

- Consulted mentor regarding general components for MVP for essential features using Bootstrap
  - Sticky Navbar
  - Scrollspy
  - Carousel
  - Album
  - Modal

- Business Goals and objectives
  - FAQ resource for students
  - Tool for the curator to upload answers to FAQ
  - Easy to update and maintain
  - Timely and effective delivery of information to students and minimize FAQ activity in Slack and Tutor channels
  - Information content
  - Answers to FAQ by topic and category

## Scope Plane

Build a single-page web site to simplify and provide a positive user experience.

The content consists of answers to FAQs and important concepts categorized by topic.

Content is accessed using buttons and hyperlinks to access curated material and videos.

Quick start tips will include annotated screen capture and step by step instruction.

A feedback form to collect rating by topic and user comments.

- In-Scope Features
  - Onepage website with multiple sections
  - Cards containing information and buttons to access documents and videos for each
  - Carousel with screen images for quick start tips
  - Scrollspy to provide step by step instructions
  - Modal Feedback Form with alert on submit.

- Personas and User Stories
  - Student wants to understand the workflow for a project
  - Student wants information related to concepts and how to use tools
  - Student wants quick start information on how to perform a task
  - Student wants access to daily tips
  - Student wants to provide feedback by rating content by topic and free form comment
  - Curator wants to update content for web page easily

- Adopt agile iterative stakeholder feedback and approval approach
- Minimize documentation by developing a proof of concept using wireframe published on Git Pages. Here is the link [Digital prototype wireframe iteration with Proof of Concept exploring different compoments](https://ngiappuoykoh.github.io/MS1PrototypeWireframe/)
- Use a digital prototype for iterative stakeholder and development team review

- Future Features
  - Chatbot
  - Search feature
  - Automate cycling FAQ times weekly
  - Track user usage
  - Track user rating and comments
  - Improve content to address FAQ
  - Replace steps with Animation
  - Decision tree or simple AI to keep, remove or modify the content

## Structure Plane

Goal: Traceability of components to business requirements

### Functional Specifications and Content Requirements

- Draft Balsamiq wireframe for desktop and mobile
- Research top FAQ based on Slack activity
- Content Categorization by Course Module, Tools and Concepts
- Sample Content Types
  - Annotated Images
  - Slack Pinned messages
  - Slack downloadable pdfs
  - External URL links videos and resources
- Research UX approach on how to ensure good user experience with web page navigation
  - Guide navigation by organizing the flow of information
  - Quick access using menu and mouse click based on FAQ
- Information Design
  - Topic/category (Modules, Tools and Concept)
  - Select content to align with when FAQ occurs during the  learning journey (Identify specific FAQs)
  - How-to steps in sequence (carousel)
  - Single visual how to image (modal window)
  - Document download
  - Link to slack messages and URL
- Provide the opportunity for user feedback

## Skeleton Plane

Interface and Information Design Details

- Proof of concept implementing wireframe using Bootstrap on gitpage
- Planning call with Mentor to review Proof of Concept and wireframes
- Wireframes
  - [Initial wireframe for iPhone](wireframes\InitialWireframeiPhone.png)
  - [Initial wireframe for desktop](wireframes\InitialWireframeDesktop.png)
  - [Digital prototype wireframe iteration with Proof of Concept exploring different compoments](https://github.com/NgiapPuoyKoh/MS1PrototyeWireframe)

- Revise Scope, components and prioritize features
  - Sticky collapsable Navbar with a scrollspy for mobile and desktop
  - Responsive containers with cards that will stack for mobile devices
  - Carousel for sliding image display for quick start
  - Scrollspy to provide step by step instructions

- [Favicon Font Awesome png converter](https://gauger.io/fonticon/)

- [Sample Icons from Fontawesome gallery](https://fontawesome.com/icons?d=gallery&m=free)
  - [slack hash](https://fontawesome.com/icons/slack-hash?style=brands)
  - [slack](https://fontawesome.com/icons/slack?style=brands)
  - [git](https://fontawesome.com/icons/git?style=brands)
  - [copyright](https://fontawesome.com/icons/copyright?style=regular)
  - [comment](https://fontawesome.com/icons/comment-dots?style=regular)
  - [book-reader](https://fontawesome.com/icons/book-reader?style=solid)
  - [bootstrap](https://fontawesome.com/icons/bootstrap?style=brands)
  - [chalkboard](https://fontawesome.com/icons/chalkboard?style=solid)
  - [chalkboard with teacher](https://fontawesome.com/icons/chalkboard-teacher?style=solid)
  - [map](https://fontawesome.com/icons/map?style=regular)

- Card Samples
  - [Cards](wireframes/uipatterns/Cards.jpg)
  - [Cards Text](wireframes/uipatterns/CardsText.jpg)
  - [Card Headline Thumbnails](wireframes/uipatterns/HeadlineThumbnailsGallery.jpg)
  - [Card Silhouette](wireframes/uipatterns/silhouetteView.jpg)

## Surface Plane - Visual Design

Goal: Clean, Minimalist and Effective intended primarily for use on a mobile device

- Single-page website with multiple sections

- Typography
  - Font - GoogleFont Exo and Roboto
  - Font Awesome Icons

- Color Scheme
  - #007BFF Dodger Blue
  - #444655 Blue Zodiac
  - #A8AABC Mischka
  - #F12E5E Radical Red

- Sticky Navbar with scrollspy
  - Collapse to a button for small devices
  
- Sections
  - Container of 3-4 cards
  - Card with buttons

- Carousel
  - Slider with annotated Screen Capture
  - Magnify screen capture using media queries

- Scrollspy
  - Summary steps
  - Step details

- Modal
  - Button to open Modal Feedback
  - Radio options for rating
  - Textarea for comment
  - Alert on Submit
  - Close Modal Button

### Bootstrap Components Used

- [Bootstrap Grid](https://getbootstrap.com/docs/4.0/layout/grid/)

- [Navbar with scrollspy](https://getbootstrap.com/docs/4.0/components/navbar/)

- [Cards](https://getbootstrap.com/docs/4.0/components/card/)

- [Buttons with links to vidoes and documents](https://getbootstrap.com/docs/4.0/components/buttons/)

- [Carousel](https://getbootstrap.com/docs/4.0/components/carousel/)

- [Scrollspy List](https://getbootstrap.com/docs/4.0/components/scrollspy/)

- [Modal with Image Magnification](https://getbootstrap.com/docs/4.0/components/modal/)

- [Button invoked Modal Feedback Form with radio oprtions](https://getbootstrap.com/docs/4.0/components/forms/)
- [Text links to resources](https://getbootstrap.com/docs/4.0/components/badge/#links)

### HTML Components

- Alerts
- Favicon

## Features

### Feature 1

Sticky Navbar with collapsable menu button for mobile devices to allow a user to navigate to different sections of the web page

### Feature 2

Cards in organized by sections with high-level descriptions and buttons links to download documents or access videos

### Feature 3

Carousel with sliding screen capture to provide quick-start information on how to perform a task

### Feature 4

Scrollspy to list steps and scrollable panel for details for each step

### Feature 5

Modal Feedback form with radio options and text area will trigger an alert acknowledgment. Implement form validation for required radio options selection on submit.

### Feature 6

Applied ARIA Labels to elements for screenreader processing

## Features left to implement

- Improve UI design
- Improve page identity

## Technologies Used

- HTML
- CSS
- Bootstrap
- JQuery
- popperJS
- Font Awesome
- Google Fonts

- Other Tools
  - Chrome Dev Tool
  - GitPod
  - Visual Studio Code (VSCode)
  - Balsamiq
  - SnagIt

- Validators
  - [CSS Beautifier](https://www.freeformatter.com/css-beautifier.html)

  - [WCAG Color contrast checker](https://chrome.google.com/webstore/detail/wcag-color-contrast-check/plnahcmalebffmaghcpcmpaciebdhgdf?hl=en)

  - [Responsive Design Checker](http://ami.responsivedesign.is/)

  - Chrome Dev Tool
    - Accessibility Audit
    - JS loaded using dev tool/network

## Testing

### Use Cases Test Scenarios

#### Navbar

- User scrolls down the page the Navbar sticks to the top of the page

- User clicks on the menu bar links to navigate to the target sections on the page

- Navbar menus will collapse to a button on small devices

- User clicks on the navbar button to render an item menu

- User clicks on an item on the button menu to navigate to the target sections on the page

- User clicks on all card buttons to access all links to documents and videos

#### Carousel

- User is able to view annotated screen capture on all devices displayed on the Carousel

- User clicks on Previous or Next buttons on the carousel to navigate to the respective annotated screen capture

#### Scrollspy

- Scrollspy for daily tips
  - Clicking on the scrollspy item will display the corresponding item details on the scroll panel

#### Modal Feedback Form

- User click on Button to render Modal
- User clicks on Close to close Modal form
- User clicks on Submit buttons a Thank You alert will render
- User clicks on OK on alert to close the window
- User is able to select a single radio button for each radio group
- User is able to enter free form comment
- User click on Submit button to trigger a thank you acknowledgment alert
- User fails to select required radio buttons and clicks submit button a message will render to notify that selection a radio is required
- User selects all required radio options without entering a comment and clicks on submit button no messages will render

#### Validation

- HTML [W3C Makeup Validation Service](https://validator.w3.org)
  - BUG: stray footer reported for body reported because of existing modal window footer

- [CSS W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

- [CSS Beautifier](https://www.freeformatter.com/css-beautifier.html#ad-output)

- [Autoprefixer CSS online](https://autoprefixer.github.io/)

- [WCAG Color contrast checker](https://chrome.google.com/webstore/detail/wcag-color-contrast-check/plnahcmalebffmaghcpcmpaciebdhgdf?hl=en)

- [Markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

### Issues Resolved

- Maintain the same height for cards responsiveness medium devices small card sizes in container columns are not the same height

- Carousel slider skippingdue to different image height and size

- Resolve alt tages for ARIA screenreader audit

- [Form Validation require selction of radio items](https://getbootstrap.com/docs/4.0/components/forms/#validation)

- Implement media queries for scrollspy scrolable panel height

- Upgrade to Bootstrap 4.5 form radio item columns fail to be responsive
  - BUG: Modal Window responsiveness broke requiring forced ```<div class="col-xs-6 col-sm-4">``` and class to adjust stacking or radio items on form for smaller devices

### Open Issues

- Navbar scrollspy does not work on iPhone6S. The alignment is below the location of section item ids.
  - BUG: Known Issue with iPhone and iPad [Issue with fixed bootstrap navbar on mobile](https://www.freecodecamp.org/forum/t/issue-with-fixed-bootstrap-navbar-on-mobile/17533)

- Modal Feeback Form
  - BUG: Form data does not clear after closing modal window unless the browser session is refreshed

- Improvement of UI/UX design. A creative challenged individual requires the investment of a significant amount of time and learning with practice to achieve minimal competency. The CI Full Stack Web Development program does provide suport for UI and UX design.

### Devices Used

- iPhone 6S
- Lenovo laptop L421

### Browser Used

- Chrome
  - Chrome emulation for all responsive sized
  - Chrome device emulations for available devices
  - Checked margins and padding of the container (sections) to ensure the content within it did not look disproportionate on various screen sizes, individually smaller devices.

### Future Goals

- For smaller device swap Carousel with Modal to include magnified images
- Scripts to Automated content updates
- Scripts to automate daily Quickstart
- Use APIs to track usage based on clickstream data
- API to Track Slack frequently FAQ by module
- API to extract Slack Pinned messages
- Improve accessibility using ARIA best practices (contrast ratio)
- [Aria-labels](https://www.aditus.io/aria/aria-label/)
- Use bot to collect feedback

## Deployment

GitHub Pages was used to deploy the project web page.

### Cloning a repository

1. Navigate to [https://github.com/NgiapPuoyKoh/student-resource-tool](https://github.com/NgiapPuoyKoh/student-resource-tool)

1. Click Clone or download

1. Clone HTTPS [https://github.com/NgiapPuoyKoh/student-resource-tool](https://github.com/NgiapPuoyKoh/student-resource-tool)

1. Open git bash(Windows) or Terminal(macOS and Linux)

1. Change the current working directory to the desired location of the target cloned directory.

1. Type git clone [https://github.com/NgiapPuoyKoh/student-resource-tool.git](https://github.com/NgiapPuoyKoh/student-resource-tool.git)

1. Press enter

### Configure GitHub Pages site

1. Navigate to the Github remote repository [https://github.com/NgiapPuoyKoh/student-resource-tool](https://github.com/NgiapPuoyKoh/student-resource-tool)

1. Click on settings

1. Scroll down the page to GITHUB Pages section

1. For the Source select "master branch"

1. Wait a few minutes and then access the completed project using this link [https://ngiappuoykoh.github.io/student-resource-tool/](https://ngiappuoykoh.github.io/student-resource-tool/)

## Credits

### Content

- Anna Greaves a notable active Tutor on CI Slack and author of MS1 Project documents, videos and pinned messages
- Igor Basuga and Anthony O'Brien contributors to slack pinned items
- Publicly available videos and documentation on the internet
- [Favicon fontawesome generator](https://gauger.io/fonticon/)
- [Favicon Generator](https://favicon.io/)

### Acknowledgment

- [**Guido Cecilio**](https://www.linkedin.com/in/guidocecilio/) for mentor guidance
- [**Anna Greaves**](https://www.linkedin.com/in/anna-greaves/) providing helpful material to navigate through my MS1 project
- Code Institute Slack Community members who participated as the project stakeholders on the #pair programming channel and peer review feedback
  - [**Simem Daehlin**](https://www.linkedin.com/in/simendaehlin/)
  - [**Igor Basuga**](https://www.linkedin.com/in/igor-basuga-b2a123111/)
  - [**Anthony O'Brien**](https://www.linkedin.com/in/anthony-o-%E2%80%8B-brien-8324a5139/)
  - [**Kasia Bee Zee**](https://github.com/bezebee)
- Support from the Code Institute tutors, CI Staff and Slack community

## References

### Bootstrap

- [How the Bootstrap 4 Grid Works](https://uxplanet.org/how-the-bootstrap-4-grid-works-a1b04703a3b7)
- [Change arrow colors in Bootstraps carousel](https://stackoverflow.com/questions/46249541/change-arrow-colors-in-bootstraps-carousel)

### Markdown

- [Markdown Crash Course](https://www.youtube.com/watch?v=HUBNt18RFbo)

### UX Design

- [UI Patterns](https://ui-patterns.com/patterns)
- [UX Apprentice](https://www.uxapprentice.com/)
- [The 2020 UI Design Fundamentals Crash Course](https://www.youtube.com/watch?v=tRpoI6vkqLs)
- [My Color Space](https://mycolor.space/)

### Wireframe Reference

- [How to Create Your First Wireframe](https://www.youtube.com/watch?v=KdfO_e0yK-g)
- [Rapid Wireframing:Finding the Right Product Design](https://www.skillshare.com/classes/Rapid-Wireframing-Finding-the-Right-Product-Design/1947996659)

- [Udemy Wireframing with Balsamiq Mockups](https://www.udemy.com/course/wireframing-with-balsamiq-mockups/learn/lecture/3993718)

### Stackoverflow

- [Twitter Bootstrap carousel different height images cause bouncing arrows](https://stackoverflow.com/questions/13391566/twitter-bootstrap-carousel-different-height-images-cause-bouncing-arrows)
- [Stretch child div height to fill parent that has dynamic height](https://stackoverflow.com/questions/17900122/stretch-child-div-height-to-fill-parent-that-has-dynamic-height)

### Dev Tool

- [How to find computed size of any element in Chrome Developer Tools?](https://stackoverflow.com/questions/10234154/how-to-find-computed-size-of-any-element-in-chrome-developer-tools)
- [Chrome Developer Tools](https://youtu.be/x4q86IjJFag)

### Disclaimer

This is for educational use

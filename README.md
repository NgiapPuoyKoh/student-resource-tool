# Student Resource and Annotated Tips Tool

This tool is intended for students to access curated material and daily tips. The curator can easily update the content.

## Strategy

A minimal viable product that works well on a mobile device and desktop for students. Single page with topic sections selected for better user experience.

The content is easy to update by the curator. Utilize the Bootstrap 4 framework for faster development and easy code maintenance.

## Scope

A single-page web site will simplify and provide a positive user experience.

The content consists of answers to FAQs and important concepts categorized by topic.

Content is accessed using buttons and hyperlinks to access curated material and videos.

Quick start tips will include annotated screen capture and step by step instruction.

A feedback form will collect ratings for topic content and user comment.

## Skeleton

- [Initial wireframe for iPhone](assets\wireframes\InitialWireframeiPhone.png)
- [Initial wireframe for desktop](assets\wireframes\InitialWireframeDesktop.png)
- [Digital protoptype wireframe iteration with Proof of Concept exploring different compoments](https://github.com/NgiapPuoyKoh/MS1PrototyeWireframe)

## Surface

- Single-page website
  - UX Colors scheme - Greyscale
  - Typography

Detail UX design document is available [here](MS1UXD.md)

## Technologies

- HTML
- CSS
- Bootstrap 4

- Other Tools
  - Balsamiq
  - SnagIt

## Features

- Information Design Features:
  - Workflow for Project
  - Concepts
  - Tools
  - Daily Tips
    - Carousel with annotated screen images
    - Scrollspy to provide step by step instructions
  - Modal Feedback Form
  - Fontawesome Icon
  - Annotated Screen Capture
  - Single Page with multiple sections

- Bootstrap 4 Components Used:
  - [Bootstrap Grid](https://getbootstrap.com/docs/4.0/layout/grid/)
  - [Navbar with scrollspy](https://getbootstrap.com/docs/4.0/components/navbar/)
  - [Cards](https://getbootstrap.com/docs/4.0/components/card/)
  - [Buttons with links to vidoesand documents](https://getbootstrap.com/docs/4.0/components/buttons/)
  - [Carousel](https://getbootstrap.com/docs/4.0/components/carousel/)
  - [Scrollspy List](https://getbootstrap.com/docs/4.0/components/scrollspy/)
  - [Modal with Image Magnification](https://getbootstrap.com/docs/4.0/components/modal/)
  - [Button invoked Modal Feedback Form](https://getbootstrap.com/docs/4.0/components/forms/)
  - [Text links to resources](https://getbootstrap.com/docs/4.0/components/badge/#links)

- Features left to implement
  - Improve responsiveness for medium size devices
  - Javascript to collect feedback information

## Testing

### Devices Used

- iPhone 6S
- Lenovo laptop L421

### Browsers Used

- Chrome
  - Checked margins and padding of the container (sections) to ensure the content within it did not look disproportionate on various screen sizes, individually smaller devices.
  - Chrome device emulations for available devices

### Use Cases

- Review workflow for a milestone project
- Confirm links are working for Concepts and Tool sections
- Carousel
- Daly tip Scrollspy
- Modal feedback form renders and closes

### Validation

- HTML [W3C Makeup Validation Service](https://validator.w3.org)
  - BUG: stray footer reported  for body reported because of existing modal window footer.
- [CSS W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
- [Autoprefixer CSS online](https://autoprefixer.github.io/)
- [Markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- Accessibility Audit
  - BUG: Contrast ratio needs improvement

### Issues/Bugs

- Navbar scroll spy does not work on iPhone6S. The alignment is below the location of section item ids.
  - BUG: Known Issue with iPhone and iPad [Issue with fixed bootstrap navbar on mobile](https://www.freecodecamp.org/forum/t/issue-with-fixed-bootstrap-navbar-on-mobile/17533)
- Modal Feeback Form
  - BUG: Form data does not clear after closing modal window unless the browser session is refreshed
- Responsiveness medium devices small card sizes in container columns are not the same height
- Unintended image skip probably due to image sizing, overflow or unintended animation effect
- Styling of borders, cards, greyscale and typography needs improvement
- Resolve alt tages for ARIA screenreader audit
- Improve semantics for Search Engine Optimization (SEO)
- [Form Validation](https://getbootstrap.com/docs/4.0/components/forms/#validation)
- implement media queries for scrollspy item height

Detail Testing document is available [here](TESTING.md)

### Future Goals

- Scripts to Automated content updates
- Scripts to automate daily Quickstart
- Use APIs to track usage based on clickstream data
- API to Track Slack frequently FAQ by module
- API to extract Slack Pinned messages
- Improve accessibility using ARIA best practices (contrast ratio)
- Use bot for feedback with decision-tree or simple AI to keep, remove or modify the content

## Code Review Summary Checklist

- Bootstrap version is the same as the imported bootstrap HTML, CSS, JS scripts
- Fontawesome latest version
- Comments
- Title
- Article Semantic
- Header Callout - Purpose of the website
- Page Sections
- Aria Navigation to Modal window and images
- Image Alternates
- Styling
  - borders
  - typography e.g. block quote highlights importance to draw attention
  - button styles
  - margins e.g. mt-, my-, etc.
  - Javascript components
  - Javascript before the closing HTML tag
  - menu button, magnify
- JS loaded using dev tool/network

Reference: [HTML Semantics Cheatsheet](https://learn-the-web.algonquindesign.ca/topics/html-semantics-cheat-sheet/)

## Deployment

GitHub Pages was used to deploy the project web page.

### Cloning a repository

- Navigate to [https://github.com/NgiapPuoyKoh/student-resource-tool](https://github.com/NgiapPuoyKoh/student-resource-tool)
- Click Clone or download
- Clone HTTPS [https://github.com/NgiapPuoyKoh/student-resource-tool](https://github.com/NgiapPuoyKoh/student-resource-tool)
- Open git bash(Windows) or Terminal(macOS and Linux)
- Change the current working directory to the desired location of the target cloned directory.- Type git clone [https://github.com/NgiapPuoyKoh/student-resource-tool.git](https://github.com/NgiapPuoyKoh/student-resource-tool.git)
- Press enter

### Configure GitHub Pages site

- Navigate to the Github remote repository [https://github.com/NgiapPuoyKoh/student-resource-tool](https://github.com/NgiapPuoyKoh/student-resource-tool)
- Click on settings
- Scroll down the page to GITHUB Pages section
- For the Source select "master branch"
- Wait a few minutes and then access the completed project using this link [https://ngiappuoykoh.github.io/student-resource-tool/](https://ngiappuoykoh.github.io/student-resource-tool/)

## Credits

### Content

- Anna Greaves creator of videos and project resources on slack referenced
- Igor B and Anthony contributors to slack pinned items
- Publicly available videos and documentation on the internet
- [Favicon](https://icons8.com/icon/pack/free-icons/ios-glyphs)

### Acknowledgment

- Guido Cecilio for mentor guidance
- Slack Community members who participated as the project stakeholders on the #pair programming channel
  - Igor Basuga
  - Anthony O'Brien
  - Simem Daehlin
- Anna Greaves Active Tutor on CI Slack the author MS1 Project documents, videos and pinned messages
- Support from the CI Tutor and Slack community as a whole

## References

### Bootstrap

- [How the Bootstrap 4 Grid Works](https://uxplanet.org/how-the-bootstrap-4-grid-works-a1b04703a3b7)

### Markdown

- [Markdown Crash Course](https://www.youtube.com/watch?v=HUBNt18RFbo)

### UX Design

- [UI Patterns](https://ui-patterns.com/patterns)
- [UX Apprentice](https://www.uxapprentice.com/)
- [The 2020 UI Design Fundamentals Crash Course](https://www.youtube.com/watch?v=tRpoI6vkqLs)

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

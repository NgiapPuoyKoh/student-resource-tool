# Student Resource and Annotated Tips Tool

This tool is intended for students to access to curated material and daily tips. The curator can easily update the content.

## Strategy

A minimal viable product that works well on a mobile device and desktop for students. Single page with sections selected for better user experience.

The content is easy to update by the curator. Utilize Bootstrap 4 framework for faster development and easy code maintenance.

## Scope

Content answers to most FAQs on the community slack channel.The content is categorized using topics.

A single-page web site will simplify and provide a positive user experience.

Content is accessed using buttons and hyperlinks to access curated material and videos.

Quick start tips will include annotated screen capture and step by step instruction.

A feedback form will collect ratings for topic content and user comment.

## Skeleton

- [Initial wireframe for iPhone](assets\wireframes\InitialWireframeiPhone.png)
- [Initial wireframe for desktop](assets\wireframes\InitialWireframeDesktop.png)

- [Digital wireframe iteration with Proof of Concept exploring different compoments](https://github.com/NgiapPuoyKoh/playground)

## Surface

- Single-page website
  - UX Colors scheme - Greyscale with Red borders
  - Typography

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
    - Scrollspy to provide instrction by steps
  - Modal Feedback Form
  - Fontawesome Icon

- Bootstrap 4 Components Used:
  - Bootstrap Grid
  - Single Page with multiple sections
  - Navbar with scrollspy
  - Cards
  - Buttons with links to vidoes and documents
  - Text links to resources
  - Annotated Screen Capture
  - Carousel
  - Modal with Image Magnification
  - Button invoked Modal Feedback Form

- Features left to implement
  - Improve responsiveness for medium size devices
  - Javascript to collect feedback information

## Testing

Devices Used

- iPhone 6S
- Lenovo laptop L421

Browsers used

- Chrome

Use Cases

- Review workflow for a milestone project
- Confirm links are working for Concepts and Tool sections
- Carousel
- Daly tip Scrollspy
- Modal feedback form renders and closes

Validation

- [W3C Makeup Validation Service](https://validator.w3.org)
  - HTML
  - CSS
- [Markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

Issues/Bugs:

- Responsiveness medium devices small card sizes in container columns are not the same height
- Unintended image skip probably due to image sizing, overflow or unintended animation effect
- Styling of borders, cards, greyscale and typography needs improvement
- Navbar scrollspy does not work on iPhone6S it scrolls past where the item ids for the sections are placed
- ARIA screenreader and alt tags for links need to be resolved
- Semantic improvements for website Search Engine Optimization SEO

Future Goals

- Scripts to Automated content updates
- Scripts to automate daily Quickstart
- Use APIs to track usage based on clickstream data
- API to Track Slack frequently FAQ by module
- API to extract Slack Pinned messages
- Improve accessibility using ARIA best practices
- Use bot for feedback with decision-tree or simple AI to keep, remove or modify the content

## Code Review Summary Checklist

- Bootstrap version are the same for imported bootstrap HTML, CSS, JS
- Fontawesome latest version
- Comments
- Title
- Article Semantic
- Header Callout - purpose of the website
- Page Sections
- Aria Navigation to Modal window and images
- Image Alternates
- Styling
  - Borders
  - typography e.g. block quote (highlight important to draw attention)
  - button styles
  - margins e.g mt- my- etc
  - Javascript components
  - Javscript before the closing HTML tag
  - menu button, magnify
- js loaded using dev tool/network

## Deployment

GitHub Pages was used t0 deploy the project web page

Cloning a repository

- Navigate to [https://github.com/NgiapPuoyKoh/](https://github.com/NgiapPuoyKoh/)
- Click Clone or download
- Clone HTTPS [https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git](https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git)
- Open git bash
- Change current working directory to the location where you want the cloned directory to be made
- Type git clone [https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git](https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git)
- Press enter

Configure GitHub Pages site

- Navigate to the Github remote repository [https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project](https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project)
- Click on settings
- Scroll down the page to GITHUB Pages section
- For the Source select "master branch"
- Wait a few minutes and then access the completed project using this link [https://ngiappuoykoh.github.io/user-centric-frontend-milestone-project/
](https://ngiappuoykoh.github.io/user-centric-frontend-milestone-project/)

## Credits

Content

- Anna Greaves creator of videos and project resources on slack referenced
- Igor B and Anthony contributors to slack pinned items
- Publicly available videos and documentation on the internet

Acknowledgment

- Guido Cecilio for mentor guidance
- Slack Community members who participated as the project stakeholders on the# pair rogramming channel @igor B, @Anthony, @yoda
- Support from the community as a whole

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

### Disclaimer

This is for educational use

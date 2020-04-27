
# New Student Annotated Tips and Resource Links

A simple tool for curated FAQ, tool tips and Key concepts

## Project Brief

### What does the client want

- Improve student journey experience. Help to minimize lost study time access to annotated "how to" visuals by topic

- Minimally Viable Product (MVP)

- Track User rating and feedback

### Who do I think will be using the site?

New students to the course who have little programming experience and have simple how to questions

### How can I make the site as user friendly as possible for the user?

- Simple and intuitive navigation
- Find relevant information easily

## What considerations do I need to keep in mind to meet the user/client requirements?

- Remove friction to learning by providing alerts and tips at the most appropriate checkpoints by topic
- Provide the informaton in combination with concrete contexts for applying the concepts by adopting the apporach of experiential learning

## Is there a specific color scheme I need to work around?

- Easy on the eyes
- Need to research best practice UX color scheme for text and image content webpage

## Personas

- New CI Student
- Non-Slack User
- CI Student Care

## Client Stories/User Stories

- As an X user, I want Y, to achieve Z
- Student wants to see screens capture that show how to do something in a tool
- Student wants to download a document
- Student wants tips related to specific challenges
- Student wants daily tips

## Single Page Website with Three Sections

- Mobile-first default layout
- One page design to focus on the most helpful information
- Webpage is reusable or recyclable by topic or issue
- target 1 minute read content
- remove the friction to get started
  - annotated visual
  - animated gifs
  - Accessibility
  - screen reader
  
## Wireframes

- Refer to MS1 balsamiq
- [Initial wireframe for desktop](assets\wireframes\InitialWireframeDesktop.png)
- [Initial wireframe for iPhone](assets\wireframes\InitialWireframeiPhone.png)

## Website Maintenance

- Easy to maintain and update content
- Minimal code change maintenance
- Aria compliant

## UX

- Call out Information Architecture how to find information try to suggest at what point in their progress that tips are relevant
- Single Page: 3 Sections
  *CI modules (HTML, CSS, User-Centric)
  *Tools (CI LMS Repl.it, Gitpod Team Unlimited, Github, Git, Slack, Browser Developer Tool) *Key Concepts (CSS-Specificity, Bootstrap-Flexbox)
  *MS1 Resources

## Color Scheme

- Need recommendations with background, fonts and color scheme

### Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### Existing Features

- sticky navbar
- sections
- carousel
- scroll spy
- modal window
- image magnification
- file download
- hide elements at defined breakpoints
- Aria labels?
- Form for Collect Usage and Rating of each resource
- Modal window search

- Home Header section
  - Use to welcome users and provide a `call to action button` to select section

- Responsive Navigation

  - Navigation collapses automatically depending on the device utilized

- Document Download

- Footer
  - Input Form to Content Usage and Feedback
    - Rating of content
    - Comment to provide feedback for improvements
  
#### Features Left to Implement

- Activate Form Javascript for Collect stream click
- Collect Rating of each resource

- JavaScript
  Additional JavaScript/jQuery could be added to make particular elements more interactive, for example, a scrollable testimonial sections, more modals and animation.

### Future Goals

- Track Slack frequently FAQ by module
- Track Slack Pinned messages
- Single screen Visual Checklists
- Manual maintenance process flow to be automated using slack API and bots
- use decision-tree or simple AI to keep, remove or modify content
- chatbot

### Technologies Used

- Semantics markup

- [CSS3](https://www.w3.org/Style/CSS/ "Cascading Style Sheets Official Site")

- Cascading Style Sheets for website presentation.

- [Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/ "Bootstrap Official Site")

- Fonts
  - [Google Fonts](https://fonts.google.com/ "Google Fonts Official Site")

- Utilized for icons  
  - [Font Awesome](https://fontawesome.com/ "Fontawesome Official Site")

## Testing

- HTML Validataor

- Test website using `Google Chrome Dev tools` for various devices sizes responsiveness

- The webpage was tested on a cell phone and iPad

- External links to third party websites.
  - fontawsome

- buttons responsiveness

- Navigation

- Links

- Ensured individual section headers resized and appeared well when viewed on various device screens.

- Spell checked all text content.

- Storybook plyground/ Selenium website testing /

- image compression and optimization impact on page load performance

- HTML and CSS validation via [w3.org](https://www.w3.org/ "W3C Official Site").

- Chrome Developer Tool validation
  - Checked margins and padding of the container (sections) to ensure the content within it did not look disproportionate on various screen sizes, individually smaller devices.

- Semantic Checklist
  - Title Specifically for CI Full Stack Developer New Students
  - Article Container for New Student FAQ and tips focused on User-Centric Frontend Development
  - sections
  - check out if time permits [jsfiddle](https://jsfiddle.net/boilerplate/bootstrap)

  - CSS prefixes - autoprefixer.github.io

  - Aria-label is what the screen reader READS OUT to me
    - images
    - icon links
    - modal window link

## Deployment

GitHub Pages was used for deploying the final project version

### To clone repository using command line

[Cloning a repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

  1. Navigate to [https://github.com/NgiapPuoyKoh/](https://github.com/NgiapPuoyKoh/)
  1. Click Clone or download
  1. Clone with HTTPS [https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git](https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git)
  1. Open git bash
  1. Change current working directory to the location where you want the cloned directory to be made
  1. Type git clone [https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git](https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project.git)
  1. Press enter

### Configure GitHub Pages site

[Configuring a publishing source for your GitHub Pages site](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

1. Navigate to Github remote repository [https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project](https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project)

1. Click on settings

1. Scroll down the page to GITHUB Pages section

1. For the Source select "master branch"

1. Wait a few minutes and then access completed project using this link [https://ngiappuoykoh.github.io/user-centric-frontend-milestone-project/](https://ngiappuoykoh.github.io/user-centric-frontend-milestone-project/)

### Content

- Annotated png
- All text content is original or link
- slack pinned messages
- links to 5 star and above read
- bitesize concepts
- Animated Gifs

- Bootstrap
  - Anna_ci
    - [How to use the Bootstrap 4 grid - Demo site](https://www.youtube.com/watch?v=zDpCejbl1sU&feature=youtu.be)

### Media

- CI Slack channel links to pinned messages

- [CI resources](https://auxfuse.github.io/userCentricResourcePack/) by Anthony O'Brien with CI collaborators

- Documents, CI slack links reference

### Issues and Resolutions + Any known issues

### Acknowledgements and Credits

- Igor Basuga User stakeholder
- Anthony O'Brien
- eventyret_mentor
- Anna_ci

## Semantic Checklist

- Title Specifically for CI Full Stack Developer New Students
- Article Container for New Student FAQ and tips focused on User-Centric Frontend Development
- sections

## Research

- Customer Research
Observation of slack FAQ and Pinned Messages
- Personas
Students with little experience but comfortable using a computer as a user
-Student Journey
-[Existing resource](https://auxfuse.github.io/userCentricResourcePack/)

## References

### Markdown

- [Markdown Crash Course](https://www.youtube.com/watch?v=HUBNt18RFbo)

### UX Design

- [The 2020 UI Design Fundamentals Crash Course](https://www.youtube.com/watch?v=tRpoI6vkqLs)
- [UX Apprentice](https://www.uxapprentice.com/)

### Wireframe Reference

- [Rapid Wireframing:Finding the Right Product Design](https://www.skillshare.com/classes/Rapid-Wireframing-Finding-the-Right-Product-Design/1947996659)

- [Udemy Wireframing with Balsamiq Mockups](https://www.udemy.com/course/wireframing-with-balsamiq-mockups/learn/lecture/3993718)

- [How to Create Your First Wireframe](https://www.youtube.com/watch?v=KdfO_e0yK-g)

### Bootstrap

- [How the Bootstrap 4 Grid Works](https://uxplanet.org/how-the-bootstrap-4-grid-works-a1b04703a3b7)

### Developer Tools

- [Goole Chrome Developer Tools Crash Course](https://www.youtube.com/watch?v=x4q86IjJFag)

- IDE
  - Gitpod
  - VSCode

### HTML

- [HTML5](https://www.w3.org/TR/html5/HTML5) Official Site

### Git and GitHub

- [MS1 Github Repository](https://github.com/NgiapPuoyKoh/user-centric-frontend-milestone-project)

- Feature Branches
  - README

### Online Tools

-[jsfiddle](https://jsfiddle.net/boilerplate/bootstrap)
-[tinypng](https://tinypng.com/)

### Disclaimer

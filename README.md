# Stag Board Games Club Website #
![Stag Logo](documents/logo-small.png)

The Stag Board Games Club website has two main purposes. It aims to attract new members to the club by providing clear and factual information about club events, portray the welcoming and inclusive atmosphere of the club and allow for an easy method to contact a club representative with any questions. It also aims to cater for current members who want to see up-to-date photos from recent events, find out more information about future events and research popular games.

The target audience of the website is both potential new members and current members. It will be useful for finding out information about club events, contacting club representatives and gaining an insight into what an experience would be like if attending a club event.

Click this <a name="Stag Board Game Club" target=_blank aria-label="Github deployed version of the STAG board game club website, opens in a new tab." href=https://andrewpmilne.github.io/project-one-stag-games-club> link </a> to see the deployed version of the website.

![screenshots of aspects of the site in different screensizes](documents/responsive-screenshot.png)
---
## User Stories #

### Must Have ###
![Screenshot of github user story](documents/must-have-one.png)

![Screenshot of github user story](documents/must-have-two.png)

![Screenshot of github user story](documents/must-have-three.png)

### Should Have ###
![Screenshot of github user story](documents/should-have-one.png)

![Screenshot of github user story](documents/should-have-two.png)

### Could Have ### 
![Screenshot of github user story](documents/could-have-one.png)

All the Must Have and Should Have user stories were completed. The Could Have user story was completed but the method to do this was altered. Instead of a list of games played on an average night, a carousel of the voted for 'Games of the Year' was included instead.

---
## Features ##
The website includes a number of features to reach the aims of encourages new members and supporting current members.

### Navbar ###
The navbar includes a number of features to aid user experience:
- Responsiveness at different screen sizes to use space appropriately.
- Clear naming of different pages within the site to allow of ease of use between pages.
- A logo to help brand the club and navigate to the homepage.
- Underlined text to indicate the page a user is currently on.
- A change in text colour when a mouse if hovered over a link to visually indivate what will happen when the link is clicked.
![The desktop navbar](documents/navbar-full.png)
![The mobile or small screen navbar](documents/navbar-small.png)

### Introduction and 'Hero' image ### 
The first feature of the main section is a large image of a number of people at a club night and a button as a 'call to action' for new members to find out more. This busy scene shows the club in a positive light for any users one their first viewing of the website. The button uses a media query to position in front of the image in desktops to save space and ensure it can be seen in a prominent position, but sits beneath the images in smaller screens to avoid blocking the image.
![image and button on desktop screens](documents/action-button-large.png)
![image and button on smaller screens](documents/action-button-small.png)

### Information Section ###
The information section allows users to quickly and easily find out information about the club in order to easily attend events in the correct location. Images and a map have also been used to aid understanding.
![Screenshot of the venue information](documents/information.png)

### Testimonials Section ###
The testimonials section helps users to see the welcoming and inclusive nature of the club, making them feel at easy with attending events. Images of the speakers in this section make the testimonials personal to the user reading them.
![Screenshot of two of the testimonials](documents/testimonials.png)

### Gallery ### 
The purposes of the gallery are to give perspective members an idea of what happens at an event and for current members to look at photos from events they have attended. The following features aid these aims:
- Large, clear images, professionally taken.
- A responsive layout so that the images can be seen clearly on any screen size.
- A shadow effect to help the images stand out.

![Screenshot of the gallery page on a mobile screen](documents/gallery-small.png)
![Screenshot of the gallery page on a desktop screen](documents/gallery-large.png)

### Games of the Year ### 
The aim of this page is to allow users further insight into the sort of games played at the club. A carousel was used to allow the user to interact with the images of the games and look at them at their own speed. The scroll buttons were styled to increase accessibility. Each picture links to the Board Game Geek website to give the user more information about the game. Each link opens in a new tab to allow easy of navigation for the user.

![screenshot of the games of the year carousel](documents/goty.png)

### Contact Us ###
The contact us page displays a form for the user to fill in to connect with a club representative and find out more information. It includes the following features:
- Required elements of 'First Name', 'Last Name' and 'Email Address' in order that no important information is left out.
- Checkboxes to make clear the particular events users are interested in.
- A textarea element to give the user the chance to write an specific questions.
- Submit and reset buttons to aid user experience. The submit button navigates to a separate page to confirm the form has submitted successfully.
- A responsive design that positions the form on top of the image in desktop screens, but keeps it below the image on smaller screens.
Borders around fields to ensure accessibility.

![Screenshot of the form in a small screen](documents/form-small.png)
![Screenshot of the form in a large screen](documents/form-large.png)
![Screenshot of the form-complete page](documents/form-response.png)

### Footer ### 
The footer section contains links to social media, relevant for users looking to connect with the club. These links will open to a new tab to allow easy navigation. 

![Screenshot of the footer](documents/footer.png)

---

### Features Left to Implement ###
The site could benefit from the following features in the future:
-A page used for write-ups of events. This already exists in the club's social media and could easily be transfered to the page.
-A 'members area' to allow current members to arrange meet-ups and discuss games played.

---

## Testing ## 
- The website has been tested in different browsers: 

  - Chrome

  ![Chrome testing](documents/chrome.png)
  ![Chrome testing](documents/chrome-two.png)

  - Edge

  ![Edge testing](documents/edge.png)
  ![Edge testing](documents/edge-two.png)

  - Safari

  ![Safari testing](documents/safari.png)
  ![Safari testing](documents/safari-three.png)

- The project is responsive and functions on all standard screen sizes, using Dev Tools device toolbar.

![video of the site showing responsiveness at different screen sizes](documents/responsive-one.gif)

![video of the site showing responsiveness at different screen sizes](documents/responsive-two.gif)

![video of the site showing responsiveness at different screen sizes](documents/responsive-three.gif)

- The text in all pages is readable and easy to understand. Lighthouse was used to check for accessibiliy, including colour clashes.
- The form has been tested, requires entries in the 'First Name', 'Last Name' and 'Email' fields, and the 'Email' field will only accept a recognised email address. The submit button navigates to a confirmation page and the reset button works.
- All external links work and are open in new tabs.
- Internal links and buttons all work.

### Bugs ### 
- Navigation proved difficult in earlier deployments due to inconsistent styling of the buttons and links. This was corrected in the final version.
- Accessibility was an issue in the initial colour choices on the form, but this was corrected.
- Initially, a hover psuedo classed was used in the gallery to increase the size of images. However, this created issues with navigating the site and was removed. 

### Validation ###
- HTML was validated using the official W3C validator. All pages passed with no errors:
-index
![index page validation](documents/html-check-index.png)
-contact us
![contact us page validation](documents/html-check-form.png)
-for submitted
![form submitted page validation](documents/html-check-form-submitted.png)
-gallery
![gallery page validation](documents/html-check-gallery.png)
-game of the year
![game of the year page validation](documents/html-check-goty.png)

- CSS was validated using...
- Accessibility was checked using...
---
## Deployment ##
This section describes the process required to deploy this project using GitHub.
- Go to the Settings tab of your GitHub repo.
- On the left-hand sidebar, in the Code and automation section, select Pages.
  - Make sure:
    - Source is set to 'Deploy from Branch'.
    - Main branch is selected.
    - Folder is set to / (root).
- Under Branch, click Save.
- Go back to the Code tab. Wait a few minutes for the build to finish and refresh your repo.
- On the right-hand side, in the Environments section, click on 'github-pages'.
Click View deployment to see the live site.

The live site can be found here:
- https://andrewpmilne.github.io/project-one-stag-games-club/
---

### Technologies Used ###
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - was used in media queries and to style, including to position the form and the action button in front of images.
- [Bootstrap](https://getbootstrap.com/) - was used to style elements throughout the project, including ensuring responsiveness. 
- [Balsamiq](https://balsamiq.com/) was used to make wireframes for the website.
- [VSCode](https://code.visualstudio.com/) was used as the main tool to write and edit code.
- [Git](https://git-scm.com/) was used for the version control of the website.
- [GitHub](https://github.com/) was used to host the code of the website and log notes in the design process.


## Credits ##
The following sites were used to assist with the project:
- https://getbootstrap.com/ (linked in the HTML code to aid design and responsiveness).
- https://fontawesome.com/ (linked in the HTML code for social media icons).
- https://fonts.google.com/ (to source the fonts used for the project).
- https://stackoverflow.com/ (for assistance with code-related queries).
- https://www.w3.org/ (for guides and tutorials with specific code).
- https://www.youtube.com/kevinpowell (for guidance with CSS, specifcally flexbox).
---
### Media ###
- Most images were used with permission from David Fox, co-ordinator of the STAG board games club.
- Images for the testimonials section were taking from https://www.pexels.com/
---
## Thanks ## 
I'd like to thank:
- My mentor, Juliia Konovalova for Slack calls and lots of constructive criticism!
- The Code Institute tutors, Rebecca and Oisin, for helping to solve a few technical issues.
- David Fox, co-ordinator of the STAG board games club, for moral support and providing images and logos. 
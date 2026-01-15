# World of History Museum Website

### Table of Contents
- [Overview](#overview)
- [Features](#features)
- [User Experience UX](#user-experience-ux)
- [Wireframes](#wireframes)
- [Design](#design)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Deployment](#deployment)
- [Testing and Bugs](#testing-and-bugs)
  - [Manual Testing](#manual-testing)
  - [Lighthouse Testing](#lighthouse-testing)
  - [HTML and CSS Validation](#html-and-css-validation)
- [Attributions](#attributions)
- [Additional Notes](#additional-notes)
- [Author](#author)

---

# Overview

A website for the **World of History Museum**, designed to showcase the exhibits on offer and the oppurtunity to engage with the museum through the various forms on offer. This website is for families, students and history enthuisast who are interested in what the museum has on offer.

It allowsfor users to know what they can excpect and plan their visit around what they want to see.

---

# Features

* **Home Page Carousel** showcasing museum visuals
* **Visit Page** including ticket purchase, registration, newsletter
* **Responsive Design** with Bootstrap 5
* **Contact and Newsletter forms**
* **Video integration** in exhibits

---

# User Experience UX

## Project Goals

* Provide an intuitive and visually appealing interface
* Make exhibit content available for planning
* Encourage engagement via sign ups and bookings

## User Stories

### First Time Users
* I want an engaging homepage introducing the museum
* I want clear navigation to exhibits and visit information

### Returning Users
* I want fast access to ticket booking and new events

### Frequent Users
* I want to subscribe to newsletters and receve updates

---

## Responsive Design Preview

Below is a multi device mockup demonstrating how the **World of History Museum** website appears on desktop laptop tablet and mobile screens and screeenshots.
![Multi Device Mockup](assets/media/multi-screen.jpeg) 

![Screenshots](assets/media/screenshot-1.jpg)

![Screenshots](assets/media/screenshot-2.jpg)

![Screenshots](assets/media/screenshot-3.jpg)

![Screenshots](assets/media/screenshot-4.jpg)

![Screenshots](assets/media/screenshot-5.jpg)

![Screenshots](assets/media/screenshot-6.jpg)



---

# Design

## Colour Scheme

* Background `#f5f1e6`
* Header and Footer `#212529`
* Highlight `#ffc107`

## Typography

* Open Sans for body text
* Playfair Display for headings and titles

## Imagery

High quality curated images including Unsplash Wikimedia Commons museum inspired assets and exhibit specific photography.

---

# Wireframes

Wireframe link  
https://balsamiq.cloud/sucgt7o/phmvnkl

Desktop layouts use a full width carousel  
Tablet layouts use adjusted padding  
Mobile layouts use a single column layout

---

# Technologies Used

## Languages
* HTML
* CSS
* JavaScript Bootstrap bundle

## Frameworks and Libraries
* Bootstrap 5.3
* Google Fonts

## Tools
* GitHub
* VS Code
* Chrome DevTools
* Lighthouse
* Balsamiq
* W3C Validator
* MDN
* Chat GPT

---

# File Structure
# File Structure

World-Of-History  
│  
├── index.html  
├── exhibits.html  
├── visits.html  
│── email.html  
├── submitted.html  
├
├── assets  
│   ├── style.css  
│   ├── exhibits.css  
│   ├── visits.css  
│   │  
│   ├── media  
│   │   ├── bronzeage.jpg  
│   │   ├── clip-one.mp4  
│   │   ├── crystal-palace.jpg  
│   │   ├── crystalpalace.jpg  
│   │   ├── egyptian.mp4  
│   │   ├── greek-new.jpeg  
│   │   ├── greekstatue.jpeg  
│   │   ├── hannibal.jpeg  
│   │   ├── henry-new.jpeg  
│   │   ├── henry8.jpg  
│   │   ├── lighthouse.jpeg  
│   │   ├── multi-screen.jpeg  
│   │   ├── mummy-artifact.jpg  
│   │   ├── mummy.jpeg  
│   │   ├── museum-1.jpg  
│   │   ├── museum-front.jpeg  
│   │   ├── museum-image2.jpg  
│   │   ├── museum-image3.jpg  
│   │   ├── museum-image4.jpg  
│   │   ├── museum-nhm.jpg  
│   │   ├── new-carousel.jpg  
│   │   ├── new-carousel-two.jpg  
│   │   ├── new-carousel-three.jpg  
│   │   ├── plato.jpeg  
│   │   ├── plato-new.jpeg  
│   │   ├── pyramids.jpeg  
│   │   ├── queen-victoria-abdul.jpg  
│   │   ├── responsive-one.jpeg  
│   │   ├── responsive-two.jpeg  
│   │   ├── roman-enemy.jpeg  
│   │   ├── roman-warrior.jpeg  
│   │   ├── romans.jpeg  
│   │   ├── romans.mp4  
│   │   ├── screenshot-1.jpg  
│   │   ├── screenshot-2.jpg  
│   │   ├── screenshot-3.jpg  
│   │   ├── screenshot-4.jpg  
│   │   ├── screenshot-5.jpg  
│   │   ├── screenshot-6.jpg  
│   │   ├── tudors1.jpg  
│   │   ├── validator-css-exhibit.jpeg  
│   │   ├── validator-exhibit.jpeg  
│   │   ├── validator-index.jpeg  
│   │   ├── validator-style.jpeg  
│   │   ├── validator-visit-css.jpeg  
│   │   ├── validator-visit.jpeg  
│   │   ├── venuehire.jpg  
│   │   ├── victoriaandabdul.jpg  
│   │   └── victorian-video.mp4  
│  
└── README.md

---

# Deployment

## Local Development Environment

The project was developed locally using **Visual Studio Code (VS Code)**. A new project folder was created on my computer, and all relevant files were organised within this folder. This included HTML pages for each section of the website, CSS files for styling placed in `assets/css`, and image and video assets stored in `assets/media`. During development, each page was tested locally by opening the HTML files directly in a web browser. This allowed me to check the **layout, navigation, responsiveness, and functionality** before committing any changes. Minor adjustments were made in VS Code based on these tests to ensure that the website displayed correctly across different devices and screen sizes.

## Version Control Using Git

Version control was managed using **Git**. This allowed me to track changes to the project over time, revert to previous versions if needed, and maintain a clear history of development progress. The workflow included:

1. **Initialising Git**: The local project folder was initialised as a Git repository using `git init`.  
2. **Staging Changes**: After making changes to files, I staged them using:
 *git add .*
This added all new or modified files to the staging area in preparation for committing.  
3. **Committing Changes**: Commits were made regularly with descriptive messages summarising the changes:  
git commit -m "Add homepage layout and carousel functionality"
4. **Pushing to Remote Repository**: Changes were then pushed to the remote repository on GitHub to keep the online version up-to-date:
This process was repeated continuously during development to ensure that every key change was backed up and versioned.
git push
## Creating the GitHub Repository

A **GitHub account** was created to host the project remotely. The repository was created with the following steps:

1. Signed up for a GitHub account at [github.com](https://github.com).  
2. Created a new repository named `WorldOfHistory`.  
3. Set the repository to **public** so it could be viewed and accessed online.  
4. Connected the local project to the repository using the main branch. This included configuring Git with my user details: 
git config --global user.name "sadek17471748"
git config --global user.email "sadek17481748@gmail.com"
5. Linked the local repository to the GitHub repository using the command: 
git remote add origin https://github.com/sadek17481748/worldofhistory.git
6. Pushed the local files to the **main branch** of the repository using:
The repository structure mirrored the local folder, with assets organised in subfolders for images, videos, and CSS.
git push -u origin main
## Deployment Using GitHub Pages

The website was deployed online using **GitHub Pages**, which allows static websites to be hosted directly from a GitHub repository. The deployment process involved:

1. Opening the repository settings and navigating to the **Pages** section.  
2. Selecting the **main branch** as the source branch and the **root folder** as the deployment folder.  
3. GitHub Pages then generated a live URL for the website: 
https://sadek17481748.github.io/worldofhistory/

During this process, I encountered some deployment issues. Initially, some pages returned **404 errors**. This was caused by incorrect file paths to assets such as images, CSS, and videos, as well as naming inconsistencies between local files and their references in the HTML. These issues were resolved by carefully checking the file paths, ensuring consistent naming conventions, and confirming that all assets were correctly referenced in the HTML files.

## Updating the Live Website

Once deployed, any updates to the website are automatically reflected on the live site whenever new commits are pushed to the **main branch** of the GitHub repository. This allows the live website to stay up-to-date with the latest development changes without manual redeployment.

## Live Website

The website is live and accessible via GitHub Pages at:  
[https://sadek17481748.github.io/worldofhistory/](https://sadek17481748.github.io/worldofhistory/)


# Testing and Bugs

|# Testing and Bugs

| Bug | Description | Expected Result | Actual Result | Status |
|-----|------------|----------------|--------------|--------|
| 1 | Navbar not collapsing on mobile | Collapses correctly | Stayed expanded | Fixed |
| 2 | Gallery image broken | Image loads | Broken link | Fixed |
| 3 | Form not submitting | Form sends | No action | Fixed |
| 4 | Cards misaligned on tablet | Proper grid | Overlap | Fixed |
| 5 | Footer alignment issue | Footer stays at bottom | Misaligned | Unresolved |
| 6 | Hover colour incorrect | Gold hover | Grey hover | Fixed |
| 7 | CSS not updating | Updated styles load | Browser cached | Fixed |
| 8 | Video not responsive | Scales correctly | Overflowing | Fixed |
| 9 | Anchor links misaligned | Correct scroll | Offset slightly | Fixed |
| 10 | Carousel not autoplaying | Rotates slides | Stuck on first slide | Fixed |
| 11 | Mobile padding inconsistent | Even spacing | Too tight | Fixed |
| 12 | Hero image pixelated | Sharp image | Blurry | Fixed |


---

## Manual Testing

Manual tests were carried out on navigation buttons links and forms to ensure expected behaviour for a static front end project. 


### Button and Link Functionality

| Item Tested | Page | Expected Result | Actual Result | Pass |
|------------|------|-----------------|---------------|------|
| Home navigation | All pages | Loads index page | Works correctly | Yes |
| Exhibits navigation | All pages | Loads exhibits page | Works correctly | Yes |
| Visit navigation | All pages | Loads visits page | Works correctly | Yes |
| Carousel next button | Home | Moves to next slide | Works correctly | Yes |
| Carousel previous button | Home | Moves to previous slide | Works correctly | Yes |
| Book a tour button | Home | Opens visits page | Works correctly | Yes |
| Our exhibits button | Home | Opens visits page | Works correctly | Yes |
| Footer social links | All pages | Opens external site | Works correctly | Yes |

### Forms Testing

| Form | Page | Expected Behaviour | Result | Pass |
|------|------|-------------------|--------|------|
| Newsletter signup | Home | Accepts email input | Works | Yes |
| Contact form | Home | Accepts text input | Works | Yes |
| Buy tickets form | Visit | Accepts selections | Works | Yes |
| Register interest form | Visit | Accepts text input | Works | Yes |


---


# Lighthouse Testing

Lighthouse testing was carried out using Chrome DevTools to assess performance accessibility best practices and SEO.

| Category | Result |
|--------|--------|
| Performance | Passed |
| Accessibility | Minor warnings |
| Best Practices | Passed |
| SEO | Passed |

![Lighthouse Results](assets/media/lighthouse.jpeg)




---

# HTML and CSS Validation

HTML and CSS were validated using the W3C Validator. All CSS files passed validation. HTML errors were related to button placement and missing alt attributes.

![Validator Screenshots](assets/media/validator-index.jpeg)
![Validator Screenshots](assets/media/validator-exhibit.jpeg)
![Validator Screenshots](assets/media/validator-visit.jpeg)
![Validator Screenshots](assets/media/validator-style.jpeg)
![Validator Screenshots](assets/media/validator-visit-css.jpeg)
![Validator Screenshots](assets/media/validator-css-exhibit.jpeg)


### HTML Validation Results

| Page | Result |
|-----|--------|
| index.html | Errors related to button placement |
| exhibits.html | Missing alt attributes |
| visits.html | No errors |

### CSS Validation Results

| File | Result |
|-----|--------|
| style.css | No errors |
| exhibits.css | No errors |
| visits.css | No errors |

---

# Attributions

Images videos and design inspiration were sourced from Unsplash Wikimedia Commons museum websites and educational resources. 
# Sources & References

This document lists all image, article, video, and design references used for research, visual inspiration, and development.

---

## Image Sources
- **Hercules Beating the Centaur Nessus** — Wikimedia Commons  
  https://commons.wikimedia.org/wiki/File:Hercules_beating_Centaur_Nesso.jpg

- **Moscow State Historical Museum** — Wikimedia Commons  
  https://commons.wikimedia.org/wiki/File:Moscow_State_Historical_Museum_-_IMG_3502.JPG

---

## Articles & Online Resources
- **Great Minds of Greece** — *I Became a Stoic Through These 3 Not-So-Easy Daily Practices* (Medium)  
  https://medium.com/masterpieces-in-progress/i-became-a-stoic-through-these-3-not-so-easy-daily-practices-cbd2bb8e556b

- **Greek Art Courses** — Apollon Art Studio, Florence  
  https://apollonartstudioflorence.com

- **Augustus (Roman Emperor)** — Wikipedia  
  https://en.wikipedia.org/wiki/Augustus

- **Tudors Exhibit** — Legion of Honor Museum  
  https://www.famsf.org/visit/legion-of-honor

- **Pyramid Construction** — Science Focus  
  https://www.sciencefocus.com/science/egyptian-pyramids-new-studies

- **Mummification Ingredients** — *Jerusalem Post*  
  https://www.jpost.com/archaeology/article-730316

- **Victoria & Abdul** — Abdul Karim (the Munshi), Wikipedia  
  https://en.wikipedia.org/wiki/Abdul_Karim_(the_Munshi)

- **Great Exhibition of 1851** — Antique Box Guide  
  https://www.antiquebox.org/the-great-exhibition-of-1851/

- **Psychological Framing** — *The Life-Changing Power of Seeing…*  
  https://mindfulambition.net/psychological-framing/

- **Watford Museum Plans** — Local news source

- **Museum Sleepovers** — Travel article

- **Garden Museum Orangery** — Dan Pearson Garden  
 https://flavoursearch.com/listings/3395/garden-museum/the-orangery-dan-pearson-garden

---

## Unsplash Images
- https://images.unsplash.com/photo-1491156855053-9cdff72c7f85
- https://images.unsplash.com/photo-1544213456-bc37cb97df74
- https://plus.unsplash.com/premium_photo-1661963952208-2db3512ef3de
- https://images.unsplash.com/photo-1594026200204-a25bea256816
- https://images.unsplash.com/photo-1505664194779-8beaceb93744

---

## Video Sources
- **Egyptians Exhibit** — YouTube  
  https://www.youtube.com/watch?v=Nh-1eTd2c4o

- **Victorian Era** — YouTube  
  https://www.youtube.com/watch?v=YbimS9gQtZ4

- **Roman Empire** — YouTube  
  https://www.youtube.com/watch?v=b9bcohqsTGk

---

## Design & Visual Inspiration
- **British Museum**  
  https://www.britishmuseum.org

- **Victoria and Albert Museum (V&A)**  
  https://www.vam.ac.uk

- **Science Museum**  
  https://www.sciencemuseum.org.uk

---

## Bootstrap Components
- **Grid System**  
  https://getbootstrap.com/docs/5.3/layout/grid/

- **Forms**  
  https://getbootstrap.com/docs/5.3/forms/overview/

- **Cards**  
  https://getbootstrap.com/docs/5.3/components/card/

- **Buttons**  
  https://getbootstrap.com/docs/5.3/components/buttons/

- **Utilities**
  - Spacing: https://getbootstrap.com/docs/5.3/utilities/spacing/
  - Flex: https://getbootstrap.com/docs/5.3/utilities/flex/

- **Navs & Tabs**  
  https://getbootstrap.com/docs/5.3/components/navs-tabs/

---

## HTML Layout Inspiration
- **W3Schools** — HTML5 Semantic Elements  
  https://www.w3schools.com/html/html5_semantic_elements.asp

- **freeCodeCamp** — HTML Structure Examples

- **Professional Museum Websites** — General design inspiration  
  https://www.britishmuseum.org

---

# Additional Notes


This project was inspired by modern museum websites that focus on clear navigation visual storytelling and user engagement. Design ideas were taken from professional museum platforms to help make the site feel realistic and accesible to a wide range of users.

During development a mix of manual debugging online research and some AI assistance was used to help solve problems and improve features. AI was mainly used as a support tool when issues could not be easily resolved or when further explanation was needed.

Examples of areas where AI assistance helped include:

1. Identifying why the navigation bar was not colapsing correctly on smaller screen sizes.
2. Understanding Bootstrap grid behaviour when cards became misaligned on tablet view.
3. Troubleshooting broken image paths after reorganising the assets and media folders.
4. Fixing carousel autoplay issues caused by missing Bootstrap data attributes.
5. Improving form structure so required fields behaved correctly in a static project.
6. Resolving CSS specifity issues where styles were being over written.
7. Identifying browser caching problems when updated CSS was not loading correctly.
8. Adjusting video containers to prevent overflow on mobile devices.
9. Improving anchor link behaviour within the README file.
10. Debugging footer positioning issues across different screen sizes.
11. Clarifying correct semantic HTML structure to improve accesibility.
12. Understanding Lighthouse warnings and how to reduce accesibility related issues.
13. Fixing missing alt attributes on images to improve HTML validation results.
14. Improving responsive spacing using Bootstrap utility clases.
15. Correcting GitHub Pages deployment issues related to file paths and case sensitivity.

All solutions were implemented and tested manualy by the developer to ensure they worked correctly within the project. AI was used to explain errors suggest possible fixes and improve overall understanding of front end development concepts.

Future projects would benefit from planning the file structure earlier in development and applying Bootstrap consistantly from the beginning to reduce layout issues later on.


---

# Author

Mohammed Sadek Hussain  
NCC  
Level 5 Web Development  
Milestone 1
 






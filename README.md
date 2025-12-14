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
![Multi Device Mockup](assets/media/multi-screen.jpeg.png) 

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
│  
├── assets  
│   ├── style.css  
│   ├── exhibits.css  
│   ├── visits.css  
│   │  
│   ├── media  
│   │   │ 
│   │   │   ├── crystalpalace.jpg  
│   │   │   ├── victoriaandabdul.jpg  
│   │   │   ├── mummy.jpeg  
│   │   │   ├── pyramids.jpeg  
│   │   │   ├── tudors1.jpg  
│   │   │   ├── henry-new.jpeg.webp  
│   │   │   ├── roman-warrior.jpeg.avif  
│   │   │   ├── roman-enemy.jpeg.avif  
│   │   │   ├── greek-new.jpeg.avif  
│   │   │   └── plato-new.jpeg.avif  
│   │   │  
│   │   ├── videos  
│   │   │   ├── clip-one.mp4  
│   │   │   ├── egyptian.mp4  
│   │   │   └── romans.mp4  
│   │  
│   ├── lighthouse.jpeg  
│   ├── multi-screen.jpeg.png  
│   ├── validator-index.jpeg  
│   ├── validator-visit.jpeg  
│   └── validator-exhibit.jpeg  
│  
└── README.md

---

# Deployment

### Local Development Environment

The project was developed locally using VS Code. A new project folder was created and opened in VS Code. All HTML CSS image and video assets were created and organised within this folder.

During development each page was tested locally in the browser to check layout navigation and responsivness.

---

### Version Control Using Git

Git was used for version control to track progress. Files were staged and committed regularly after key changes were made.

---

### Creating the GitHub Repository

A repository named World Of History was created on GitHub and the local project was connected to it. Files were pushed using the main branch.

---

### Deployment Using GitHub Pages

GitHub Pages was enabled through repository settings. The main branch and root folder were selected. GitHub then generated a live link.

---

### Updating the Live Site

Any new commits pushed to the main branch automatically update the live website.

---

### Live Website

https://msadekhussain2001-ux.github.io/World-Of-History/

---

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
## Manual Testing

Manual tests were carried out on all interactive elements across the site to ensure correct navigation and expected behaviour for a static front end project.

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

Lighthouse testing was carried out using Chrome DevTools. 
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
## Image Sources * Hercules beating Centaur Nessus — [https://commons.wikimedia.org/wiki/File:Hercules_beating_Centaur_Nesso.jpg](https://commons.wikimedia.org/wiki/File:Hercules_beating_Centaur_Nesso.jpg) * Great Minds of Greece — "I Became A Stoic Through These 3 Daily..." (blog) https://medium.com/masterpieces-in-progress/i-became-a-stoic-through-these-3-not-so-easy-daily-practices-cbd2bb8e556b * Greek Art Courses — Apollon Art Studio Florence https://apollonartstudioflorence.com * Romans – Augustus — [https://en.wikipedia.org/wiki/Augustus](https://en.wikipedia.org/wiki/Augustus) * Tudors Exhibit — Legion of Honor Museum https://www.famsf.org/visit/legion-of-honor * Pyramid Construction — Educational article https://www.sciencefocus.com/science/egyptian-pyramids-new-studies * Mummification Ingredients — Science history article https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.jpost.com%2Farchaeology%2Farticle-730316&psig=AOvVaw0Qom2e24TO7KsgXEHHVV9c&ust=1763658787342000&source=images&cd=vfe&opi=89978449&ved=0CBkQjhxqFwoTCIit6dOdgZEDFQAAAAAdAAAAABAE * Victoria & Abdul — Historical documentary reference https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FAbdul_Karim_%2528the_Munshi%2529&psig=AOvVaw04iJHgyNGmujdw-Bihvmyb&ust=1763658848387000&source=images&cd=vfe&opi=89978449&ved=0CBkQjhxqFwoTCODe3vOdgZEDFQAAAAAdAAAAABAE * Great Exhibition 1851 — Antique Box Guide https://www.antiquebox.org/the-great-exhibition-of-1851/ * Psychological Framing — "The Life-Changing Power of Seeing..." https://mindfulambition.net/psychological-framing/ * Watford Museum Plans — Local news * Moscow State Historical Museum — [https://commons.wikimedia.org/wiki/File:Moscow_State_Historical_Museum_-_IMG_3502.JPG](https://commons.wikimedia.org/wiki/File:Moscow_State_Historical_Museum_-_IMG_3502.JPG) * Museum Sleepovers — Travel article * Garden Museum Orangery — [https://flavoursearch.com/listings/3395/garden-museum/the-orangery-dan-pearson-garden](https://flavoursearch.com/listings/3395/garden-museum/the-orangery-dan-pearson-garden) ## Unsplash Images * [https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=2128](https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=2128) * [https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=207](https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=207) * [https://plus.unsplash.com/premium_photo-1661963952208-2db3512ef3de?auto=format&fit=crop&q=80&w=2144](https://plus.unsplash.com/premium_photo-1661963952208-2db3512ef3de?auto=format&fit=crop&q=80&w=2144) * [https://images.unsplash.com/photo-1594026200204-a25bea256816?auto=format&fit=crop&q=80&w=987](https://images.unsplash.com/photo-1594026200204-a25bea256816?auto=format&fit=crop&q=80&w=987) * [https://images.unsplash.com/photo-1505664194779-8beaceb93744?auto=format&fit=crop&q=80&w=1470](https://images.unsplash.com/photo-1505664194779-8beaceb93744?auto=format&fit=crop&q=80&w=1470) * [https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=2070](https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=2070) * [https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=212](https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=212) ## Video Sources * Egyptians Exhibit — [https://www.youtube.com/watch?v=Nh-1eTd2c4o](https://www.youtube.com/watch?v=Nh-1eTd2c4o) * Victorian Era — [https://www.youtube.com/watch?v=YbimS9gQtZ4&t=2s](https://www.youtube.com/watch?v=YbimS9gQtZ4&t=2s) * Roman Empire — [https://www.youtube.com/watch?v=b9bcohqsTGk](https://www.youtube.com/watch?v=b9bcohqsTGk) ## Design attributes * https://www.britishmuseum.org * https://www.vam.ac.uk/?srsltid=AfmBOoouP7NWYYbtwCNar8xhK-SokgJSu3MhQLyVGvajtSR-PBZiXOaO * https://www.sciencemuseum.org.uk ## Bootstrap Components * Grid System — [https://getbootstrap.com/docs/5.3/layout/grid/](https://getbootstrap.com/docs/5.3/layout/grid/) * Forms — [https://getbootstrap.com/docs/5.3/forms/overview/](https://getbootstrap.com/docs/5.3/forms/overview/) * Cards — [https://getbootstrap.com/docs/5.3/components/card/](https://getbootstrap.com/docs/5.3/components/card/) * Buttons — [https://getbootstrap.com/docs/5.3/components/buttons/](https://getbootstrap.com/docs/5.3/components/buttons/) * Utilities — [https://getbootstrap.com/docs/5.3/utilities/spacing/](https://getbootstrap.com/docs/5.3/utilities/spacing/) [https://getbootstrap.com/docs/5.3/utilities/flex/](https://getbootstrap.com/docs/5.3/utilities/flex/) * Nav Links — [https://getbootstrap.com/docs/5.3/components/navs-tabs/](https://getbootstrap.com/docs/5.3/components/navs-tabs/) ## HTML Layout Inspiration * W3Schools — [https://www.w3schools.com/html/html5_semantic_elements.asp](https://www.w3schools.com/html/html5_semantic_elements.asp) * freeCodeCamp — HTML structure examples * General inspiration taken from professional museum websites https://www.britishmuseum.org

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






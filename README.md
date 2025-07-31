# Safeguarding Website

## Live Site

[Safeguarding Website](https://rosietrainor.github.io/safeguarding-project/)

## Introduction

This website aims to give easy to understand information on safeguarding. 

It lays out what safeguarding is, how to recognise signs of safeguarding concerns, and what to do if you have any concerns. It provides contact information to report safeguarding concerns and links to further information on safeguarding from reputable sources. 

The site aims to be as accessible as possible for everyone.

## Responsivity
### Mobile/Tablet View
### Desktop View

## Contents

## User Experience

### Strategy

The goal of this site is to provide clear, easy to access information on safeguarding, including how to recognise and respond to any safeguarding concerns. The layout and navigation should be simple and intuitive, making the information easy to access and understand.

### Scope

I used a github project board with user stories to track progress and ensure the requirements were met within the time frame. I used ChatGPT AI create the user stories from specific prompts then refined them.

 My must-have user stories amounted to an MVP, with should- and could-haves adding extra value.

**Must-have user stories focused on 5 main areas as outlined in the brief:**
- Simple and easy to understand information on safeguarding and it's key principles
- Information on how to recognise and respond to safeguarding concerns
- Accessibilty 
- Easy to use Navigation and Layout
- Responsivity for mobile, tablet, and desktop

**Should-have stories allowed users to find more information than found on the website:**
- Further information/links to other sites related to safeguarding

**Could-have stories focussed on encouraging users to report if they had concerns :**
- Contact form to allow users to report their concerns directly
- Testimonials to reassure users that reporting was the right thing to do

### Structure

The structure of this site is quite simple, with it being one page.

There is a naviagtion bar fixed at the top so it is easily accessed from everywhere on the site. The links take you to different sections of the site. 

On the navigation bar and in the hero section of the page there is a button with "Report a Concern". This takes you to the contact section of the site within the footer, so users can easily find the contact information needed to report a safeguarding concern. 

There is also a link within the last card of the Respond to Concerns section which takes you to the same place. It is assumed that a user with a concern may want read through the sections above before reporting, and once they have, this link will take them to the next step. 

### Skeleton

Balsamiq Wireframes were used to plan the layout of the site. 

![Desktop Wireframe](documentation/Wireframes-Desktop.jpg)

![Mobile Wireframe](documentation/Wireframes-Mobile.jpg)

### Surface 
 
My design choices are outlined below. 

## Design

### Colour Scheme

The colour scheme was chosen to be calming and professional, whilst meeting accessibility guidelines for colour contrast. A pale blue fading to teal is used for the background whilst a darker blue is used for the text, navigation and footer. Within the "Respond to Concerns" cards the colour combination is flipped for emphasis, with a dark blue background and pale blue text.  When necessary for accessibilty and colour contract, black or white text is used. All colour combinations were checked with webaim contrast checker to ensure readability.<br>

Teal is used for buttons to stand out whilst fitting the colour scheme. The hover for buttons is set to a darker teal to show they are highlighted.

#2C3E50 - dark blue <br>
#F0F8FF - pale blue <br>
#20B2AA - teal <br>
#008B8B - darker teal <br>

### Fonts

This website uses Inter for the headings and PT Sans for the body text. These were chosen for their readability and style. They are listed as "calm" and "business" on google fonts, which is appropriate for a safeguarding website that aims to be easy to read and approachable, but also professional. They pair well as both are modern sans-serif fonts.

## Website Features

<!-- Navbar -->
<!-- Footer -->
<!-- Report Button -->
<!-- Features of Home Page -->


## Future Features

In future, I want to implement a Contact Form page where users can directly report a safeguarding concern online. This would make it easier for users to report than the current contact information given. I would also want an associated success page directed to when submitting the form to show a successful submission. Both of these pages can be seen on my wireframes.

I would also want a Testimonials page where users can see successful outsomes of safeguarding referrals to reassure users that reporting is the right thing.

I would want to add a favicon to the pages rather than the "Safeguarding" text I currently have.

## Technologies Used

This site was coded with HTML, CSS, and JavaScript.

**Git** was used for version control. 

**[Github](https://github.com/)** was used to save and store the files for the site.

**[Github Pages](https://pages.github.com/)** were used to deploy the site.

**[Github Issues Project Board](https://github.com/features/issues)** was used to track progress.

**[Bootstrap](https://getbootstrap.com/)** Framework (v5.3) was used for the grid structure and responsivity throughout the site. 

The navigation bar, cards, carousel, and buttons were built using Bootstrap and adapted for the site.

**[Font-Awesome](https://fontawesome.com/)** was used for icons throughout the site.

**[Google Fonts](https://fonts.google.com/)** was to import fonts.

**[Fontpair](https://fontpair.co/)** was used to pick a font pairing.

**[WebAIM](https://webaim.org/resources/contrastchecker/)** was used to check the colour contrast for accessibility.

**[Emmet](https://emmet.io/)** was used for rapid HTML/CSS generation via abbreviation syntax, and to generate text primarily in the "Recognise the Signs" section.

**[Sqoosh]( https://squoosh.app/)** and **[Tinify](https://tinypng.com/)** were used to compress images for the web.

**[ChatGPT](https://chatgpt.com/)** was used to generate user stories.

**[Microsoft Copilot](https://copilot.microsoft.com/)** was used for image generation, code generation, and debugging (see AI use section).

**[Chrome DevTools](https://developer.chrome.com/docs/devtools)** were used for debugging and testing.

### AI Use

AI was used in this project for code generation (per project brief), debugging, and image generation. I also used ChatGPT to help generate users stories given the brief.

#### Image Generation

The image in the "About" section was created with Microsoft Copilot, as were the images for the cards in the "Recognize the Signs" section.

#### Code Generation

Copilot was used to generate and style an overlay div to darken the hero image without darkening the text on the image. It was also used to style the carousel images so they appeared the same size and remained responsive.
Finally, I used it to add global CSS styles to prevent horizontal scrolling.

When I decided to change the colour scheme, Copilot was used to implement this change rather than go through and do it manually. I also used it to implement explicit widths/heights on images after testing with Lighthouse.

#### Debugging

Copilot AI was used throughout for debugging. 
For example: 
- I asked it to check whether I had all the required closing tags for one section when I thought I might have missed a tag. 
- I asked it to tell me the specificty of bootstrap stylings so I could easily override them.

## Deployment

This site was deployed using Github Pages. 

From your github repository, navigate to the Pages area (within Settings) and choose to deploy from branch. Then choose the branch to deploy from (usually main) and click save.

At the top of the Pages page, you should have the link to your deployed site. You may need to refresh the page or wait a few minutes.

## Testing 

### Validation

#### HTML

I used [W3 HTML Validator](https://validator.w3.org/) to check my HTML. It gave me a warning that I had incorrectly used ari-labels on icons that were just decorative, so I removed these labels. 

#### CSS

I used [W3 CSS Validator](https://validator.w3.org/) to check my CSS. It found no errors.



### Manual Testing

I tested all of the internal links in desktop, tablet and mobile view using Chrome DevTools. The links all scrolled to the correst sections and the scroll stopped at the right place. I also tested the external links to make sure they opened to the correct sites and in a new tab. 

I used the keyboard to tab through the site to see whether it took me to the correct links. 

I used Chrome DevTools to check whether my site was responsive in all screen sizes. 

### Lighthouse

#### Performance 

My first Lighthouse score for performance was 79, mainly due to the LCP (hero image) loading and render delay times. 
<!-- image here -->
To improve this, I changed the hero image to be an img tag in the HTML rather than as a background-image from css.I set a defined width/height and adjusted this for mobiles with a media query.
I preloaded the image in the head, and set the loading within the img to "eager". 
I also embedded the CSS for my hero image in the head of the HTML rather than in the CSS file to reduce render delay. 

Additionally, I resized the image used for my hero image as it was slightly larger than would be used on the site, even with desktop screens.

For the rest of the site, I added lazy loading to all images excluding the hero image, and loaded the fonts from Google Fonts in the HTML rather than importing to the CSS. 

With these changes, my performance is now at 97 on Lighthouse.

<!-- image here -->

### Accessibility 

My accessibility score was at 98 to begin with so I did not make any changes due to the Lighthouse scores. I also tested this manually (see manual testing section).

### Best Practices

My Lighthouse score was at 79 to begin with, mainly due to displaying images with the incorrect aspect ratios.
I added explicit widths and heights to my images, and adjusted these to fit the aspect ratios of the original images. 

<!-- new score -->
## Credits

[North East London NHS](https://northeastlondon.icb.nhs.uk/about-us/about-nhs-north-east-london/our-statutory-duties/) - image taken from here for hero image.

[CQC](https://www.cqc.org.uk/what-we-do/how-we-do-our-job/safeguarding-people) - linked to in site, and image taken from here for carousel in "Further Information" section. <br>
[NHS](https://safeguarding-guide.nhs.uk/) - linked to in site, and image taken from here for carousel in "Further Information" section. <br>
[SCIE](https://www.scie.org.uk) - linked to in site, and image taken from here for carousel in "Further Information" section.  Also used for safeguarding research. <br>


[CaringforCare](https://caringforcare.co.uk/what-is-safeguarding-in-school/) - used for safeguarding research.

[Code Institute](https://codeinstitute.net/) - a small amount of Javascript code (navbar collapse when internal link clicked) was copied from a previous walkthough project.

[Copilot](https://copilot.microsoft.com/) - used for image generation (see AI use section)

[Balsamiq](https://balsamiq.com/) - used to create wireframes.

[W3 Validator](https://validator.w3.org/) - for HTML validation.




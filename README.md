
<h1 align="center">mrdhruvparikh.com</h1>

<h2 align="center">Professional Medical Portfolio</h2>

<h3 align="center">Code Institute Diploma in Software Development - Milestone Project 1</h3>

<h3 align="center">The last update to this file was: February 15, 2022</h3>

![mockuper](https://user-images.githubusercontent.com/17801129/154098389-9b671297-70cb-4983-8592-049acc86c8a0.png)

[View the live project here.](https://#)

### User Experience (UX) 

### Strategy

mrdhruvparikh.com will promote the surgical work of the neurosurgeon Mr Dhruv Parikh. The site is targeted at prospective and existing patients/clients and colleagues interested in the type of surgical work that Mr Parikh undertakes, and conditions that they may be experiencing. The site encourages visitors to make contact through the booking page.

#### User stories

First Time Visitor Goals
   1. Understand the main purpose of the site and learn more about Mr Parikh.
   2. Navigate through the site with ease to find content. 
   3. Understand what Mr Parikh does, see testimonials/feedback, make an enquiry.

Returning Visitor Goals
   1. Book an appointment.
   2. Give feedback.
   3. Find information about a condition I've been told I have. 

#### Client objectives 

The client (Mr Parikh) would like the site to:
   1. Present a professional brand to prospective and existing clients.
   2. Be a useful resource for information for patients before and after an appointment. 
   3. Encourage patient bookings.

#### Scope

The first deployment of the site will acheive following requirements: 
   1. Eye-catching layout which conveys a professional clinical brand.
   2. Clear layout with easy navigation.
   3. Information for patients which is clear and avoids overloading by using 'read more' function. 
   4. Centralised contact page for comments, feedback, booking enquiries.  
   5. Calls to action to encourage clients to book. 

Features not included in the initial viable product but to be included in future versions will include:
   1. Calendar feature for appointment bookings.
   2. Other formats of information for patients and testimonials including videos.

#### Structure 

#### Features and overall structure
 
* Navigation Bar
    * Featured on all pages, the nav bar is responsive and includes links to the Logo, Home, Conditions and Treatments, Research and Contact pages. It is identical in each page to allow for easy navigation.
    * This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

* Landing page
    * The landing includes a photograph with text overlay that highlights Mr Pariks surgical philosophy and forms part of the brand identity. This section introduces the user to Mr Parikh with an eye-catching image of Mr Parikh in theatre. 
    *  Below is a summary of Mr Parikh's professional career and a call to action to 'book your appointment'.  
    *  The third section of the landing page displays feedback/reviews from a sample of previous patients.    

* Conditions and Treatments 
    * The Conditions page will provide information about common conditions requiring neurosurgery. It will include information for patients. Conditions will be provided in a responsive drop down menu. 
    * This section is valuable to the user as they will be able to easily identify symptoms and information about treatment and prognosis. Mr Parikh intends to use this area of the website to offer patients an online resource to support the information they receive at appointments. 
    * Conditions covered
          * Acoustic neuroma 
          * Chordoma
          * Craniopharyngioma
          * Pituitary Tumours
          * Meningiomas

* Contact us
    * This section will include a form to request to book an appointment with general contact information below. 
* Research
    * This section will include titles of publications by Mr Parikh with links to PubMed citations. 
    * The citations list will be available as a downloadable pdf. 
* Footer 
    * The footer will include social media links and a copyright statement.

#### Skeleton 

#### Wireframes

Home Page Wireframe - [View](https://github.com/)

Mobile Wireframe - [View](https://github.com/)

Contact Us Page Wireframe - [View](https://github.com/)

#### Surface

#### Colour Scheme

The site will utilise blue/gray tone with images and clear grayscale text to evoke a professional modern brand. 

#### Typography

The Roboto font is the main font used throughout the site with Sans Serif as the fallback font should the site fail to load correctly. Roboto is a clean and widely used font on websites. Using a light font-weight gives a further professional appearance.

#### Imagery

The large, background hero image is designed to be striking and catch the user's attention. It also has a modern, clinical aesthetic. Further images are used throughout the site to provide focus for content, for example on the 'Conditions' pages. All a unified by muted blue/grey tones. 


### Technologies Used

#### Languages

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

#### Frameworks, Libraries & Programs Used

1. [Bootstrap 5.0.2:](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [LogoMakr:](https://logomakr.com/)
    - LogoMakr was used to create the logo.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

### Testing

#### UX Testing 

UX was assessed by Mr Parikh and 2 first time visitors on mobile and desktop devices.  

#### Validator Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate the project to ensure there were no syntax errors.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)

#### Browser and Device Testing 

Project has been viewed and debugged using Chrome DevTools. The site looks and works as intended on different screen sizes including mobile, tablet and desktop.
Functionality of different browsers has been assessed including Safari, Chrome, Firefox and Opera.

#### Bugs and Fixes 

Bug: 'Read more' buttons not aligning when viewed on desktop.

<img width="1348" alt="Screenshot 2022-02-14 at 10 44 11" src="https://user-images.githubusercontent.com/17801129/154084639-a2298e5a-ecd2-4ccb-b75c-ba6b05e360c8.png">

Fix: Read more placed into separate div with above div given min-height.

Bug: Negative space showing on some pages when viewed on mobile device. 
   
<img width="832" alt="Screenshot 2022-02-14 at 10 44 19" src="https://user-images.githubusercontent.com/17801129/154084716-fddc77b3-3fe8-49f5-953f-d19092474ca8.png">

   Fix: Missing 'container' class added above bootstrap 'row' class. 

### Deployment

* The site was deployed to GitHub pages. The deployment steps taken were:
    * In the GitHub repository, navigate to the Settings tab
    * From the source section drop-down menu, select the Master Branch
    * Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
* The live link can be found here - [insert link]

### Credits

Content
* Icons used throughout the site were supplied by Font Awesome [insert link]
* The site Logo was produced using LogoMakr [insert link]
* Fonts used throughout the site were supplied by Google Fonts  [insert link]
* Text content on the 'Conditions + Treatments' pages was edited from NHS Direct [https://www.nhs.uk/]

Media
* The photos used throughout the site were supplied by the client. Those not supplied were sourced from the open source platform Pexel [https://www.pexels.com/]



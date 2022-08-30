# EMOWAA

## Table of Contents
1. [General Information](#General-information)
2. [Technologies](#Technologies)
3. [Testing](#Testing)
4. [Depolyment](#Depolyment)
5. [Credits](#Credits)
***


## General Information

**EMOWAA** is an illustrative website about a museum that houses a collection of artefacts and imagery (primarily Bronze and copper carvings from the ancient Benin Kingdom). Although, the museum only exists presently as an idea/proposal, this website aims to provide insight on a probable collection of artefacts to be housed in the hypotehtical museum.

The website also aims to serve as a guide to the structural layout of the museum and provide a platform which guests can have a sneak preview of the collection of artefacts on display and schedule a tour of the museum. View the live site [here]( https://deenafe.github.io/edomuseum/)


![](docs/mockup-screenshot.png)  

***
### **Features**

### *Navigation*  

* The navigation menu is consistent in all 3 pages of the website and links to the Home, Collection, Bookings pages and the Logo which navigates to the Home page.
* This will allow users to easily navigate across the pages without having to use the "back" button

![](docs/nav-capture.png)

### Landing Page 

 #### *The Landing page image*  
 *   The landing page include a picture of one the most valuable bronze artefacts in the history of Benin Kingdom
  *  The provides a visual clue to the user that the museum has noteworthy artefacts on display

  ![](docs/capture-landing-image.png)

   

  ####  *Museum Information*  
  *   This section aims to provide users with information on the location of the museum and importance of the artworks on display
 *   It also provides a bit of background information on the source of artefacts on display

 ![](docs/capture-museum-info.png)

  ####  *Museum Layout*  
  *   This aims to provide a visual illustration of various sections of the museum
  *   It is meant to help users get a hint of layout of the museum prior to booking a visit

  ![](docs/capture-museum-layout.png)

  ####  *Footer*
  *   This contains links to four social media platforms that will be displayed as icons. All the links will open in new tabs, so users don't have to leave the website to access the social nedia websites.
  *    The footer is important to enable users connect via social media to get latest information about the museum and new artefacts on display.

  ![](docs/capture-footer.png)


### Gallery Page  

   #### *Gallery*

  *  The gallery contains images of some of the important imagrey and artefacts on display.
  *  It's intended to provide a sneak preview of what is on display at the museum.

![](docs/capture-gallery.png)

### Booking Page  

 #### *Open Times and Reservations*

 *   This page provide information on the open days and open times to the user as well a phone contact number.
 *   It provides users with a platform to book a tour of the museum and users are be required to input their Names, Email Address, Intended date and time of visit, and number of persons coming on the visit.

 ![](docs/capture-booking-page.png)

 ### Contact Page  

 #### *Contact Form*

 *   A contact form which allows users to input their names, email address and message.
 *   It enables users to contact the museum if they have any enquiries outside the scope of information provided on the website.

![](docs/capture-contact-form.png)


### Existing Features  

* Information on museum 
* Responsive gallery
* Responsive design
* Captions for gallery pictures
* Reservation page
* Contact form


### Features Left to Implement  

* An interactve map to help users get the precise location of the museum

* A slide show of the main image on the landing page to consist of at least 5 diffrent images of related artefacts.

* A modal to be added to the collection page, so when clicked, each image can be displayed on top of the gallery with a caption.

***


## Technologies  
*** 

  **HTML**
   * The structure of the web pages was done using html. 

   **CSS**
   * The decorative features of the web pages was done using CSS in an external file.

   **Font Awesome**
   * The social media icons was sourced from https://fontawesome.com/ 

   **Gitpod Workpspace**
  *  Used to commit and push code during the development of the Website.

  **GitHub**
  *  Code is hosted and deployed on GitHub.

***
## Testing   

***

   ### Responsiveness
All the pages were tested for responsiveness on various device screens ranging from 280px.

The design features was consistent when tested on Chrome, Mozilla Firefox, Opera and Edge browsers.

All pages of the website were responsive when tested on the following devices using Chrome Developer tools.:

1. iPhone Se
2. iPhone 12
3. Samsung Gakaxy 8+
4. iPad Air
5. iPad Mini
6. Galaxy Fold
7. Samsung Galaxy A51

The responsive design features was also consistent when the website was manually opened on the following IOS and Andriod devices:

1. iPhone X 
2. Samsung Galaxy A21s
3. Huawei Honor 8

 ### Functional Testing
   
**Navigation Links**

   The navigation links on all pages was tested to ensure functionality by navigating to the correct page when clicked. 

   * The navigation link to the Home page is *index.html*
   * The navigation link to the Collection page is *collection.html*
   * The navigation link to the Bookings Page is *bookings.html*
   * The navigation link to the Contact Form page is *contact.html*

    The Logo has an anchor with *index.html* as the *href* attribute so clicking the Logo from any page of the website will navigate to the Home Page. The navigation links (excluding the Logo) have a hover color which was present which was functional when tested.


 ### Form Testing

     There are 2 forms on the website and both forms can be accessed from the navigation links on any all pages of the website. The forms present on the website are:

* Online Reservation Form

      The following test scenarios were performed for the Online Reservation Form

      *Scenario One - Correct Inputs*

      Steps to test:

1. From the Home page navigate to the Booking page.
2. Input the following data into the form below the heading "Make Online Reservation"
      * Name: Bless
      * Email Address: shdhd@outlook.com
      * Date: 2022-08-25
      * Time: 23:39
      * Number of Persons: 3
3. Click "Book Now"      
4. Users should be directed to [Code Institute Form Dump](https://formdump.codeinstitute.net/) with a congratulatory message indicating the form was correctly submitted.

Expected Result:
    *Form submits with no errors and redirects to https://formdump.codeinstitute.net/*

Outcome:
    *Website behaved as expected with no errors or warnings and redirected to https://formdump.codeinstitute.net/*    

![](docs/correct-entry.png)


*Scenario Two - Missing Name*

      Steps to test:

1. From the Home page navigate to the Booking page.
2. Input the following data into the form below the heading "Make Online Reservation"
      * Name: 
      * Email Address: shdhd@outlook.com
      * Date: 2022-08-25
      * Time: 23:39
      * Number of Persons: 3
3. Click "Book Now"      

Expected Result:
    *The form does not submits and displays and error requesting the user to fill out the "Name" field*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.* 

![](docs/missing-name.png)

*Scenario Three - Missing Email*

      Steps to test:

1. From the Home page navigate to the Booking page.
2. Input the following data into the form below the heading "Make Online Reservation"
      * Name: Bless
      * Email Address: 
      * Date: 2022-08-25
      * Time: 23:39
      * Number of Persons: 3
3. Click "Book Now"      

Expected Result:
    *The form does not submits and displays and error requesting the user to fill out the "Email" field*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.* 

![](docs/missing-email.png)

*Scenario Four - Incorrect Email Input*

      Steps to test:

1. From the Home page navigate to the Booking page.
2. Input the following data into the form below the heading "Make Online Reservation"
      * Name: Bless
      * Email Address: shdhdoutlook.com
      * Date: 2022-08-25
      * Time: 23:39
      * Number of Persons: 3
3. Click "Book Now"      

Expected Result:
    *The form does not submits and displays and error requesting the user to include an @ sign in the email address*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.*  

![](docs/incorrect-email.png) 

    
*Scenario Five - Missing Date*

      Steps to test:

1. From the Home page navigate to the Booking page.
2. Input the following data into the form below the heading "Make Online Reservation"
      * Name: Bless
      * Email Address: shdhd@outlook.com
      * Date: 
      * Time: 23:39
      * Number of Persons: 3
3. Click "Book Now"      

Expected Result:
    *The form does not submits and displays and error requesting the user to fill out the "Date" field*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.*   

![](docs/missing-date.png) 

 *Scenario Six - Missing Time*

      Steps to test:

1. From the Home page navigate to the Booking page.
2. Input the following data into the form below the heading "Make Online Reservation"
      * Name: Bless
      * Email Address: shdhd@outlook.com
      * Date: 2022-08-25
      * Time: 
      * Number of Persons: 3
3. Click "Book Now"      

Expected Result:
    *The form does not submits and displays and error requesting the user to enter a valid time value*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.*   

![](docs/missing-time.png) 


  
* Contact Form

The following test scenarios were performed for the Contact Form

*Scenario One - Correct Inputs*

      Steps to test:

1. From the Home page navigate to the *Contact Us* button.
2. Input the following data into the form below the heading "Contact"
      * Name: Bless
      * Email Address: shdhd@outlook.com
      * Message: Test Message
3. Click "Send Message"      
4. Users should be directed to [Code Institute Form Dump](https://formdump.codeinstitute.net/) with a congratulatory message indicating the form was correctly submitted.

Expected Result:
    *Form submits with no errors and redirects to https://formdump.codeinstitute.net/*

Outcome:
    *Website behaved as expected with no errors or warnings and redirected to https://formdump.codeinstitute.net/*    

![](docs/correct-contact-message.png)   



*Scenario Two - Missing Name*

      Steps to test:

1. From the Home page navigate to the *Contact Us* button.
2. Input the following data into the form below the heading "Contact"
      * Name: 
      * Email Address: shdhd@outlook.com
      * Message: Test Message
3. Click "Send Message"      

Expected Result:
    *The form does not submits and displays and error requesting the user to fill out the "Name" field*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.*     

![](docs/missing-name-contact.png) 


*Scenario Three - Missing Email*

      Steps to test:

1. From the Home page navigate to the *Contact Us* button.
2. Input the following data into the form below the heading "Contact"
      * Name: Bless
      * Email Address: 
      * Message: Test Message
3. Click "Send Message"      

Expected Result:
    *The form does not submits and displays and error requesting the user to fill out the "Email" field*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.*     

![](docs/missing-email-contact.png)   



*Scenario Four - Incorrect Email*

      Steps to test:

1. From the Home page navigate to the *Contact Us* button.
2. Input the following data into the form below the heading "Contact"
      * Name: Bless
      * Email Address: shdhdoutlook.com
      * Message: Test Message
3. Click "Send Message"      

Expected Result:
    *The form does not submits and displays and error requesting the user to include an @ in email address*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.*     

![](docs/incorrect-email-contact.png)   



*Scenario Five - Missing Message*

      Steps to test:

1. From the Home page navigate to the *Contact Us* button.
2. Input the following data into the form below the heading "Contact"
      * Name: Bless
      * Email Address: shdhd@outlook.com
      * Message: 
3. Click "Send Message"      

Expected Result:
    *The form does not submits and displays and error requesting the user to fill out the "Message" field*

Outcome:
    *Website behaved as expected, error message was displayed and the form did not submit.*     

![](docs/missing-contact-message.png)   


### Testing Social Media Icons / Links

Testing was performed on the Font Awesome Social Media icons in the footer to ensure that each one opened in a new tab.

Each item opened a new tab when clicked as expected and correct hover opacity effect was present.

  ###  Accessibility  

 [Wave](https://wave.webaim.org/) was used to evaluate the accessibility of all pages to ensure the website meets the WCAG Web Accessibilty Standards. The results of the accessibility testing showed that the following were met:

  * There were no color contrast errors in all the pages.
  * The heading elements are properly structured to facilitate page navigation for users of assistive technologies.
  * All form labels are present and associated with a form control.
  * The HTML lang atrribute is present to allow screen readers to read the content appropriately.
  * Images and external links have associated alternative text and aria-labels to be read by screen readers.

     The objective of performing the accessibility testing was to ensure the website is:

    * Perceivable
    * Operable
    * Understandable
    * Robust

*However, due to time constraints, I was unable to conduct the manual testing for accessibility using a 
screen reader.*


###  Lighthouse Testing

![](docs/lighthouse-index.png) 

![](docs/lighthouse-collection.png)

![](docs/lighthouse-bookings.png)

![](docs/lighthouse-contact.png) 



## Validator Testing   

*HTML*
* No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)


![](docs/capture-index.png)
![](docs/capture-collection.png)
![](docs/capture-bookings.png)
![](docs/contact-capture.png)



*CSS*
* No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)

![](docs/capture-index.png)


## Bugs

### Identified Bugs

* I had issues with the responsiveness of the nav links on the left side of the page and the Logo in the center of the page. I initially used floats but the nav links and log become distorted when the screen size scales down below 800px.

* To resolve the bug, I used flex for both the nav-header container and the nav-links to the left. I also had to introduce another link (Contact Us) in the nav-header container to the right of the page and use the justify center:space-between property to create even spacing between the 3 elements and this resolved the distortion of the Logo's position.

I also had to resize the images on the Museum layout section using paint and give them a fixed height to get the images to fit into the container.

### Unfixed Bugs   
There was no identifiable unfixed bugs.

***
## Deployment 
***

### Github Pages

**The site was deployed to GitHub pages. The steps to deploy are as follows:**

* In the GitHub repository, navigate to the Settings tab
* From the menu on left select 'Pages'
* Click 'Save'
* The live link will be found with the message "Your site is live at" -  https://deenafe.github.io/edomuseum/

### Clone the Repository Code Locally  

**Navigate to the GitHub Repository you want to clone to use locally:**

* Click on the code drop down button
* Click on HTTPS
* Copy the repository link to the clipboard
* Open your IDE of choice (git must be installed for the next steps)
* Type git clone copied-git-url into the IDE terminal

***
## Credits  
***

### Content  

*  The idea for the creation of the museum is from the EMOWAA Trust headed by Phillip Ihenacho.
  
*  The code to create a responsive gallery using flexbox was from a [Youtube Tutorial video by "Cem Eygi Media"](https://www.youtube.com/watch?v=QmZNFnqwu74).

*  The code to create a booking page containing Open Times and booking form was from a [Youtube Tutorial video by "brilex 007"](https://www.youtube.com/watch?v=ShpH_1EPox0).

* The template for my readme.md file was sourced from https://github.com/Gareth-McGirr/tacos-travels and facilitated by my mentor **Daisy Mc Girr**.

### Media   

*  The main image and photos in the gallery are from Wikipedia and https://smarthistory.org/imagery-power-benin-bronze-plaques/ .

 * The concept for the museum layout originally belong to David Adjaye who is a renowed architect and I got the images from an article written by Alex Greenberger for [Artnews](https://www.artnews.com/gallery/art-news/photos/david-adjaye-emowaa-benin-city-designs-1234576585/5_education-spaces/).  

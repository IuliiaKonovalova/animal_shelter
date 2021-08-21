![Animal Shelter logo](assets/images/animal_shelter_logo.png)

---

<center>

![size](https://img.shields.io/github/languages/code-size/IuliiaKonovalova/animal_shelter?color=blue&label=size&logo=3.6MB)
</center>



# *Animal Shelter*

The Animal Shelter website allows people to learn about the company "Animal Shelter" and find information about animals living in this shelter. The visitors of the website could quickly contact the company about adapting animals as well as making a donation.

![Responsive Mockup](assets/images/responsive_mockup.png)

## Features

+ ### Navbar

+ ##### Navigation
    - Positioned at the top of the page.
    - Contains logo of the company on the left side.
    - Contains navigation links on the right side:
        * HOME - leads to the home page where users can learn about the company Animal Shelter.
        * GALLERY - leads to the gallery page where users can see available animals in the Animal Shelter.
        * CONTACT - leads to the contact form page where users can fill out the form in order to get in touch with the company.
    - The links have animated hover effect.
    - The navigation is clear and easy to understand for the user.
    ![NavBar desktop](assets/images/navbar_desktop.png)

    - The navigation bar is responsive:
        * On tablets: navigation bar is split into to lines: the first line filled with the logo and the second line filled with links. All elements are centered.
        ![NavBar Tablets](assets/images/navbar_tablets.png)

        * On mobile devices: 
            - navigation bar filled with the logo in the center and a hamburger menu implemented on the left side of the navigation bar.      
            ![NavBar Mobile Closed](assets/images/navbar_mobile_closed.png)
        
            - When the hamburger menu is clicked, there is dropdown menu with the links in the same order.
            ![NavBar Mobile Open](assets/images/navbar_mobile_open.png)



---

+ ### Home Page

    - Represent: 

        * the main idea of the company.
        * Emphasize the strong points of the company.
        * Shows feedback from satisfied clients.
        * Invites to fill out the contact form.


    ![Home Page](assets/images/home_page.png)

---

+ ##### Hero Section

    - Hero section have a fixed background image.

    - Hero section have the block section below the image that consist:

        * The name of the company.
        * Short description of the company's philosophy.
        * Contact button that leads directly to the contact page.

    
    ![Hero Section](assets/images/hero_section.png)

--- 

---    
+ ##### Highlights Section

    - Hightlight Section has 4 cards with strong descriptive characteristics of the company.

    - Tells website visitors how well animals are in the Animal Shelter.

    - Attracts viewers to use this company for animal adaption.

    
    ![Highlights Section](assets/images/main_cons.png)


    ---
+ ##### Testimonials Section

    - Testimonials Sectionhas three feedbacks from people who were satisfied with the company's service.

    - Each card has a picture of an animal with its owner.

    - Each card has a story from the people who had an experience of using the Animal Shelter.

    - Each card has a name of the pet's owner.

​
    ![Testimonials Section](assets/images/testimonials.png)


---
+ ##### Call to Action Section

    - Call to Action Section has an explicit message for the visitors of the website to contact the company.

    - Is also has a button that directs to the contact page.
​
    ![Call to Action Section](assets/images/call_to_action.png)


---
+ ##### Footer

    - Footer contains social media links that open in a new tab.
​
    ![Footer](assets/images/footer.png)
​
---
+ ### Gallery Page

    - Gallery page has a hero image and an introduction message for the visitors that contains an incentive to contact the company.

    - It has a button right after the introduction message that leads to the contact form page.

    - It has photos of the animals that a present in the Animal Shelter in real-time.

        - The gallery is responsive: the size of the photo depends on the user's screen.
        - Each image has a description of the animal that appears on hover.
        - descriptional information contains the name of the animal and its characteristics.

    - It has a call to action section below the gallery with the incentivizing message and the button that leads to the contact form.

    - It has a footer identical to the home page's footer.
    
​
    ![Tour page](assets/images/gallery_page.png)


---
+ ### Contact page

    - Contact page has a contact form:

        - All text input fields are customized.
        - Labels are animated when the input field is in focus and are not empty.
        - All inputs are set to be required to fill out.
        - It has to checkboxes for the visitors to fill voluntary:

            - The 1st is - ADAP, which helps the company to understand the motive of the visitor.
            - The 2nd is - DONATE, which motivates users to consider financial support for the company. 

        - The submit button is animated on hover.

    - The page is responsive on all common screen sizes.

    - The submit button leads to the response page.
​
    ![Contact page](assets/images/contact_form_page.png)


---
+ ### Response page

    - Response page appears after submitting the contact form.
    - It contains the thank you message and the promise to get in touch with the applicant within 24 hours.

    ![Response page](assets/images/response_page.png)


---
## User Stories

### First Time Visitor Goals:

* As a First Time Visitor, I want to easily understand the main purpose of the site, so I can learn more about the organization.
* As a First Time Visitor, I want to be able to easily navigate through the website, so I can find the content.
* As a First Time Visitor, I want to see the testimonials, so I can see whether the organization is trustworthy.

### Reterning VisitorGoals:

* As a Returning Visitor, I want to see various pets, so that I can pick from.
* As a Returning Visitor, I want to see information about animals, so that I can learn about each animal and make a prudent decision.
* As a Returning Visitor, I want to find a way to get in contact with the organization, so that I can ask additional questions or send a request about a particular animal.
* As a Returning Visitor, I want to find community links, so that I can learn more about the organization.

### Frequent Visitor Goals:
* As a Frequent User, I want to check whether there are any changes with available animals, so I can make a choice which animal to adapt.
* As a Frequent User, I want to have options for the reason to contact the company, so I can get an explicit answer to my email. 

---

## Testing

In order to confirm the correct functionality, responsiveness, and appearance:

+ The website was tasted on the following browsers: Chrome, Firefox, Brave.
+ The website was checked by devtools implemented in Firefox and Chrome browsers.
+ The website was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).
+ The functionality of the links in the website was checked as well by different users.

---
​
### Bugs
+ ##### Solved bugs
    1. The testimonials pictures had a square shape in Brave browser on a mobile phone when the border radius had been set to 50%. It was due to the outline properties settings instead of the border
    
        *Solutions:* Outline was replaced with border properties.
    
    1. The gallery image descriptions were not appearing on the picture when hovering it as the position of the .image_content was set to fixed.
        
        *Solution:* The .image_content position was set to absolute, with the top: 0, left: 0, and added padding on the .image_content. 

    1. Footer on the contact page was reducing the size of the screen and shrank the contact form as the height of the background image was set to calc(100vh-the size of the footer)
        
        *Solution:* The height of the image was set to 100hv, and the display of the footer was set to fixed.
    ---
+ ##### Unsolved bugs
    - None.

---
## Validator testing
+ ##### HTML
    - No errors or warnings were found when passing through the official W3C validator.
    
+ ##### CSS
    - No errors or warnings were found when passing through the official W3C (Jigsaw) validator except the warnings that all: unset properties do not exist.

+ ##### Accessibility and performance 
    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    ![Performance score](assets/images/performance.png)

---
## Deployment
+ The website was deployed to GitHub pages and can be accessed by the link: [Animal Shelter](https://iuliiakonovalova.github.io/animal_shelter/).

---
## Credits

+ #### Content

    - Inspiration for the gallery hover effect came from the article "How to add a gradient to overlay to a background image using just CSS and HTML" published the website [Web Dev etc](https://webdevetc.com).
    - Inspiration for the responsive hamburger navbar came from [Kevin Powell](https://www.youtube.com/user/KepowOb) on his YouTube channel.
    - The content was checked by my dear friend Zulya.

+ #### Media

    - All the images for the website were taken from [Unsplash](https://unsplash.com/).
    - All images were compressed by using the website [Compress JPEG](https://compressjpeg.com/).
    - All images for the gallery were resized by using the website [IMGonline.com.ua](https://www.imgonline.com.ua/eng/resize-image.php).
    - Images for the README file were made with [GIMP](https://www.gimp.org/).


---
## Wireframes

+ Mobile devices

![Home Page. Mobile Screen](assets/images/mobile_home_page.png)
![Gallery Page. Mobile Screen](assets/images/mobile_gallery_page.png)
![Contact Page. Mobile Screen](assets/images/mobile_contact_form_page.png)
![Response Page. Mobile Screen](assets/images/mobile_response_page.png)


+ Tablets

![Home Page. Tablet Screen](assets/images/tablet_home_page.png)
![Gallery Page. Tablet Screen](assets/images/tablet_gallery_page.png)
![Contact Page. Tablet Screen](assets/images/tablet_contact_form_page.png)
![Response Page. Tablet Screen](assets/images/tablet_response_page.png)

+ Desktop

![Home Page. Desktop Screen](assets/images/desktop_home_page.png)
![Gallery Page. Desktop Screen](assets/images/desktop_gallery_page.png)
![Contact Page. Desktop Screen](assets/images/desktop_contact_form_page.png)
![Response Page. Desktop Screen](assets/images/desktop_response_page.png)
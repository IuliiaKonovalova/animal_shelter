# TESTING


## Compatibility

In order to confirm the correct functionality, responsiveness, and appearance:

+ The website was tested on the following browsers: Chrome, Firefox, Brave.

    - Chrome:

    ![Chrome](documentation/browsers_google.gif)

    - FireFox:

    ![FireFox](documentation/browsers_firefox.gif)

    - Brave:

    ![Brave](documentation/browsers_brave.gif)

## Responsiveness


+ The website was checked by devtools implemented in Firefox and Chrome browsers.

    - Main Page:

    ![Main Page](documentation/responsiveness_main_page.gif)

    - Gallery Page:

    ![Gallery Page](documentation/responsiveness_gallery_page.gif)

    - Contact Page:

    ![Contact Page](documentation/responsiveness_contact_page.gif)

    - Response Page:

    ![Response Page](documentation/responsiveness_response_page.gif)

+ The website was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).

    - Desktop Screens:

    ![Desktop 1024x600](documentation/desktop_1024_600.gif)
    ![Desktop 1024x800](documentation/desktop_1024_800.gif)
    ![Desktop 1366x768](documentation/desktop_1366_768.gif)
    ![Desktop 1440x900](documentation/desktop_1440_900.gif)
    ![Desktop 1600x900](documentation/desktop_1600_900.gif)
    ![Desktop 1680x1050](documentation/desktop_1680_1050.gif)
    ![Desktop 1920x1080](documentation/desktop_1920_1080.gif)
    ![Desktop 1920x1200](documentation/desktop_1920_1200.gif)

    - Tablet Screens:

    ![Tablet 600x960](documentation/tablet_600_960.gif)
    ![Tablet 768x1024](documentation/tablet_768_1024.gif)
    ![Tablet 800x1280](documentation/tablet_800_1280.gif)
    ![Tablet 1024x768](documentation/tablet_1024_768.gif)
    ![Tablet 1366x1024](documentation/tablet_1366_1024.gif)
    ![Tablet Kindle 768x1024](documentation/tablet_kindle_768_1024.gif)

    - Mobile Screens:

    ![Mobile 320x480](documentation/mobile_320_480.gif)
    ![Mobile 320x568](documentation/mobile_320_568.gif)
    ![Mobile 360x640](documentation/mobile_360_640.gif)
    ![Mobile 375x667](documentation/mobile_375_667.gif)
    ![Mobile 384x640](documentation/mobile_384_640.gif)
    ![Mobile 411x731](documentation/mobile_411_731.gif)
    ![Mobile 414x736](documentation/mobile_414_736.gif)

+ The functionality of the links in the website was checked as well by different users.

## Manual testing

| feature | action | expected result | tested | passed | comments |
| --- | --- | --- | --- | --- | --- |
| Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Gallery | Click on the "Gallery" link | The user is redirected to the gallery page | Yes | Yes | - |
| Contact | Click on the "Contact" link | The user is redirected to the contact page | Yes | Yes | - |
| Footer | | | | | |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Twitter icon in the footer | Click on the Twitter icon | The user is redirected to the Twitter page | Yes | Yes | - |
| YouTube icon in the footer | Click on the YouTube icon | The user is redirected to the YouTube page | Yes | Yes | - |
| Home page | | | | | |
| "Contact Us" button in Hero section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| "Contact Us" button in Call to action section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Gallery page | | | | | |
| "Contact Us" button in Hero section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Image in the gallery | User hover the image | Pet's name and description appear on the image | Yes | Yes | - |
| "Contact Us" button in Call to action section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Contact page | | | | | |
| First name input | Enter the first name | The first name is entered | Yes | Yes | If user doesn't enter the first name, the error message appears |
| Last name input | Enter the last name | The last name is entered | Yes | Yes | If user doesn't enter the last name, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears. If user enters not valid email, the error message appears |
| Adopt and donate checkbox | Click on the checkbox | The checkbox is checked | Yes | Yes | These checkboxes are not required as the user can choose not to adopt or donate and other reasons for contacting |
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |
| Response page | | | | | |
| Response message | The user will be automatically redirected to the home page after 10 seconds | The user is redirected to the home page | Yes | Yes | - |


---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.


    ![Home Page HTML Validator](documentation/w3_validator_home_page.png)
    
  #### Gallery Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Gallery Page HTML Validator](documentation/w3_validator_gallery_page.png)

  #### Contact Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/w3_validator_contact_page.png)

  #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/w3_validator_response_page.png)
    
+ ### CSS
  No errors or warnings were found when passing through the official W3C (Jigsaw) validator except:
    
    - 3 errors regarding *all: unset*: "Property all doesn't exist. The closest matching property name is fill : unset".

    - Even though this error is present, I don't believe it is 100% accurate, and more information can be found [here](https://developer.mozilla.org/en-US/docs/Web/CSS/all)

  ![CSS Validator errors](documentation/w3_validator_css_errors.png)
  
    - 43 warning regarding the use of *:root variables*: "Due to their dynamic nature, CSS variables are currently not statically checked".
    
  ![CSS Validator errors](documentation/w3_validator_css_warnings.png)


+ ## LightHouse report

    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  ### Home page

  ![Home Page Lighthouse](documentation/lighthouse_home_page.png)

  ### Gallery page

  ![Gallery Page Lighthouse](documentation/lighthouse_gallery_page.png)

  ### Contact page

  ![Contact Page Lighthouse](documentation/lighthouse_contact_page.png)

  ### Response page

  ![Response Page Lighthouse](documentation/lighthouse_response_page.png)

---
​
## Bugs
+ ### Solved bugs
    1. The testimonials pictures had a square shape in Brave browser on a mobile phone when the border radius had been set to 50%. It was due to the outline properties settings instead of the border
    
        *Solutions:* Outline was replaced with border properties.
    
    1. The gallery image descriptions were not appearing on the picture when hovering it as the position of the .image_content was set to fixed.
        
        *Solution:* The .image_content position was set to absolute, with the top: 0, left: 0, and added padding on the .image_content. 

    1. Footer on the contact page was reducing the size of the screen and shrank the contact form as the height of the background image was set to calc(100vh-the size of the footer)
        
        *Solution:* The height of the image was set to 100hv, and the display of the footer was set to fixed.
    ---
+ ### Unsolved bugs
    - None.
+ ### Mistakes
    - Mistakes were made while committing changes. I used past simple tense in commits due to the habit when I just started working on this project.
    - While progressing in my code I learned to use present simple tense in commits.

---
# Testing

* 1. __Lighthouse__
 To identify and fix common problems affecting my sites Performance, Best Practices, Accessibility and SEO. By right clicking and choosing inspect or
pressing the keyboard combination "Ctrl + Shift + I" I was able to view and edit my code before making changes.


Desktop Perfomance
![Lighthouse check](https://user-images.githubusercontent.com/79915855/120713597-0f9f6e80-c4ba-11eb-8285-e4ab3ba4100c.jpg)


Mobile Perfomance
![Lighthouse check](https://user-images.githubusercontent.com/79915855/120713597-0f9f6e80-c4ba-11eb-8285-e4ab3ba4100c.jpg)


* 2. [The W3C Markup Validation Service](https://validator.w3.org/)
No errors or warnings shown for HTML
![website-validation](https://user-images.githubusercontent.com/79915855/120714080-a79d5800-c4ba-11eb-81ba-f74081b6d543.jpg)



* 3. [Jigsaw W3](https://jigsaw.w3.org/css-validator/)
No errors or warnings shown for CSS.
![css-validation](https://user-images.githubusercontent.com/79915855/120714411-111d6680-c4bb-11eb-8eff-d100bd69921a.jpg)

# Manual Testing

## All pages

* __Navigation Bar:__
    * Home - When clicking on Home I am directed to the Home Page and the text changes from white to light grey to indicate that I am on the home page. The other nav buttons
    have a working hover affect where text changes color on hover
    * About Us - When clicking About us I am directed to the About Us page and the hover affect _worked as expected_
    * AJR Fitness logo - when clicked I am redirected back to the home page, this _worked as expected_
    * Text - Font family is consistent on all pages, and no grammar/spelling mistakes were found.
    * Media - I checked that all the Images load properly on all the pages. 
    * Responsiveness - I checked if all the pages and its contents were responsive using Chrome inspect. Also viewing each page using an iPhone, iPad, Macbook and other devices. 
* Footer - When selecting the social media icons I am redirected to the different appropriate websites _as expected_
* Hero Image - Loads on all pages.

* __Home Page__
    * AJR Fitness logo visible and adjusts in size depending on what device is being used. _Worked as expected_
    * Service buttons text turns light grey when hovered over and direct me to the correct page. _Worked as expected_

* __About Us Page__
    * Testimonial Images load _as expected_

* __Services Page__
    * Flipping Images animation - When I hover over the individual services, the image flips 180 degrees and shows information of times. Once my mouse is removed it returns back to its initial state. _Worked as expected_
    * Book now button text turns light grey when hovered over and directs me to the contact page. _Worked as expected_

* __Contact Page__
    * I tested each field on the contact form by entering the appropriate information. _Worked as expected_
    * Dropdown on subject section initially displaying "Choose an option" and changes once a different selection is made. _Worked as expected_ 
    * If fields are not completed there is an error message. _Worked as expected_
    * Maps page displays desired location but is also interactive. _Worked as expected_
    * Send button works and redirects you to Code institutes formdump site. __See Below__
![Code-submit](https://user-images.githubusercontent.com/79915855/120714669-66f20e80-c4bb-11eb-854f-4f2f3b6925cd.jpg)


    * If I do not complete all fields and try to send form, an error message appears. _Works as expected_
    * If I do not use an @ in the email address, message pops up. _Worked as expected_
![email-test](https://user-images.githubusercontent.com/79915855/120714737-80935600-c4bb-11eb-8fcd-4a4ed45c86ec.jpg)

## Testing my User Goals

* __User goals:__

* As a first time visitor, I want to immediately understand what the website is about
    * Upon entering the website, users are greeted with a sleek and easily readable navigation bar. A high quality hero image which immediately allows the user to understand what the website is about. 
    * The visible logo on the top left of the landing page is short and simple, making it self-explanatory as to what the website offers.

* As a first time visitor, I want to be able to easily navigate and interact with the website
    * The site has beeen designed to allow the user to quickly navigate through the pages without having to suffocate the user, it has breif yet informative information on each page. Each button explains clearly where the user will end up. 
    * The main page provides a service button which takes the user directly to the specific part of the Service page. So the user doesn't have to scroll
    * The Service page has a BOOK now button which upon click directs them to the Contact page where they can fill out their details with ease. 
    * The logo is clickable and appears on every page which directs you to the home page.
    * Each button including the nav bar has a hover effect which changes to a different colour so the user understands where exactly he will be directed to. And the active page is a different colour to the rest which avoids confusion.

![navigation](https://user-images.githubusercontent.com/79915855/120714797-9a349d80-c4bb-11eb-89b4-fa1f3de2c29f.jpg)

* As a first time visitor, I want to feel comfortable that AJRF is provide the best services 
* As a potential customer, I want to be able to see what others think of AJR Fitness
    * On the about us page, there is a brief description explaining the certifications that each professional at AJRF has, allowing the user to feel comfortable in their hands.
    * Towards the bottom of the page there are three different testimonials and how AJRF has helped the happy customers.
    ![testimonial](https://user-images.githubusercontent.com/79915855/120714827-a3be0580-c4bb-11eb-8ac1-a792b15bc051.jpg)


* As a potential customer, I want to be able to book a class, view times and/or make an enquiry
    * The services page provides the class times on the images.
    * After viewing the different services on the Service page the user can click the BOOK now button directing them to the Contact page where they are able to easily fill out the form and choosing an appropriate subject. 

![book](https://user-images.githubusercontent.com/79915855/120714842-aa4c7d00-c4bb-11eb-8e8f-74c052289244.jpg)
![times](https://user-images.githubusercontent.com/79915855/120714866-b33d4e80-c4bb-11eb-9816-5be61cd9e8d0.jpg)


* As a potential customer, I want to be able to follow AJRF on social media
    * On the footer of each page there are four social media links which, when clicked on, the user will be directed to another page.
![social media](https://user-images.githubusercontent.com/79915855/120714887-b9332f80-c4bb-11eb-91e8-df41f2a70dfe.jpg)

* As a potential customer, I want to be able to know the location of the classes and if I can directly contact them via telephone.
    * On the contact page, the user can see a pinpoint location and interact with the map to view any nearby POI's such as travel options.
    * A telephone number is provided on the contact page.
![maps](https://user-images.githubusercontent.com/79915855/120714906-bf291080-c4bb-11eb-9b7d-940176e32cd6.jpg)

## Futher Testing

* The website was tested on various different platforms, including, Google Chrome, Internet Explorer, Microsoft Edge and Safari Browsers
* The website was viewed on a variety of devices such as Macbook, iPhone 12 Pro, iPhone 7 and desktop.
* The website was also reviewed for it's responsiveness by inspecting the page on Google chrome.
* All contents was run through grammarly to avoid spelling/grammar errors.



# Pete's plumbing & gas Ltd 



## Project purpose
This is a website for a small plumbing & heating company in East Anglia. It has been created to enhance company's visibility on the market by creating online presence. It will allow customers and potential customers to learn about services provided and convince them to choose this company over competition. 
The website is mostly for individual clients. 

#### External user’s goal:
The site users are people planning upgrades and renovation of their homes in the future and/or individuals looking for services they require now. They all wish to learn more about company and services provided and possibly book an appointment or hear back from the company.

#### Site owner's goal:
The business owner wants to inform potential clients about the services and convince them to chose their services over ones provided by the competition.

## UX
Vast majority of users will be individuals who require plumbing and heating services in near future. People visiting this page will not be looking for ideas or asking themselves a question "if" they are going to go ahead with the planned investment. In plumbing & heating industry this is mostly checked on pages like Pintrest etc. where ideas can be looked up. 
Page users will be researching "which" company they are going to choose to carry out their planned investment.

Taking this into consideration this website is designed to assure them about professionalism and affordability (this confirmed in the reviews, gas safe membership and free inspections provided by the company).  
Welcome page contains a picture of company's plumber/gas engineer at work - which enhances trust in the company, especially to returning customers that will recognize the person and will instantly know it is the person that visited them. 
Color scheme was intentionally limited to enhance red and blue that are commonly regarded as associated with plumbing and/or hot and cold water.

#### User stories
- Website user wants to have easy & efficient way of navigating to each part of website (navigation bar)
- Website user wants to connect with the company - by being introduced to the people they are potentially going to meet when they decide to purchase services
- Website user wants to have easy access to list of services provided by the company
- Website user wants to be assured/ presented that the company staff is professional, appropriately trained & a member of professional bodies
- Website user wants to have access to customer reviews to find out past customers' opinions and information about services that they were provided by the company
- Website user wants to have more that 1 way of contacting the company - i.e. phone number, email address and/or contact form
- Website user wants to have easy way of reaching company's social media to read reviews of to start following the company etc.
- Website user wants to have easy access to contact section/ contact options from each section of the website
- Website user wants to be given advice/answer to frequently asked questions
- Website user that relies on audio description/screen readers wants to have descriptions inbuilt in the website
- Returning website user wants to have easy access to contact options via link directly from navigation bar or home web section

#### Wireframes 
Initial wireframes for this project can be seen in the [wireframes folder](https://github.com/malc-u/petes-plumbing/tree/master/wireframes).

## Functionality
This project utilises Bootstrap framework and Bootswatch Journal theme as a base to create one/scrolling page with Mobile first approach. This website is within the mandatory guidelines. It is written in HTML and CSS, however some Java Script was added to enhance the user experience. It is a single scrolling page with 5 separate page areas with navigation bar and footer. 
Although there is a contact form within this page it will not work as there are no back end functions incorporated in the code.

### Existing features
- **Navigation bar** - fixed and responsive
- **Logo** - clicked navigates to the home/top page
- **Social media links** in the navigation bar - clicked open another tab with business' social media pages where reviews are clearly visible
- **Slogan/head word** on each section of the page presenting business in more detail
- **Home page/Welcome picture** - picture of actual person that will meet customers on the job - adding credibility to the business 
- **Button [Book free inspection]** on the bottom of each section of this website - takes users that wish to get in touch with company directly to the contact section
- **Additional button** on the bottom of each section of this website allowing customers to scroll to the next section to find out more about the company
- **Services** grouped in 3 main fields - to allow website user to find what company is offering easier
- **Link to Gas Safe Register** page in About section - advises that company is legitimate and can legally work with gas appliances - Gas Safe Register number clickable
- **Reviews** - 3 recent ones-  grouped and displayed in a carousel form - About section
- **FAQ section** advises what to do in emergency situation with **end step - call to action** for a website user - phone number provided - **clickable button** format - gets users directly to phone call screen with company number already pre-entered
- **Contact** section - presents **phone number** and **email** address as well as **contact form** allowing website users to choose for the business to get in touch with them. **Email** address is presented in **clickable** form that gets users directly to their default email application in order to get in touch with the company
- **Contact form** has got **all fields** set as **required** - allows customer to provide all data required by the business to get in touch with them regarding booking free inspection etc.
- **Footer** - provides legal info of the company as well as links to company's social media
- **Clickable phone icon** - in the footer section - that gets users directly to phone call screen with company number already pre-entered
- **Clickable email icon** - in the footer section - that gets users directly to their default email application in order to get in touch with the company
- All links described for audio description/screen reading purposes

### Potential features to implement later
- portfolio of jobs completed
- back end functions to the contact form
- Captcha function to the contact form for better protection
- blog that would be updated regularly with tips and how-to making website more interesting and inciting customers to return or even share the page with friends and family

## Technologies & tools used
- HTML
- CSS
- jQuery - for navbar collapse function
- [Bootstrap](https://getbootstrap.com/) - for structuring the layout of the website and mobile first design
- [Font Awesome](https://fontawesome.com/)- for sourcing social media and gas,plumbing & heating icons/favicons
- Popper.js
- [Git](https://git-scm.com/) - installed on the local machine and integrated with Visual Studio Code
- [Visual Studio Code](https://code.visualstudio.com/) - IDE for writing the code
- [Chrome developer tools](https://developers.google.com/web/tools/chrome-devtools?hl=es-419) - for testing the page through the development process
- [Autoprefixer](https://autoprefixer.github.io/) - for vendor prefixes control in CSS
- [Tiny Jpg](https://tinyjpg.com/)- used to compress the pictures for better user experience


## Testing 

#### Automated testing
- [The W3C Markup validation service](https://validator.w3.org/) - automated testing of HTML in index file that pointed out few errors that were corrected 
- [The W3C CSS Validation Service - W3 Jigsaw](https://jigsaw.w3.org/css-validator/) - automated testing of CSS in style file - no errors found
- [Lighthouse in Chrome Developer Tools](https://developers.google.com/web/tools/lighthouse#devtools) - for automated webiste auditing
- [NVDA - NV Access](https://www.nvaccess.org/) - for screen reading testing

#### Manual testing
All features have been manually tested on desktops, tablets and laptops. I used Chrome Dev Tools during every stage of the project as well as a number of web browsers after the site deployment. These were:  Chrome, Opera, Microsoft Edge, Firefox, Ghostery mobile app.

Manually tested:
- all links in the navigation bar take user to relevant section
- logo click in the navigation bar takes user to the welcome/home page
- social media links in the navigation bar when clicked open new tab with relevant social media in them
- Check our services button (welcome/home page) takes users to services section
- Book free inspection button (welcome/home page) when clicked takes user to Contact section
- Check our reviews button (Services section) takes user to About section
- Book free inspection button (Services section) when clicked takes user to Contact section
- Link assigned to Gas Safe Register number 545699 (About section) when clicked opens new tab with company membership details on Gas Safe Register website
- Testimonial carousel previous and ext buttons (About section) when clicked present user  previous/next available review 
- Check FAQ button (About section) when clicked takes user to FAQ section
- Book free inspection button (About section) when clicked takes user to Contact section
- Call us on button (FAQ section) when clicked on takes user to mobile phone's call application with company number already pre-entered waiting for user to hit default "make call" button for this device or on a computer takes user to default phone call making application such as Skype etc.
- Book free inspection button (FAQ section) when clicked takes user to Contact section
- All contact form fields are set as required so when form is completed with missing information user is prompted to fill in required fields
- Links to social media (Footer section) when clicked open new tab with relevant company's social media pages
- Link under phone favicon/icon (Footer section) when clicked on a mobile phone takes user to mobile phone's call application with company number already entered waiting for user to hit default "make call" button for this device or on a computer takes user to default phone call making application such as Skype etc.
- Link under envelope favicon/icon (Footer section) when clicked takes user to their default email application
- Audio description/screen reading tested via NVDA app - descriptions added and/or amended
 
#### Testing user stories from UX:
1. Website user wants to have easy & efficient way of navigating to each part of website (navigation bar)

Navigation bar is fixed to the top and allows website users to navigate easily to each part of the page.

2. Website user wants to connect with the company - by being introduced to the people they are potentially going to meet when they decide to purchase services

Welcome/home page presents user a picture of company's plumber/gas engineer who is the face of a company. Customers are always meeting his at their doorstep.  Additionally About section presents company's professional membership status (where again users can see a picture of the same person as a company representative).

3. Website user wants to have easy access to list of services provided by the company

Website user can easily access services though navigation bar from any section of this page or directly from welcome/home page by clicking "Check our services" button.

4. Website user wants to be assured/ presented that the company staff is professional, appropriately trained & a member of professional bodies

Website user can read about membership of a professional body in the About section as well as easily access their website to confirm it by using the link provided in this section. Additionally website user has got access to some reviews on the page and provided links to the social media where more reviews can be read.

5. Website user wants to have access to customer reviews to find out past customers' opinions and information about services that they were provided by the company

Some recent reviews are presented in About section. There are also links to company's social media pages both within the navigation bar and in the footer section. These links will allow customer to read more reviews on company's social media.

6. Website user wants to have more that 1 way of contacting the company - i.e. phone number, email address and/or contact form

User is presented with many ways of contacting the company - from every section of the page they can access contact via navigation bar or "book fee inspection" button on the bottom of the page. Options they can choose are: phone, email, contact form to hear back from the company or social media.

7. Website user wants to have easy way of reaching company's social media to read reviews of to start following the company etc.

User can access company's social media from every section of the page via links/icons in the navigation bar as well via the links provided in the footer.

8. Website user wants to have easy access to contact section/ contact options from each section of the website

Contact section and contact options are easily accessible from every section of the page via navigation bar and "book free inspection" button on the bottom of each section. Additional contact option - social media - can also be accessed via navigation bar and links provided in the footer.

9. Website user wants to be given advice/answer to frequently asked questions

Advice to frequently asked questions and how to act in emergency situations is given in FAQ section. This is easily accessed via navigation bar from every section of this page.

10. Website user that relies on audio description/screen readers wants to have descriptions inbuilt in the website

This page has got incorporated instructions for screen reading.

11. Returning website user wants to have easy access to contact options via link directly from navigation bar or home web section

Contact section and contact options are easily accessible from every section of the page via navigation bar and "book free inspection" button on the bottom of each section. Additional contact option - social media - can also be accessed via navigation bar and links provided in the footer.

## Deployment
This project was developed using the Visual Studio Code IDE, committed to Git and pushed to GitHub.

Deploying this page from GitHub repository to GitHub Pages was achieved by following these steps:
1. Logging into GitHub
2. Picking malc-u/petes-plumbing repository for the list of repositories
3. Selecting Settings - from menu items on the top of the page (top, right hand corner)
4. Scrolling dow to the GitHub Pages section
5. Picking Master Branch from the "Source" drop-down menu in Github Pages (changing from the default "none" to master branch)
6. Awaiting for the page to be refreshed and website to be deployed - this happens automatically when step 5 is actioned
7. Scrolling back down to the GitHub Pages section to check/retrieve the link of newly deployed website

### How to run this project locally
This project was developed using the Visual Studio Code IDE, committed to Git and pushed to GitHub.

To clone this project from GitHub following steps need to be taken:

1. Follow this [link](https://github.com/malc-u/petes-plumbing) to the Project GitHub repository
2. Click "Clone or download"(green button on the right hand side, just above the file list) - this will open "Clone with HTTPS" section
3. Copy the clone URL for the repository from "Clone with HTTPS" section
4. Open your local IDE
5. Open Git Bash in your local IDE
6. Change the current working directory to the location where you want the cloned directory to be
7. Type git clone, and then paste the URL you copied in Step 3 - in this project the comant should be:

	git clone https://github.com/malc-u/petes-plumbing.git

8. Press Enter to create your local clone 

Futher reading or help with cloning can be found on this GitHub Help [page](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

## Credits
The content of this page was entirely written by myself and consulted with the company.

1. Navbar collapsing on click - thanks to jQuery posted by [Zim developer](https://stackoverflow.com/users/171456/zim) [here](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click)
2. Testimonial carousel used for reviews found [here](https://www.nicesnippets.com/snippet/bootstrap-4-testimonials-or-people-review-slider)
3. Photo on welcome/home page taken by Pete's plumbing & gas Ltd


### Acknowledgements

I would like to thank my mentor [Simen Daehlin](https://github.com/Eventyret) for his knowledge and listening to my 
ideas as well as suggesting what could possibly be added to improve my project. Also for his help with Visual Studio Code - how to best utilize its features and extensions.

Huge thanks to all people involved in creating helpful content that can be found online i.e. [Brad Traversy](https://github.com/bradtraversy), especially for his [Git crash course](https://www.youtube.com/watch?v=SWYqp7iY_Tc) and all participants and creators of [Stack overflow](https://stackoverflow.com/), [W3Schools](https://www.w3schools.com/), [Bootstrap documentation](https://getbootstrap.com/docs/4.1/getting-started/introduction/), [Nicesnippets](https://www.nicesnippets.com/) & [Positronx](https://www.positronx.io/).

Big thank you to [Code Institute](https://codeinstitute.net/) tutors for amazing course content that is very helpful in getting to understand the concept of HTML and CSS and to students current and past for sharing their work, ideas and opinions on Slack application - this gave me a lot of inspiration and help when in doubt about something. Especially Anthony O'Brien and [this](https://auxfuse.github.io/userCentricResourcePack/) extremely helpful resource pack & Ann Greaves and her amazing Bootstrap grid [tutorial](https://www.youtube.com/watch?v=zDpCejbl1sU&t=539s).

Lastly my family and friends that were very involved in testing this website on their mobile phones, laptops, tablets etc. and for giving me helpful feedback.



# Supreme Feast!

### By Aaron Green

## Description
<p>Supreme Feast is a website based on a newly built restaurant located in Sydenham, London which allows the user to explore what the restaurant has to offer and what they will expect if they choose to visit the resturant. It has a home page where the user can know all about the restaurant, a menu page for the user to look at the foods, drinks and deserts aand the resturant has a contact page for the user to put their details in to for reservation on how many will be attending. Opening hours and social links which can be found at the bottom.  <p>

----
## User Experience (UX)  
 * ### User stories
   
 1. As a new vistor to the website, I want to be able to access the website without any extensive time and to easily find and browse the navigation menu.  


1. As a new visitor I want to find information about the restaurant, such as its hours of operation, location and contact information.
    
1. As a returning vistor, I want to find the best way to get in contact the restaurant as there may be any questions I may have. 

1. As a potential client, I want a clear list of prices in menu so I can decide if it is within my budget     



      
 *  ### Business Goals
  1.   To increase revenue and profitability
  1.   To franchise the business in other locations
  1.   To increase brand awareness and loyalty
  1. Increasing the frequency of customer visits 
  1. To maintain success for a long term vision 
  1. To aim to be the number one restaurant in the country, that means to maintain brand goals  

* ### Customer goals
  1. To meet the requirements for customers and to meet dietary requirements for customers who may be vegeterian. 
  1. To provide customer reasonable prices that suit their budget
  1. To provide quick responsive orders for customers
  1. To ensure the location of the restaurant is accessiable for parking so it'll be easier for those who will be travelling my car 
  1. To make the website as clear as possible for customers to access what they want to look for

  ----
  ## Design
   * Colour Scheme
      * The two main colours used for the website application are Black and White
    * Typography 
      * The fonts used for are Roboto font which is used for the entire website followed with San Serif as a backup. 
    * Imagery 
       * The user will get to feel what it would be like experincing the resturant and what the atomsphere would be like by visualing the images of the website    
    ----
  ## Wireframes
    * Home Page Wireframe [Restaurant Project Milestone 1 (Home Page).pdf](https://github.com/A-Gr33n/Milestone-Project-1/files/10734473/Restaurant.Project.Milestone.1.Home.Page.pdf)

    
    * Menu Page Wireframe [Restaurant Project Milestone 1 (Menu Page).pdf](https://github.com/A-Gr33n/Milestone-Project-1/files/10734478/Restaurant.Project.Milestone.1.Menu.Page.pdf)


    * Contact Us Page Wireframe [Restaurant Project Milestone 1 (Contact Page).pdf](https://github.com/A-Gr33n/Milestone-Project-1/files/10734433/Restaurant.Project.Milestone.1.Contact.Page.pdf)


    * Moblie Wifeframe [Restaurant Project Milestone 1 (Mobile Wireframe).pdf](https://github.com/A-Gr33n/Milestone-Project-1/files/10734481/Restaurant.Project.Milestone.1.Mobile.Wireframe.pdf)


    * Tablet Wireframe[Restaurant Project Milestone 1 (Tablet Wireframe).pdf](https://github.com/A-Gr33n/Milestone-Project-1/files/10734485/Restaurant.Project.Milestone.1.Tablet.Wireframe.pdf)

     ----
    ## Features 
     * Responsive on all device sizes. 
     
     * Interactive elements
     ----
     ## Technologies Used 
     
     ### Languages Used

     * HTML5

     * CSS3
     ------
     ## Frameworks
     
     1. Boostrap V5.3:
        * Bootstrap was used to keep the website responsive 

     1. Google Fonts:
        * Google fonts was used for to provide the text that was needed to construct the webisite it is imported in the css style section 

     1. Font Awesome:
        * Font Awesome was used to import icons needed for the website  
     
    1.  Git :
        * Git was used for version control by utilzing the Gitpod terminal to commit to Git and Push to GitHub 

     1. GitHub:
         * GitHub is used to store the projects code after being pushed from Git
     
     1. Material Design:
        * Material Design is used to access the level of color combination to make the website as nice and presentable for the user
    1. Balsamiq:
       * Balsamiq was used to create the wireframes as a blueprint to design this website    
     
    
    
    ----
   ## Deployment 
     This project was developed using Gitpod a cloud-based editor linked to the Microsoft VS Code. Files and Folders are committed to git and pushed to GitHub. 

     To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken.

     1. Log into GitHub.
     2. From the list of repositories on the left side of the screen, select A-Gr33n/Milestone-Project-1
     3. From the menu items near the top of the page, select Settings
     4. On the code and automation section on the left side of the screen select pages
     5. Under "Build and deployment", under "Source", select Deploy from a branch
     6. Under "Build and deployment" , under "Branch", click the dropdown called "None" and select "Main"   
     7. Next to the main dropdown on the right click on dropdown "(root)" and select "(docs)"

    ### How to Clone this project 
   To clone this project from GitHub:
    1. Select A-Gr33n/Milestone-Project-1 from the list of repositories
    1. From the menu items near the top of the page select <>code from  dropdown menu 
    1. In the clone with HTTP's secion, copy the clone URL for the repository.
    1. Open Git Bash
    1. Change the current working directory to the location where you want the cloned directory.
    1. Type git clone, and then paste the URL you copied earlier next to it
       
       $ git clone https://github.com//A-Gr33n-milestone-1 
           
    1. Press "Enter" to create your local clone
     ---   
     ## Testing
     ### W3C Markup Validor and W3C CSS Validator
   The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no sytax errors. Screenshots are presented below for evidence to show solved errors. 
    
     

     ### Lighthouse
     Lighthouse was used in chrome dev tools to check the Performance, Best Practices and Accessibility. Screenshots are documented in the images folder showing the websites' progress. 
     <p> Testing each attribute there were errors that needed to be solved.
     
     #### Perfomance
   * Images where not properly sized,
    <p>solution: Images are reduced by size in Style.CSS to met the perfomance standard and to be compatiable on mobile screens. 
    
   * render- blocking needed to be eliminated, 
     <p> solution: Script element was in the body element which needed to be 
     in head element.
   
   
    
   #### Asccessibilty   
     
  * links did not have a discernible name. (Did not link text for social links)
      <p> solution: All social links are now linked to there page. 
  * the heading elements were not in a sequentially-descending order.
      <p> solution: Changed heading size in footer to follow logical order.
  
  #### Best Practices  
  *   Diplays images with incorrect aspect ratio  
      <p> solution: Changed image size in CSS which and changed the image's width and height attributes in the HTML. 
   


      
      

     ### Testing client stories from UX section of README.md 
     * #### First Time Vistor Goals 
      1. As a First Time Vistor to the website, I want to be able to access the website without any extensive time and to easily find and browse the navigation menu on any device.  
          
          i. The website loading time process was tested on lighthouse and other testing site and its perfomance shown to be above 90%. 

          ii. No matter what page the new visitor lands on, they can easily find and use the navigation bar on any device as the site is responsive.   
         
          
      
        
      2. As a First Time Visitor I want to find information about the restaurant, such as its hours of operation, location and contact information.
         
          i. At the bottom of each website page the user can find the opening times. 
         
         ii. The location is placed in the contact page

         iii. The user can click on contact link on the navbar and it will direct them on the contact page. 
        
        
      3. As a Returning Vistor, I want to find the best way to get in contact the restaurant as there may be any questions I may have. 

         i. On the navigation bar there is a contact page, the user can find a textarea located at the bottom of the page where the user can type any queries once.

         ii. There is a submit button underneath the textarea once the user has finished writing the message.  
          
      4. As a potential client, I want a clear list of prices in menu so I can decide if it is within my budget. 

        i. On the menu page products are clearly listed for the user to see and has images next to price description to it more cl  
     ---
    ## Credits
    
   ### Code
      /* credit: code for making images all equal height for menu page taken from https://stackoverflow.com/questions/52871316/how-to-make-bootstraps-card-img-top-equal-height-at-responsive-widths and edited slightly to fit project needs */
    
     .card-img-top {
      <p> width: 100%; </p>
      <p> height: 15vw; </p>
      object-fit: cover;
      }



   Bootstrap v5.3.0:
    * Bootstrap v5.3.0-alpha1 was mostly used to create the html structure for this website. It was needed to make the site responsive using the Bootstrap Grid System. The Bootstrap card codes was used to put images and text to group them row by row. 

    Google Fonts :
    * Google Fonts provided the text that was needed to build the website.



    ### Media
   Images:
    1. Home Page :   
     
       All images from the home page are provided by https://pxhere.com/ these images give a feel of what the resturant would be like for the user if they were to visit. 

    1. Menu Page : 
    
       Images from menu page were referenced from  https://pxhere.com/ and https://www.pexels.com/. Each image shows the user the menu order and what they can order when they are visiting.

    1. Contact Page:

       On the contact page there is only one image which is sourced from https://www.pexels.com/ which shows a waiter holding two dinner plates. This gives the user the type of customer service the business provides when they book a table.   


# Workout World
This website is created for the new gym Workout World in the center of Stockholm in Sweden. The project is fictional and created for educational purpose.

## UX 
In this section is the explanation of how the website is planed to make it useful, usable and valuble for both the user and site owner using the five planes of user experience. 
### 1 Strategy
The objective of this website is to inform about the gym and its offer to new and existing members. 
The target audience for the gym is people living in Stockholm whom wants to workout at a modern and friendly gym. 
The user on the website is always going to be an anonymous user since it is not possible to log in to the website yet. 
Users goal: wants to know more about the gym and what it offers.
Site owners goal: to create an online presence of the gym and to inform about what the gym offers. 

#### User stories 
* As a user, I want to know what type of memberships the gym offers. 
* As a user, I want to know what a membership cost.
* As a user, I want to find out how to contact the gym. 
* As a user, I what to see what classes the gym offers. 
* As a user, I want to find out when the classes are available. 
* As a user, I what to know what opening hour the gym has. 
* As a user, I what to know where the gym is located. 

### 2 Scope 
The focus of the is for new and excisting members to easily find information abot the gym, its offer and how to get in contect with the personel at the gym. 
Since it is a b2c website it is important to have easy digestable content on the site and this has been taken into consideration when building the site, 
to have big pictues and small sections with text to make it easier for the user. 
### 3 Structure 
For the structure of the page is designed with a linear narrative to make the site easy to use from the first time visiting it.
The navigation bar is placed at the top of the browser window and is sticky so that it is easy to go where you want on the website.
On the landingpage of the site more genreal information and an offer is representet and then you can move on to more detaild information on the other sides of the webpage. 
### 4 Skeleton
Wireframes where developed for the website to ensure that the content is presentent is in line with the strategy and gole of the website and to make sure that the arragement amongst the emelments work. 
Visual methaphors in the form of icons is used in some places to make the content easier to interpret for the user. 
For the structure the more general information and perks of the gym is represented because this content is proritised to get users interested. When you continue on the navbar 
to the right more detail information is presented for those who are interested and furtherst to the right in the navbar the contact page is placed. 

Balsamiq was used to create wireframe for the website, the wierframes are linked below. 
* [Desktop](/assets/wireframes/desktop-wireframes.pdf) 
* [Tablet](/assets/wireframes/tablet-wireframes.pdf) 
* [Mobile](/assets/wireframes/phone-wireframes.pdf) 

### 5 Surface

#### Color

The color scheme used for this project is to create a minimalistic and modern design with high contrast between the lighter turquoise and the darker colors. 
![Color scheme](/assets/images/color-scheme.jpeg)

#### Typography 
The fonts used in this project is both found on google fonts, Montserrat is used for the headings paired with the font Lato for bodytext which was a popular pairing according to google fonts.
The fallback font for both headings and bodytext is Sans-Seriff. 

## Features 

### Existing Features
- Navbar
    - The navbar will be sticky so that the user always can easily can get to different parts of the webpage 
    and become a dropdown menu on tablet and phone. 
- Footer 
    - The footer will contain links to social media so the user can easily fin the gym on social media 
    and a link to the contact page so that it is always easy for the user to find out how they can contact the gym.
- Home
    - Navbar (described under navbar)
    - The homepage will have a heroimage underneath the navbar with an offer on it to get the users attention. 
    - Underneath the heroimage on the homepage some of the benefits with the gym will be presented 
    to emeidietly let the user knows some of the advantages of the gym. 
    - Footer (described under footer).
- Membership
    - Navbar (described under navbar). 
    - On the membership page the three different memberships will be presented so that the user know what memberships are avalibe and their prices. 
    - Underneath the memberships on the membership page there will be a picture where the student discound is presented 
    so that the users that are students know they can get a discount on the memberships.
    - Footer (described under footer).
- Class schedule
    - Navbar (described under navbar).
    - On the Class schedule page underneath the navbar there will be a heroimage with the main heading on it. 
    - Underneath the heroimage on the class schedule page the schedule for the classes will be so the user can se when the classes take place. 
    - Underneath the schedule for the classes the instructors will be shortly presented so that the user can get to know the different instructurs a little. 
    - Footer (described under footer).
    
- Contact
    - Navbar (described under navbar).
    - On the contactpage under the navbar the different ways to contact the gym will be presented so that the user know the different ways they can contact the gym. 
    - Underneath the diffrent ways to contact the gym there will be a contact form if the user wants to fill that out instead of using some of the other ways to contact the gym. 
      This form will reload the page.  
    - Footer (described under footer).

### Features Left to Implement
* A way to sign up to become a member on the website.
* Link pictures from the gym's instagram on the website. 
* A google maps to see where the gym is located. 

## Technologies Used
* HTML was used to build the webpage.
* CSS was used to style the webpage.
* Bootstrap was used to style some elements and to make the website responsive. 
* Fontawesome was used for the icons. 
* Google Fonts was used for the two fonts that I used in the project, Montserrat and Latol. 
* Gitpod was used to code the website. 
* Github was used to hoast the project. 
* Balsamiq was used to create the wireframes. 
* Tinyjpg was used to compress the images. 
* Photoshop was used to edit some of the images. 

## Testing

1. Navbar 
    * Clicking the logo reloads the home page. 
    * Clicking the home link reloads the home page.
    * Clicking the memberships link brings user to the membership page. 
    * Clicking the class schedule link brings user to the class schedule page. 
    * Clicking the contact link brings user to the contact page.
    * Scrolling dow the page the navbar stays at the top of the browser window. 

2. Footer 
    * Clicking the logo reloads the home page. 
    * Clicking the facebook icon brings user to facebook.com in a new browser window. 
    * Clicking the instagram icon brings user to instagram.com in a new browser window. 
    * Clicking the linkedin icon brings user to linkedin.com in a new browser window.
    * Clicking he contact link brings user to the contact page.

3. Contact form 
    * Go to the contact page 
    * Trying to submit the form emty and an error message appears to fill out required fields. 
    * Trying to submit the form without a valid email adress and a error message appears. 
    * Trying to submit the form with all the required information and the page reloads. 

### Bugs 
* It's a gap on the screen to the right on mobile verision for everything but the navbarthat disepears after pressing something on Moto G4, Glaxy S5 pixel 2, pixel 2 XL Iphon 5/SE, iphone 6/7/8, iPhone X, Galaxy Fold, Surface duo in Chrome DevTools.
  After googling this problem i started to check that i didn't have any element that was exceeding more than 100% of the screen width. I could'n fint any so I inserted overflow-x: hidden for html and body
  in my css file that i found in [this](https://stackoverflow.com/questions/46012482/unwanted-white-space-on-right-side-in-mobile-view/46012924) thread on Stack Overflow that fixed the problem. 
* Images don't work when deploying the website on github. Fixed this by changing the image filepaths from absolute to relative instead. 
## Deployment

## Credits 

### Code 
Most of the code in this project was written by me, however some of the code I got from other that are presented below. 
* The navbar is taken from bootstrap and costomized to fit my project. 
* Bootstrap is used to make the content responsive and to style some elements. 
* In my css file I used a piece of code found in [this](https://stackoverflow.com/questions/46012482/unwanted-white-space-on-right-side-in-mobile-view/46012924) thred on Stack Overflow to fix a layout problem on smaller screensizes, this is described in more detail in the bugs section. 
* I used a pice of code from [this](https://www.youtube.com/watch?v=O7WbVj5apxU&t=583s) youtube video made by Dev Ed to set the background on some items on the website, there are comment in the code in the regarding places. 

### Media 
* Hero image on home page by [Li Sun](https://www.pexels.com/@823sl) from [pexels](https://www.pexels.com/) 
* Student discount picture on memberships page by [Ivan Samkov](https://www.pexels.com/@ivan-samkov) from [pexels](https://www.pexels.com/) 
* Hero image on class schedule page by [Victor Freitas](https://www.pexels.com/@victorfreitas) from [pexels](https://www.pexels.com/) 
* Picture of the instructor Anna on class schedule page by [Leah Kelley](https://www.pexels.com/@leah-kelley-50725) from [pexels](https://www.pexels.com/)
* Picture of the instructor Kalle on class schedule page by [Elle Hughes](https://www.pexels.com/@elletakesphotos) from [pexels](https://www.pexels.com/)
* Picture of the instructor Philip on class schedule page by [Italo Melo](https://www.pexels.com/@italo-melo-881954) from [pexels](https://www.pexels.com/)
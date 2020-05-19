
<img src="assets/images/LongLogo2.png">
<br>

*[Add the responsive site preview here]* 

---
# Irish Legends

At the time when your  little one forgets to bring their favourite book on a trip and the story time routine is under threat; this site will provide you with collection of the most popular stories to read on the go.
With an easy access the on phone or tablet an adventure to Ireland of the past has never been easier. 

Get comfy and let yourself to be enchanted by Irish Legends.

Live demo of this site [here](https://janabuckova.github.io/Irish-Legends/)

---

## UX (User Experience)

### Website Goals
The site’s intended users are young readers and parents of young readers who enjoy reading stories from Irish Mythology. 

Starting as single page site with a simple navigation and reduced content in order for young reader not to get overloaded with too much information but with a potential for future expansion based on users’ story suggestions.

### User Stories (parents)

* As a user I want the site to be easy to navigate even by my 7 year old (Chris, Dublin)
* As a user I want the text to be written in nice writing/font (Joanna, Skerries)
* As a user I want to be able to send feedback or quries (Martin, Naas)
* As a user I would like an option to receive news email/notification or when new stories are added (Martin, Nass)
* As a user I want to be able to increase the font size so my daughter can read alongside me (Chris, Dublin)
* As a user I would like to see your social media posts (Joanna, Skerries)

### Design choices

* I have gone for a minimalistic design for more than a half of the site with only one 
dominant image on the site in the about section to capture the users attention. 
* The colours were specifically chosen to to represent Ireland's nature hence the use of different shades of green.
* Navigation of the site was created with young user in mind but also with the potentional of the expansion of the site. 
The nav bar is fixed on the top so the user doesn't need to scroll excesively through the page.
* The font used was chosen to compliment the design and the theme of the overal site.

### Wireframes

Wireframes for this project were created at the beginning of the project using [Balsamiq](https://balsamiq.com) and provided a usefull visual aid for the 
intended sturcture on diferent devices. 
After initial discussion with my mentor I diviated from my design slightly. 

In the initial design:

* In About section I was unsure how an image would look like in the backgroung of the section and at the time I was also unable to find a suitable one 
to match the colour theme of the site. At the end I have opted for visualy pleasing background image. 

* In Stories section I have chosen to display image with carousel slider next to it where the user would navigate through the story by clicking arrow 
buttons. Instead I have chosen to use card-deck with modal for each story as it provides better user experience (less clicks for the user).

* Considering a user story I have opted for newsletter sign up form which I placed in the footer which is not on the initial design.

* I have decided not to use pink colour other than in Logo. 

Wireframes and colour composition can be found at the below location.

* [Desktop](wireframes/desktop.pdf "Desktop")
* [Tablet](wireframes/tablet.pdf "Tablet")
* [Mobile](wireframes/mobile.pdf "Mobile")
* [Colour-composition](assets/wireframes/colour-composition.pdf "Colours")

## Features

### Existing Features
* **Navigation Bar** - responsive navigation bar that enables the user to navigate through the site
* **About Section** - provides user with brief comntary on Irish Mythology
* **Stories Section** - responsive section containig stories for users to read
* **Modals** - each story is contained in scrollable modal to ensure positive UX
* **Contact Form** - allows user to to contribute to the content of the site or comment 
* **Subscribe Form** - allows user to subscribe to newswletter to receive latest updates
* **Social Media Links** - allow users to stay connected on social media 

### Features Left to Implement
* **Additional Page** - When the site receives more interest and user would like to see more stories
a separate page would be added
* **Font Increase** - Based on the UX story a font size increase would be added
* **Font Change** - I would like to look into a posibility of changing font on modals depending on the reader
(e.g. dyslexic friendly)
* **Audio Version of Stories** - Depending on user's interest I would like to add and audio version of stories

## Technologies Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
  - This project used HTML5 for building the structure of the site
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) 
  - This project used CSS3 for styling of the site
* [Bootstrap](https://getbootstrap.com/) 
  - This project used Bootstrap - CSS framework responsiveness of the site, including Javascript plugins
* [Google Fonts](https://fonts.google.com/) 
  - This project used Google Fonts library for customised font
* [Font Awesome](https://fontawesome.com/) 
  - This project used Font Awsome icon toolkit for Social Media Logos
* [GitPod](https://code.visualstudio.com/) 
  - This project used GitPod - IDE for local developement
* [GIT](https://git-scm.com/) 
  - This project used GitPod for version control
* [GitHub](https://github.com/) 
  - This project used GitHup for hosting the repository and the live website preview



## Testing

Thoughout the project I have rellied on Chrome and Opera Developer tools which had proven to be invaluable for testing on responsiveness on different devices.

I have validated the HTML adn CSS code in [W3C Markup Validation](https://validator.w3.org/) and [W3C CSS validation](https://jigsaw.w3.org/css-validator/), the results are enclosed [here](testing/w3c-validatio.pdf "Validation")
To validate the code I clicked on the provided link and in the tab validate by URL I entered url of my site. (e.g https://janabuckova.github.io/Irish-Legends)


## Testing user Stories - implemented features

The testing was completed in Chrome Opera, Firefox, Edge and IE on laptop.

1. Navigation of the site
  * From Navigation bar I clicked each navigation link
  * Links worked and took user to the appropriate section of the site
  * Navigation bar stayed fixed to the top to ensure easy navigaton without too much scrolling

2. Font choice rendered
  * The chosen Font Ruloko rendered in all browsers 
  * The media query for laptop and desktop for font increase worked as expected

3. Contact Form
 * From navigation bar clicked 'Contact'
 * Tried to submit the empty form and verified that an error message about the required fields appeared
 * Tried to submit the form with an invalid email address and verified that a relevant error message appears
 * After all fields were populated tried to 'Submit' the form. 403 error message appeared due to the fact the 'Action' and 'Method'
attribute were not include in the design of the form. (not a requirement of this project)

 * **Observation** - Firefox browser doesn't provide user with the message how correct email address should look like (contain @), only 'Please enter and email address'
From experience with my father I can confirm this can be little confusing for older users who are not used to forms and only use email on tablet or phone by clicking an email icon. 
This should be taken into consderatin when designing websites in general. A proper placaceholder would make the user experience more positive. Note to myself **Think of the intended user** (younger/older audience)

4. Subscribe Form
  * From footer section tried to submit the form with an invalid email address and verified that a relevant error message appears
  * After the field was populated tried to 'Submit' the form. 404 error message appeared due to the fact the 'Action' and 'Method'

5. Social Media
 * From footer section clickd on each social media icon and was redirected to the appropriate social media site
 * As designed each social media site opened in a new tab 
 * Same **Observation** as above applies

 ## Testing other features
 
 Tested on desktop, tablet, mobile using Developer tools and in real mobile enviroment using **OnePlus 3**, **Samsung Galaxy A3** and tablet **Samsung Galaxy Tab A** 

1. Navigation bar logo - resizing
 * When site vieview on mobile and tablet verified that th logo is responsive and resizing on smaller screen

2. Toggler/Hamburger menu
 * On moblil device the navigation bar was designed to colapse into a Toggler
 * Tested and verified that the toggler appeared as intended on smaller and larger mobile scren 

3. Modals in Stories section
  * Clicked each button and verified that modal window appered as designed. Large modal on desktop and tablet held horizontally. 
  Small modal on tablet held vertically and mobile

4. Smooth Scroll
 * Verified that works as intended with exception of IE (not working at all). Also when tested in Edge and the Firefox the scroll is so quick that almost appears as 'jump'










In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

To deploy this page to GitHub Pages from [its GitHub repository](https://anabear.github.io/ZestyTails/), the following steps were taken:

1. On GitHub, navigate to the site's repository.
2. Under the repository name, click on **Settings**.
3. Scroll down to the **GitHub Pages** section.
4. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**.
5. On selecting **Master Branch** the page is automatically refreshed, the website is now deployed.
6. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
7. A green box should appear with the following message 
Your site is published at `https://janabuckova.github.io/Irish-Legends/`

For more information on how to deploy a website on GitHub, [please visit this website](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

### How to run this project locally

To clone this project from GitHub:

1. On GitHub, navigate to the main page of the repository.
2. Under the repository name, click the green button **Clone or download**.
3. In the **Clone with HTTPs** section, copy the clone URL for the repository.
4. Open Terminal.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.
   `git clone https://janabuckova.github.io/Irish-Legends/.git`
7. Press **Enter**. Your local clone will be created.

For further reading and troubleshooting on cloning a repository [from GitHub](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).


## Credits

### Content
The content in Stories section was copied from books Irish Legends for children [Gill Books](https://www.gillbooks.ie/) and Best-Loved Irish Legends [The O'Biern Press](https://www.obrien.ie/) 

### Media
The photos used in this site were obtained from:
 * [Shutterstock](https://www.shutterstock.com/home)
 * [Pixabay](https://pixabay.com/images) - Clipart for Stories images
 * [Sketchpad 5.1](https://sketch.io) - Stories images created by me using inbuilt Clipart Library
 * [Logomakr](https://logomakr.com/) - Site logo created by me using inbuilt Library

### Acknowledgements

- I received inspiration for this project from X
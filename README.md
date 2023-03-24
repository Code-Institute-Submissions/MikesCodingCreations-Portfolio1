# Bitcoin Info

The 'Bitcoin Info' website is a landing page for anyone who is curious about cryptocurrency and specifically Bitcoin. It is aimed to briefly explain what Bitcoin is, how it works with a few brief lines of text and an external video, the timeline and historical events and finally allow request (via the form) for more information.

Users of this website will be able to find out basic information around Bitcoin as well as conduct further research by reviewing the Whitepaper on the Bitcoin.org website or watching the short external video link. 

![Responsice Mockup](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_full_responsive_mockup.png)


### Features 

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Home page, About section, Timeline section and the Contact section and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_full_navbar.png)


- __Hero section__

  - The landing includes a photograph of the Bitcoin icon/logo with text to the right (on large devices, and below on smaller devices) which explains briefly what Bitcoin is. 
  - This section introduces the user to Bitcoin Info with an eye catching image and hero text to grab their attention

![Hero Section](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_hero.png)

- __About section__

  - The about section will allow the user to quickly and easily understand the main concent of Bitcoin.
  - This user will also be able to use video controls (pause, play, full screen, mute etc.) to preview a short and simply video explansation from an extrernal site of what Bitcoin is. 
  - Further to this, users will be able to navigate to the external link so they may conduct further research on what Bitcoin is via the Bitcoin.org website.

![About Section](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_about_section.png)


- __Timeline section__

  - This section will allow the user to see historical events that have occured since the creation of Bitcoin. This information is displayed in a table format with a heading and a sub-heading.
  - This section will be updated as further/future events occur. 

![Meetup Times](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_timeline.png)

- __Contact section__

  - The contact section will provide the user an opportunity to submit any queries or questions they may have either about the website itself or about Bitcoin.
  - Here the user will be prompted to enter their full name, their email address where they will be contacted back on and finally their query in a text box. 
  - This section is valuable to the user as it shows the creator is willing to contact them back to answer any query they may have. It also shows interactivty as the form will be submitted to CI's form dump site where in theory they should get a 'form/request submitted' popup.

![Gallery](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_contact.png)

- __Footer__ 

  - The footer section includes links to the relevant social media sites for Bitcoin Info. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_footer.png)

### Features Left to Implement

- A gallery of more Bitcoin images
- A 'partnership/user' section detailing entetites that have integrated Bitcoin
- A live API that displays the live price for Bitcoin

## Testing 

- I tested that this site works well on multiple browsers such as Google Chrome, Firefox, Safari and IE.
- I confirm that this website is responsive, lookgs good and functions well on all standard screen sizes using the Google Chrome devtools and the 'am i responsive' website.
- I declare that all sections including the navigation header, nav links, home, about, timeline, contact and footer sections are relatateable and simple to comprehend.
- I can verify that the form works well and relevant fields apply (e.g., email field only accepts email responses).

## Bugs
Solved bugs
- When deploying my project to GitHub pages, i noticed that the CSS file was not correctly linked via the file path as the styles did not apply. Previously the filepath that i had was:
    <link rel="stylesheet" href="assets/style.css">
However, after a few tests, i changed the link to the correct filepath:
    <link rel="stylesheet" href="./assets/style.css">

- When submitting the form, i discorved that the ID of certain fields were not linked and therfore did not match. I quickly changed these to ensure the form was fully connected

- A bug that took a while to solve was the website responsiveness. I had to play around with 'Flexbox Froggy' to fully understand CSS Flexbox layouts to ensure the site was fully responsive on all devices.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official 
  [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmikescodingcreations.github.io%2FPortfolio1%2F)
  [W3C validator image](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_w3c_validator.png)
- CSS
  - No errors were found when passing through the official 
  [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmikescodingcreations.github.io%2FPortfolio1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
  [Jigsaw validator image](https://github.com/MikesCodingCreations/Portfolio1/blob/main/media/bitcoin_info_jigsaw_validator.png)

### Unfixed Bugs

N/A

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://mikescodingcreations.github.io/Portfolio1/ 


## Credits 

Credits go to the below links for their information on how to build this site and for providing information that has been used such as image, text and video.

# Content 

- Information on the Hero section was taken from the Bitcoin website [Bitcoin] (https://bitcoin.org/en/)
- The text for the about section was taken from Wikipedia [Wikipedia] (https://en.wikipedia.org/wiki/Bitcoin)
- Info for the timeline section (bitcoin price history) was taken from two sites 
    [Statista] (https://www.statista.com/statistics/326707/bitcoin-price-index/) 
    and [Investopedia] (https://www.investopedia.com/articles/forex/121815/bitcoins-price-history.asp)
- Instructions on how to create this site was taken from the CI project 1 course [Link to CI](https://codeinstitute.net/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Information on the Bitcoin color code was taken from [Design_Pieces] ( https://www.designpieces.com/palette/bitcoin-colour-palette-hex-and-rgb/#:~:text=The%20Bitcoin%20logo%20comprises%20three,the%20logotype%20text)%20and%20White. )


### Media

- The hero image of Bitcoin was taken from [pngitem] (https://www.pngitem.com/middle/JTbmmo_bitcoin-png-transparent-background-bitcoin-png-png-download/)
- The video in the about section was taken from [The_Guardian] (https://www.theguardian.com/news/video/2014/apr/30/bitcoin-made-simple-video-animation)

---



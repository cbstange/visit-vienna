# ![Austrian flag logo](assets/images/austria-readme-logo.jpg)

# Visit Vienna

### "Visit Vienna" is a site to offer users a concise visitor's guide which includes some popular attractions, restaurants and outdoor activities. "Visit Vienna" is intended for travelers with limited times who are looking for a quick overview of activities for their visit.

## Finished site deployment [link](https://cbstange.github.io/visit-vienna/index.html).

![Responsive Mockup](.//assets/images/readme-responsive.png)

## Planning
Before starting the project, I went through my old photos of living in Vienna for inspiration and also researched a number of Vienna travel websites. I used Balsamiq to create a
[wireframe](.//assets/planning/visit_vienna.pdf) which can be found in the planning folder in "assets".

## Existing Features:
- ### Navigation Bar
  - Featured on all four pages, the navigation bar is fully responsive and includes a image that brings you back to the home screen and links for all other pages: Attractions, Restaurants and Outdoors.
  - The navigation bar's structure is meant to be familiar to users: when a user visits the site, it is clear how to navigate each page.
  - To add to usability, a hover effect was added so there is feedback to the user has they choose which page to visit.

![Navigation bar](.//assets/images/readme-navbar.png)
- ### Landing page image
  - The home page features a photo of the Vienna skyline at dusk with a transparent text overlay containing Vienna, Austria and a small fact about the city.

![Index hero image](.//assets/images/readme-index-hero.png)
- ### Landing page video
  - The home page includes a short, embedded YouTube video showing some highlights of Vienna meant to get the user excited about visiting the city.

![Index youtube video](.//assets/images/readme-index-content.png)
- ### Subsequent Pages
  - Each page features a large, beautiful hero image and below there is a content section featuring three columns each containing an attraction.
  - Each content item includes a clickable title, photo and short description. 

- ### Attractions page
![Attractions page hero image](.//assets/images/readme-attractions-hero.png)
![Attractions page content image](.//assets/images/readme-attractions-content.png)

- ### Restaurants page
![Restaurant page hero image](.//assets/images/readme-restaurant-hero.png)
![Restaurant page content image](.//assets/images/readme-restaurant-content.png)
 
 - ### Outdoors page
![Outdoors page hero image](.//assets/images/readme-outdoor-hero.png)
![Outdoors page content image](.//assets/images/readme-outdoor-content.png)

 - ### Contact Us page
   - The "Contact Us" page includes a simple form where the user can request more information on the content shown on the site. The form uses validation and includes a "reset" button to clear the form.

![Contact us image](./assets/images/readme-contact-us.png)

- ### Thank You page
  - The "Thank You" page simply confirms the form was submitted successfully. There is a link to return to the home page as well.

![Thank you image](./assets/images/readme-submit.png)

- ### Footer
  - The footer is visually simple and contains three icons with links to social media accounts for the City of Vienna. All links open in a new tab.

![Footer image](.//assets/images/readme-socials.png)

## Testing & Bugs
Throughout the entire process, I utilized the Chrome Developer Tools to verify the site's:
  - Responsiveness on different screen sizes and mobile devices
    - When there was unexpected behavior when shriking the screen size, I knew at which screen size I needed to add a media query.
  - Lighthouse was used to rate the site's accessibility and efficiency.
  - Bugs
    - Sizing and font for the navigation bar had differenced between the home page and subsequent pages. The bug was resolved by adding the Google Font link to all subsequent pages.
    - Form validation was not functioning - form could be submitted in any state. The bug was due to the submit input being outside the form element.

## Validator Testing
#### HTML
- No errors were returned when passing through the official W3C validator.
#### CSS
- No errors were found when passing through the official (Jigsaw) validator.

#### Accesibility
-WAVE and Lighthouse were used in Chrome to test accessibility of the site.

## Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- The live link can be found here - https://cbstange.github.io/visit-vienna/

## Credits
### Media
- Images were sourced from [Unsplash](https://unsplash.com/) which is a site that provides free images so there are no copywrite violations.
- The video on the index.html splash screen was sourced from a [Youtube](https://www.youtube.com/watch?v=nK_SLrX4Pfc) channel called "Cities of the World".
- Development
  - GIT was used for version control.
  - CodeAnywhere was the IDE used for development.

### Content
- The code for the footer socials was taken from the Code Institue ["Love Running"](https://code-institute-org.github.io/love-running-2.0/index.html) sample project.
- Fonts were sourced from [Google Fonts.](https://fonts.google.com/)
- Text and background colors were sourced from [Coolors.](https://coolors.co/)
- Descriptions for each of the recommendations on the site were inspired by [The City of Vienna's Homepage.](https://www.wien.info/de?fbclid=IwAR2pgHbrho6MsR38oeZCxlwGr5lFF47vXAEo9Y_W17FoFtc7zmHG8U5pJt4)
- Navigation bar was inspired by this [YouTube](https://www.youtube.com/watch?v=PwWHL3RyQgk&t=428s) tutorial by "Skillthrive".
- CSS reset was used from [Meyer Web](http://meyerweb.com/eric/tools/css/reset/).
- Wireframes were created using [Balsamiq](https://balsamiq.com/).
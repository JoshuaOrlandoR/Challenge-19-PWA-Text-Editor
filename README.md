
  # Challenge 19 - Progressive Web Apps : Text-Editor 

  [![mit license](https://img.shields.io/badge/License-mit-brightgreen.svg] ([mit] (https://choosealicense.com/licenses/mit))
  
  ## Table of Contents 
  * [Description](#description) 
  * [Requirements](#requirements) 
  * [Installation](#installation) 
  * [Useage](#useage) 
  * [License](#license) 
  * [Contributions](#contributions)
  * [Tests](#tests) 
  * [Questions](#questions) 
 
  ## Description
  This is JEST, Just Another Text Editor! This application lets users create code or write whatever they want, with the ability to store whatever is written, regardless of an internet connection. This application utilizes a variety of packages and utilities, like service workers and caching, to enable this offline (and online) operation. Users can utilize the application in both a browser, or even save it to their own device.  

  ## Requirements
  This application utilizes the following packages: Express, Webpack (and its server and PWA manifest packages), Babel, CSS-loader, Concurrently, and IndexedDb. These libraries are all found in the package.json. 

  ## Installation
  This application is hosted on Heroku! Please go to the following linkand open the application there!
<br>
https://challenge-19-jate-pwa-joshuaor.herokuapp.com/
<br>
 Once the app is opened, users are able to download it. If the heroku deployment fails or expires in the future, users can also download this github repo. Once done, open it with a coding enviornment, like VS Code. In VS Code, and in the proper directory, users can type npm i to install dependencies. Typing npm start will build the dist folder and launch the app on the given local port (3000).

  ## Useage
  The app itself is very simple! Once opened (locally or in browser), users can type whatever they want in JEST. If they leave the program and come back, whatever was typed will remain there! This persistance should last for 30 days. 

  ## License 
  
    *[License](#license)

  ## Contributions
  Thank you for your interest in this app! I am not accepting contributions to the code at this time, but feel free to contact me at my provided email address!

  ## Tests 
  SCREENSHOTS : 
  <br>
  JATE - Opened in Browser
  <br>
  ![image](https://user-images.githubusercontent.com/114437149/222728536-fde1830b-1a12-4d21-a5f7-37d73e20fabc.png)
  <br>
  IndexDb working - note that the first line of text is "Test!" in JATE, and in the dev tools under IndexDb, test is also displayed
  <br>
  ![image](https://user-images.githubusercontent.com/114437149/222729311-ab501eef-edcb-4c59-8c0c-68d10748dde3.png)
  <br>
  Local Storage has the same content that IndexDB does but it is able to be displayed much easier (IndexDb content couldnt have been expanded in Dev Tools)
  <br>
  ![image](https://user-images.githubusercontent.com/114437149/222729614-a12c3284-ecca-4522-b577-5075ba3af37f.png)
  <br>
  Desktop icon created when Install is clicked
  <br>
  ![image](https://user-images.githubusercontent.com/114437149/222730069-a95fff8b-de19-461e-b2ca-f88b4881f414.png)
  <br>
  Opened via desktop app - note content is available due to precache and service workers 
  <br>
  ![image](https://user-images.githubusercontent.com/114437149/222730306-0cba690b-3db9-4bf3-9c92-65923f59a4f0.png)
  <br>


  ## Questions 
  Thank you for your interest in my application, Challenge 19 - Progressive Web Apps : Text-Editor ! 
  If you have any questions, concerns, or would like to reach out for any other reason;
  My Github: JoshuaOrlandoR
  My Email: joshuaorlando.r@gmail.com


  Signed - Joshua Orlando

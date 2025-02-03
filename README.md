# Simple Weather Website
Simple weather website made using Express.JS. Project to showcase usage of APIs. [Click here to go to the website](https://andres-borges.github.io/Weather_Website/)

## Built With:
* HTML
* CSS
* JavaScript
* Node.JS
* Express.JS

## API used:
* [OpenWeatherMap](https://openweathermap.org/api)

## How to run:
1. Clone the repository to your local machine.
2. Open in your prefered IDE.
3. In the terminal, run the "npm install" command (this will make sure all the node modules are installed).
4. Create a file named ".env".
5. Inside this file, write "API_KEY = ".
6. For the API to work, you need to provide your own key. You can get it for free by creating an account at [OpenWeatherMap](https://openweathermap.org/api) and going to the "My API Keys" page ([More information here](https://openweathermap.org/appid#:~:text=Once%20you%20sign%20up%20using,additional%20API%20keys%20if%20needed.)).
7. Now, copy the default key and paste it on your ".env" file after the equal sign.
8. Go to [index.js](/index.js) and run it.
9. Click on the link that will be given in the output.

## Why Express.JS for this project?

Express.JS is used in this project to generate back-end JavaScript code, allowing for the use of server-side features such as require, env, etc. The ".env" file is where any personal and sensitive information is stored, such as the API key. By not hard-coding the key in the client-side JavaScript, there are no security concerns about losing the key or leaking important sensitive information. In other words, express.js allows for server-side coding, giving access to env files that increase security and protects sensitive and personal data.

## Screenshots
### Before search is done
![Main Page](/Screenshots/main.png)
### After search is done
![Data Page](/Screenshots/data.png)

# API-INTEGRATION

*COMPANY*:  CODTECH IT SOLUTIONS

*NAME*: SHAIK ABDULHAFEEZ

*INTERN ID*: CT06DR1513

*DOMAIN*: Full Stack Web Development
 
*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

##The task is to create a simple and interactive weather application using HTML, CSS, and JavaScript. The main goal of this project is to allow users to check the current weather information for any city in the world by typing the city name. This app will fetch live weather data from a public API called OpenWeatherMap and display it in a clean and user-friendly interface. It is a practical project that helps in understanding how web applications can communicate with external services to get real-time data.

The project starts with creating the basic structure of the webpage using HTML. The HTML file includes a container card where all the content of the weather app is displayed. Inside this card, there is a title, an input box for entering the city name, a button to get the weather information, and a result section where the weather details will appear. The input box allows the user to type the city name they want to check the weather for. The button triggers a JavaScript function that fetches the weather data from the API. Initially, the result section shows a message like “Enter a city name to get weather info,” which guides the user about what to do.

The CSS part is responsible for making the app look attractive and clean. In this project, we use a modern card design with a gradient background and smooth shadows. The card is centered in the middle of the screen, and all the elements inside it are aligned properly. The fonts are chosen to be simple and readable, and buttons and input boxes are styled to look modern. The weather information like temperature, description, wind speed, and time is displayed with different font sizes and colors to make it easy to read. For example, the temperature is bold and larger in size, the weather description is capitalized and clear, and wind speed is highlighted in red to draw attention.

The JavaScript part of this task is the main functionality of the app. It is used to communicate with the OpenWeatherMap API to get live weather data. The script starts by reading the city name entered by the user. If the input is empty, it shows a message asking the user to enter a city name. If the city name is entered, the script sends a request to the API using the fetch() function. The API returns a JSON response containing weather details like temperature, weather description, wind speed, icon, and time. This data is then processed and displayed dynamically inside the result section of the card. The app also calculates the local time of the city using the time and timezone information provided by the API. This allows users to see not only the weather but also the current time in the city they are searching for.

The app also includes error handling. If the user enters a city that does not exist or there is a problem with the API, the app shows an error message in red, telling the user that the city was not found. This makes the app more user-friendly and prevents it from crashing when an incorrect input is given.

In addition, the app uses icons provided by OpenWeatherMap to visually show the current weather condition, like sunny, rainy, cloudy, or snow. This helps users to quickly understand the weather without reading the text.

Overall, this weather app project is a simple, interactive, and practical web application that teaches important concepts of web development. It involves working with HTML for structure, CSS for styling, and JavaScript for logic and API integration. Users can learn how to fetch data from external sources, handle JSON responses, and dynamically update the webpage. The app is fully responsive, visually appealing, and provides real-time weather information for any city in the world. It is a useful tool for learning and practicing web development skills while creating a project that is both functional and attractive.

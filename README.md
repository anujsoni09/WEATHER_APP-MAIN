The Weather App is a web application that allows users to check the current weather conditions by searching for a city name or pin code. It provides features such as dark and light mode, date and time display, weather information, humidity levels, and wind speed.

## **Features**
1.Search weather by city name or pin code.<br>
2.Toggle between dark mode and light mode.<br>
3.Display current date and time.<br>
3.Show current weather conditions, humidity, and wind speed.<br>
4.Responsive Design<br> 
## **Technologies Used**
        HTML: For structuring the web pages.<br>
        CSS: For styling the web pages.<br>
        JavaScript: For adding interactivity.<br>
        React.js: For building the user interface.<br>
        Axios: For making HTTP requests to the OpenWeather API.
## **Installation and Running the Application Locally**
To run the Weather App on your local machine, follow these steps:<br>
1. Download the project: Clone or download the repository to your local machine.
   git clone <repository-url>
3. Navigate to the project directory.
    cd weather-app<br>
4. Install dependencies: Run the following command to install the required npm packages
    npm install
5. Install Axios: Run the following command to install Axios, which is used to make HTTP requests.
   npm install axios
6. Start the server: Run the following command to start the development server.
   npm start
7.  Open the application: Open your browser and go to http://localhost:3000 to view the Weather App.

$$ **Known Issues or Limitations**
1. API Rate Limiting: The OpenWeather API has a rate limit for free-tier users, which might affect the number of requests that can be made in a given time period.<br>
2. Limited Data: The app only displays current weather conditions and does not provide forecasts or historical data.

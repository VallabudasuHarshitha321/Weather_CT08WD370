#Weather_CT08WD370 
#weather_task2 
Intership : CODTECH IT SOLUTIONS 
Task-2    : WEATHER FORECAST APP 
Name      : Vallabudasu Harshitha 
ID        : CT08WD370 

Code Explaination : 
This code represents a simple weather application built using HTML, CSS, and JavaScript. 

###HTML: 
- It starts with the standard HTML5 doctype declaration.
- Inside the `<head>` section, it includes meta tags for character set and viewport settings, a link to import Google Fonts, and sets the title of the page.
- In the `<body>` section, there's a main container div with the class "weather-app".
- Inside this container, there's a form for user input (city search), a section to display city and date information, another section to display temperature information, and a final section to display additional weather details like wind speed, humidity, and visibility.

###CSS:
- Resets default margin, padding, and box-sizing.
- Sets the background color, font family, and height for the body.
- Styles the weather app container with specific dimensions, margins, padding, and border radius.
- Styles form inputs, buttons, and other elements for a cohesive look and feel.
- Defines styles for various sections within the weather app, such as city and date, temperature, and additional weather info.

###JavaScript:
- Defines an API key for accessing weather data from the OpenWeatherMap API.
- Defines an asynchronous function `fetchWeatherData(city)` to fetch weather data for a given city using the Fetch API.
- Handles errors during data fetching and logs them to the console.
- Defines a function `updateWeatherUI(data)` to update the UI with weather data received from the API response.
- Listens for form submissions, prevents default behavior, and calls `fetchWeatherData(city)` with the input city value.
- Defines a mapping function `getWeatherIconName(weatherCondition)` to map weather conditions to appropriate icons.

Conclusion:
Overall, this code creates a weather application that allows users to search for a city and see its current weather conditions. The UI is styled using CSS, and JavaScript handles the fetching and updating of weather data.

# MLH Prep Project

Over the next 2 weeks, you'll be building a React App that works with various APIs (Application Programming Interfaces) that talk to different data sources to do cool stuff.

We're using the [OpenWeather API](https://openweathermap.org/current) to get weather data on different cities. Your challenge over the next 2 weeks is to build out this website and add even more functionality to it. At the moment, it displays basic information about a location when you type it in. Check out [Issues](/issues) for some more ideas!

You'll need to get your own API Key from their website (for free) and add it as an environment variable in a `.env` file. We have a template available as `example.env`.

You'll be using React initially to build this. If you're new to React, check out the [website](https://reactjs.org) for some information on getting started! 

***
### Creating API key for Food Recommendations:
[Spoonacular API](https://spoonacular.com/food-api/docs) can be used for food recommendations
Steps:
- Click on 'Start Now' button to go to the signup page.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/73184612/159624513-7ef7f754-e2be-46c6-9a14-6d4bc93d9821.png">

- Sign Up with email. Confirm your account by following the steps in the email sent by spoonacular
<img width="500" alt="image" src="https://user-images.githubusercontent.com/73184612/159624823-98c00147-d4b9-44c8-bd25-98290f6d5517.png">

- After confirming, log in to your account 
- Go to the profile section on the dashboard, and click on 'Show/Hide API key' button
<img width="500" alt="image" src="https://user-images.githubusercontent.com/73184612/159625250-9894be85-d265-4445-8882-c953d59225ac.png">

- Copy this API key. Create a .env file in the root of your local repository, and add the API key inside it as: <br />
REACT_APP_FOODAPIKEY=<your_key>

- Restart the terminal and run the app.

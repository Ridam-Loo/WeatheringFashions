# WeatheringFashions
Python code that uses the OpenWeatherMap API to get the weather in your location, and suggests clothing items from a local database based on the weather condition and current fashion trends.

In this code, we first import the necessary modules and set our OpenWeatherMap API key and location coordinates. We then make a request to the API and extract the temperature and weather condition. We use a dictionary to map clothing items to their suggested weather conditions, and another dictionary to map clothing items to current fashion trends. We loop through the clothing items and conditions, and append items to a list of clothing suggestions based on the weather condition and fashion trends. Finally, we print the list of suggestions.

Note that this code assumes you have a database of clothing items that can be accessed in your code. You would need to modify the `clothes_dict dictionary` to match the clothing items in your database, and modify the logic for accessing and querying your database as needed.

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

(Contributions text taken directly from othneildrew/Best-README-Template) 

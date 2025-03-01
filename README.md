# WeatherNow

WeatherNow is a simple web application that provides real-time weather information for any city. Users can input a city name and receive current weather conditions for that location.


## Features

- **City-based Weather Search**: Enter any city name to get instant weather updates.
- **Real-time Data**: Utilizes a weather API to fetch the most current information.

## Tech Stack

- **Backend**: Flask 
- **Frontend**: HTML, CSS
- **Templating**: Jinja2 for dynamic HTML rendering
- **API**: Weather API (OpenWeatherMap)

## Installation

1. Clone the repository:
git clone https://github.com/ksandeep18/WeatherNow_.git
cd weathernow

2. Set up a virtual environment:
python -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate

3. Install dependencies:
pip install -r requirements.txt

4. Set up your API key:
- Add your weather API key to the `.env` file

5. Run the application:
flask run

6. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Enter a city name in the search bar.
2. Click the "Get Weather" button.
3. View the current weather conditions for the specified city.
4. If you Entered Invalid city name then it will show you Enter a valid city name.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgements

- [OpenWeatherMap API](https://openweathermap.org/api)


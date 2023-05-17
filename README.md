# Weather App

A simple weather app built with React and Django. The app retrieves weather data for a specific location from an external API, and displays the weather details for the current day, previous day, and next day.

## Installation

1. Clone the repository: `git clone https://github.com/Taraansh/weather_app_frontend`
2. Install dependencies for the backend server: `pip install -r requirements.txt`
3. Create a `.env` file in the root directory and add the following line to hide the API key:
   ```
   WEATHER_API_KEY=your-api-key
   ```
4. Start the Django server: `python manage.py runserver`
5. Install dependencies for the frontend app: `cd frontend && npm install`
6. Start the React app: `npm start`

## Usage

1. Open the app in your web browser at `http://localhost:3000`.
2. Enter the name of a city in the search bar and click the "Search" button.
3. The weather details for the current day, previous day, and next day will be displayed for the entered city.

## Technology Stack

- React
- Django
- Python Decouple (to hide API key)
- Bootstrap

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
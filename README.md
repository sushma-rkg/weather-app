# Weather Now

A beginner-friendly weather app that fetches real weather data from the OpenWeatherMap API.

## Setup (2 steps)

### 1. Get a free API key
1. Go to [openweathermap.org/api](https://openweathermap.org/api)
2. Create a free account
3. Copy your API key from the dashboard

### 2. Add your key to the code
Open `index.html` in a text editor and find this line near the bottom:

```js
const API_KEY = 'YOUR_API_KEY_HERE';
```

Replace `YOUR_API_KEY_HERE` with your actual API key.

## Run the app

Open `index.html` in any web browser. No server needed.

## What this teaches

- What an API is (a service you send requests to)
- What an API key is (a password that identifies your app)
- How `fetch()` sends a request and waits for a response
- How JSON data comes back from an API
- How to display that data on a web page

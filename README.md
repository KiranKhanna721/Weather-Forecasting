# Weather Forecasting

Checks the current weather for any city with the **OpenWeatherMap** API.

## Features

For the city you enter, it shows:
- Weather description
- Temperature (°C)
- Humidity
- Pressure

## Files

| File | Purpose |
|------|---------|
| `app.py` | Streamlit web app |
| `main.py` | Command-line version |

## Getting started

1. Get a free API key from [openweathermap.org](https://openweathermap.org/api).
2. Put it into the `api_key` variable. An environment variable is better than writing it in the code.
3. Run:

```bash
pip install streamlit requests
streamlit run app.py
# or
python main.py
```

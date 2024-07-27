# API Details

## Endpoints

### Get Current Weather

`GET /current`

Retrieves the current weather for a specified city.

#### Parameters

- `city` (required): Name of the city

#### Example Response

```json
{
  "temperature": 22.5,
  "humidity": 60,
  "description": "Partly cloudy"
}

### Get Forecast

`GET /forecast`

Retrieves the current weather for a specified city.

#### Parameters

- `city` (required): Name of the city
- `days` (opt): Number of the forecast days (default 5)

#### Example Response

```json
[
  {
    "date": "2023-07-26",
    "temperature": 24,
    "description": "Sunny"
  },
  {
    "date": "2023-07-27",
    "temperature": 22,
    "description": "Cloudy"
  }
]

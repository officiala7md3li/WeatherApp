# OpenWeatherMap API Integration

## Endpoints
- **Current Weather**: `/data/2.5/weather?q={city}&appid={key}&units=metric`
- **5-Day Forecast**: `/data/2.5/forecast?q={city}&appid={key}&units=metric`

## Error Handling
- HTTP 404: City not found banner displayed in UI.
- HTTP 401: Invalid API key notification in console.
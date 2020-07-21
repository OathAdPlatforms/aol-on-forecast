### Forecast client

Client library for forecast service.

### Usage

```scala
// forecast second week given first week data
// client chooses service URL based on FORECAST_API_SERVICE_URL env variable. Eg. set it to http://localhost:9072/forecast-api/forecast 
val client = new ForecastClientImpl()
val forecast = client.forecast(Array(1, 2, 3, 4, 3, 2, 1), 7)
```
test

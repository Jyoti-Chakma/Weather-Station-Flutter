# Weather Station

This project is for developing a weather station Flutter. It uses Open Weather API to get the weather data.

## Acknowledgements

- [Open Weather API](https://openweathermap.org/api)


## Python Version

- [Weather-Station-with-Flask](https://github.com/Jyoti-Chakma/Weather-Station-with-Flask)

## API Reference

#### Get Weather Data

```http
  GET /api/${city_name}&appid=${app_id}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `app_id`  | `string` | **Required**. Your API key |

#### Parameter

| Parameter    | Type  | Description            |
| :----------- | :---- | :--------------------- |
| `temp`       | `int` | Main Temperture        |
| `feels_like` | `int` | Feels Like Temperature |
| `temp_min`   | `int` | Minimum Temperature    |
| `temp_max`   | `int` | Maximum Temperature    |
| `humidity`   | `int` | Humidity               |
| `pressure`   | `int` | Pressure               |
| `speed`      | `int` | Wind Speed             |

## Screenshots

| Dhaka Weather                                                                                    | Delhi Weather                                                                                    | Tianjin Weather                                                                                     |
|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| ![dhaka](https://github.com/Jyoti-Chakma/Weather-Station-Flutter/blob/master/Screenshots/1.jpeg) | ![delhi](https://github.com/Jyoti-Chakma/Weather-Station-Flutter/blob/master/Screenshots/2.jpeg) | ![tianjin](https://github.com/Jyoti-Chakma/Weather-Station-Flutter/blob/master/Screenshots/1.jpeg) |


## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/Jyoti-Chakma/Weather-Station-Flutter/blob/master/LICENSE.txt)

## Contributing

Contributions are always welcome!

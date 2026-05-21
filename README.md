
# Weather Redux

![GitHub Tag](https://img.shields.io/github/v/tag/perryBunn/streamDeck-weatherPlugin?style=flat&logo=github&logoColor=000&label=%20&color=fff&link=https%3A%2F%2Fgithub.com%2FperryBunn%2FstreamDeck-weatherPlugin)

`Weather Redux` is a plugin that displays the weather condition as a picture image, the city name and the temperature of a given location. It is connected to multiple providers and needs an API Key to connect. This will be a plugin that I maintain and forked from [streamdeck-weather](https://github.com/JohannesKlauss/streamdeck-weather).

Possible providers:

- WeatherAPI
- OpenWeather

Optionally, you can choose the frequency of fetching updated data and the temperature unit (Celsius or Fahrenheit).

# Button settings

The button is configured as follows:

- Title: Please do not set any value to display the temperature correctly.
- Image: Please do not update the picture to display the weather icon correctly.
- Provider: the weather information provider: WeatherAPI or OpenWeather.
- API key: your provider account key available in your account information on the associated provider website.
- City Name: the city for which the information will be displayed on the button.
- City ID: an optional identifier for the city, useful when the city name is ambiguous.
- Temperature: the temperature unit (Celsius or Fahrenheit).
- Fetch frequency: how often the data is updated.
- Display city name: Provides the possibility choose where to display the city name or not.
- Round to the nearest degree: Provides the possibility to show / hide digits after decimal point.
- "Get my API key" button: to retrieve the key for your account.
- "Report bug" button: to report a bug.

# Features

- Choice of Weather provider
- Choose temperature unit
- choose fetching frequency of the weather data
- Weather condition icon fit to display

![screen](screenshot.png)

# Installation

In the Release folder, you can find the file `com.jk.weather.streamDeckPlugin`. If you double-click this file on your machine, Stream Deck will install the plugin.

# Source code

The `src` folder contains the source code of the plugin.

Application main icon made by [Smashicons](https://www.flaticon.com/authors/smashicons) from [www.flaticon.com](https://www.flaticon.com/)

# city explorer

I use in serevr city explorer 3 APIs

+ movies API (TMDB).

+ Weather API (weatherbit.io).

+ Location API (locationalQ).

## Movie API

• API Description

This API talk about movies and information’s about movies, actors and TV shows. This API how interested about movies and can use this API to take data about moves

• API Usage

Use search it is query and key MOVIE_API_KEY. I use this way to search about movies

`<https://api.themoviedb.org/3/search/movie?api_key>=${process.env.MOVIE_API_KEY}&query=${city}`

• API Endpoints/Request URLs

`<https://api.themoviedb.org/3/search/movie?api_key>=${process.env.MOVIE_API_KEY}&query=${city}`

`{process.env.REACT_APP_LOCATIONIQ_SERVER}/Movies?city=${city}`

• Authentication Key

 The Movie DB API Docs KEY : a6347ba795049ad33d9beeb13564a83

## Weather API (weatherbit.io)

• API Description

This API talk about weather and give you all information’s about weather. And you can forecast for any point in worlds, you can use historical weather data for the past 10+ years sourced from over 120,000 stations, doppler radar, satellite, and atmospheric re-analysis products.

• API Usage

I use search I can search by name city to git weather this city and key  WEATHER_API_KEY

`<http://api.weatherbit.io/v2.0/forecast/daily?city>=${city}&key=${process.env.WEATHER_API_KEY}`

• API Endpoints/Request URLs

`<http://api.weatherbit.io/v2.0/forecast/daily?city>=${city}&key=${process.env.WEATHER_API_KEY}`

  `${process.env.REACT_APP_LOCATIONIQ_SERVER}/Weather?city=${city}`

• Authentication Key

Weather Bit API KEY : 9adb9bb8f3d54301ac9329e762f7d430

## Location API (locationalQ)

• API Description

This API for locations cities any where and git cities information’s and image map for this city

• API Usage

I use search to search cities and key APP_LOCATIONIQ_KEY and searchQuery parameters to city name
`<https://us1.locationiq.com/v1/search.php?key>=${process.env.REACT_APP_LOCATIONIQ_KEY}&q=${this.state.searchQuery}&format=json`

• API Endpoints/Request URLs

`<https://us1.locationiq.com/v1/search.php?key>=${process.env.REACT_APP_LOCATIONIQ_KEY}&q=${this.state.searchQuery}&format=json`

• Authentication Key

 Geocoding API KEY : pk.74fc0ce092a79f45868dfa208094bd30

#### *resources*  >>>>>>>>>>

<https://locationiq.com/docs>

<https://www.themoviedb.org/documentation/api>

<https://www.weatherbit.io/api/weather-forecast-16-day>



### *links* >>>>>>>>>>>>>

this the live URL 👇

<https://city-excplorer.netlify.app>


heroku link 👇

<https://city-explorer03.herokuapp.com>

when open heroku just open APP

and add beside link /weather or Movie?city=Amman
to git data.



repo link for backend (API) 👇

<https://github.com/leenahmad/city-explorer-API>

repo link for frontend 👇

<https://github.com/leenahmad/city-explorer>

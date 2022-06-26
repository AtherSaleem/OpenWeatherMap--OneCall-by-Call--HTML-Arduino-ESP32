# OpenWWeatherMap-HTML-Arduino
Open Weather One Call API to HTML Dashboard and ESP32 App

Checkout video description of this model at:
https://youtu.be/x6Fl6GETBLo

How I generated , this long code with ease, will also be available at Channel, in near future IA

1) In HTML Graph File , On Line 182 , Enter your own API Key replace"abcd"
    daText = '{"lati":"33.6844", "longi":"73.0479", "apiKey":"abcdabcd"}'
2) If you use External Text File, Sample is enclosed, Again, Change API key: "apiKey": "abcd"

3) HTML RAW DATA Display: Use your API Key at Line Number 817
    const da_url = "https://api.openweathermap.org/data/3.0/onecall?lat=33.6844&lon=73.0479&appid=abcd&units=metric";

3) INO File is Arduino model for ESP32 - You will need to install relevant  libraries.

This is my first GIT project, Hope not to make a mess out of it.
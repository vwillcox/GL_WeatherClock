# GU_WeatherClock
A Weatrher display and Clock on the Pimoroni Galactic Unicorn
![Example](IMG_20231202_161041-EDIT.jpg)

# Usage
Upload everything to your Galactic Unicorn (Using Thony or your choice of tools)

Edit '''main.py'''

Line 32 & 33:
```
city = 'MARS'
country_code = 'UK'
```
Add your city and country

line 43
```
open_weather_map_api_key = ''
```

Get your API key from 
https://home.openweathermap.org/api_keys

Edit ```secrets.py``` with your WIFI details

```
WIFI_SSID = 'YOUR SSID'
WIFI_PASSWORD = 'YOURPSK'
WIFI_COUNTRY = 'GB'
```

---
Special thanks goes to the original icon author
https://www.dovora.com/resources/weather-icons/

---
Get your display from Pimoroni : https://shop.pimoroni.com/products/space-unicorns?variant=40842033561683 

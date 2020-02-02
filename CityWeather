import pyowm

owm = pyowm.OWM('2fcc348ab08d9beb8db26c2a1285c5ff')
report = owm.weather_at_place('Laurel, US')
w = report.get_weather()
temp = w.get_temperature('fahrenheit')['temp']
print(f'The temperature : {temp}')

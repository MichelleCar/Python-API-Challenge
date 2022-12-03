# Leveraging the power of the web with APIs
## Python-API-Challenge

![68747470733a2f2f63646e2d696d616765732d312e6d656469756d2e636f6d2f6d61782f313630302f312a5f4a4a546b6e4a5950784a504c4e454542336a6837512e676966](https://user-images.githubusercontent.com/115101031/205453329-8972048f-c83e-4db7-adb2-ba0fc82150e0.gif)

## Background

APIs (application programming interface) is a software intermediary that allows two applications to talk to each other. APIs are an accessible way to extract and share data within and across organizations.

APIs are all around us. Every time you use a rideshare app, send a mobile payment, or change the thermostat temperature from your phone, you’re using an API.

When you use one of the above apps, they connect to the Internet and send data to a server. The server then retrieves that data, interprets it, performs the necessary actions, and sends it back to your phone. The application then interprets that data and presents you with the information you wanted in a readable way. 

Companies are digitally transforming faster than ever to keep up with their competitors and increase customer demands. APIs help them digitize, connect, and innovate across their products and services. APIs are a key enabler of these efforts. In fact, 90% of executives say that APIs are mission-critical to their businesses. By adopting API-driven strategies, they can drive growth and innovation. Incorporating APIs into business operations can help:
* Simplify and accelerate their go-to-market strategies
* Enhance customer experiences
* Improve operational agility and speed
* Develop and pursue new revenue, market, and channel opportunities

Video: https://play.vidyard.com/Le2QkL3lixu3GmssEXYyLg.jpg 
SOURCE: https://www.mulesoft.com/resources/api/what-is-an-api 

## Project Details

Data's true power is its ability to definitively answer questions:

1. Create a Python script to visualize the weather of over 500 cities of varying distances from the equator (northern and southern hemisphere), using geographical coordinates, temparature, humidity, cloudiness, and wind speed.

2. Use acquired weather data skills to plan future vacations, searching for hotels in the proximity of cities of interest. 

In this project, the following APIs will be used:
* Weather API (https://openweathermap.org/api): using current weather data for any location including over 200,000 cities. Weather data is collected and processed from different sources such as global and local weather models, satellites, radars and a vast network of weather stations.  
* Geoapify APR (https://www.geoapify.com/): a feature-rich location platform, offering maps, address and location search, route optimization, reachability analysis, geodata access, and more.  
  
## Observations of the Results

### Global Weather Patterns

* As would be expected, as you move farther away from the equator (positive correlation), the maximum temperatures of a particular location (city) decreases. Cities closest to the equator record the highest temperatures due to the spherical structure and slight tilt of Earth on its axis. The results confirm that the equator experiences more stable tempteratures year-round due to the fact that sunlight hits the Earths surface from almost directly above.

<img width="517" alt="Screen Shot 2022-12-03 at 2 08 17 PM" src="https://user-images.githubusercontent.com/115101031/205457778-89295500-0349-4b02-893d-c431e780a6f5.png">

* Though there was no strong correlation suggested in the scatter plot for wind speed, though interestingly it is observed that there is a slight positive correlation in the northern hemisphere and sligh negative correlation in the southern hemisphere. 

* A high density of clouds in equatorial regions is one of the reasons why they get plenty of rain every year. This warm air unloads almost all of its moisture in the clouds above equatorial regions, but still continues to move higher up. This warm air, now also dry (on account of depositing all its moisture in equatorial clouds), begins to move towards the pole, but is stopped due to the Coriolis force, which prevents it from continuing in the direction of poles. As a result, it loops back closer to the surface in the tropics. (SOURCE: https://www.scienceabc.com/eyeopeners/why-are-tropical-regions-hotter-than-equatorial-regions.html)

### Vacation Planning

* When traveling, you might take into consideration the weather patterns, for example the amount of humidity to expect (temparature, cloud cover, rain, etc.). Not surprsingly, the highest humidity values are concentrated around equatorial and tropical locations.

<img width="782" alt="Screen Shot 2022-12-03 at 2 15 28 PM" src="https://user-images.githubusercontent.com/115101031/205457978-c6bd59ad-42ba-4a35-9390-7a0ac46f9f82.png">

* Determining the proximity of hotels to cities of interest, show few options available within a 10,000 meter distance.
<img width="776" alt="Screen Shot 2022-12-03 at 2 18 39 PM" src="https://user-images.githubusercontent.com/115101031/205458094-d1ab489d-d72a-431e-a7e4-afe1a06bd52d.png">

# CAT201 Project: Android Weather Application | WeatherApp
The repository contains the source code for an Android weather app that our group created as the final project for the **CAT201** course at **Universiti Sains Malaysia**.
The weatherapi.com API is used by the android application to retrieve current weather data and present it to the user along with the day's hourly prediction. Users may also search for a specific city, and the app will provide the current weather as well as the hourly prediction for the specified (correct) location. 
## Key Points
- The android application is developed in **JAVA** programming language with user-friendly
graphical user interface in a team of four members:
    1. Mohamad Firdaus Bin Kasah Hamid@Kasmidy
    2. Ahmad Alif Danial Bin Ahmad Shobri
    3. Farah Afifah Binti Zulkefli
    4. Mohammad Ryyan Rashid
-  The latest Human-computer interaction (HCI) principles were practiced while designing,
assessing and implementing the application.

## Dependencies
- Picasso: https://square.github.io/picasso/
- Volley: https://developer.android.com/training/volley
- Google Play Services Location: https://developers.google.com/android/guides/setup
```
dependencies {
    implementation 'com.squareup.picasso:picasso:2.8'
    implementation 'com.android.volley:volley:1.2.1'
    implementation 'com.google.android.gms:play-services-location:17.0.0'
}
```

## Releases
- v_1.0.0 | January 29, 2022 | The first release with current weather and weather forecast features.

## Screenshots
1. WeatherApp - Landing page <br>
    <p align="center">
        <img src="https://github.com/ryyanrashid01/CAT201_WeatherApp/blob/main/screenshots/landingScreen.jpg" alt="Landing Page" style="width:200px;"/>
    </p>
2. Seaching for a city <br>
    <p align="center">
        <img src="https://github.com/ryyanrashid01/CAT201_WeatherApp/blob/main/screenshots/searchCity.jpg" alt="Search for city" style="width:200px;"/>
    </p>
3. Results for the seached city <br>
    <p align="center">
        <img src="https://github.com/ryyanrashid01/CAT201_WeatherApp/blob/main/screenshots/cityResults.jpg" alt="Results for city" style="width:200px;"/>
    </p>

The background picture of the application's landing page varies based on the time of day. A image of a blue sky will be displayed if it is day at the user's location or in the city that the user has searched. If it's nighttime, an image of a starry night will be displayed.

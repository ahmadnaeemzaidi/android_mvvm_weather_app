# Android MVVM Architecture Weathe App using ViewModel + LiveData + Kotlin + Retrofit

MVVM Architecture is one of the most popular and latest architecture to develop a maintanable and managable codebase. We are developing a sample `Weater Forecast` Android App with `MVVM Architecture` using `Kotlin` language and `Retrofit` network calling library..

### Prerequisites
Basic `Kotlin` and knowledge of `HTTP` request by `Retrofit` library are required for this project.

### Open Weather API
We will use [Open Weather Map API](https://openweathermap.org/api) for collecting weather information. To get the real weather information of a city, you need to sign up and get your own `APP ID`. Otherwise you can test the API with their sample `BASE URL` and sample `APP ID` without creating account.

### Project Setup
Clone the project and open it using Android Studio. Then open your `local.properties` file under `Gradle Scripts`. You need to specify the `base_url` and `app_id` in your `local.properties` file.

**Note:** The free version of Open Weather API allows maximum 60 API calls per minute.
### Run the project
Sync the `Gradle` and run the project. Install APK on your emulator or real device. Turn on the internet of your testing device.
### Disclaimer
There are some other ways of implementation of `MVVM`. We find most of the MVVM tutorials are covered with `Rx` and `Dagger`. But it's not mandatory to use `Rx` or `Dagger` in MVVM. Even without using `LiveData` you can implement MVVM architecture. The main difference between MVP and MVVM is: `Presenter` is not `Life Cycle` aware. On the otherhand `ViewModel` is `Life Cycle` aware.

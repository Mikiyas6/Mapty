
---


# 🗺️ Mapty Project


**Mapty** is a JavaScript project aimed at helping users track workouts based on their real-time location 🏃‍♂️🚴‍♀️. This project runs entirely in the browser and integrates a dynamic map to visualize and manage workouts.

## 📸 Screenshot

![Steps Component](https://github.com/Mikiyas6/Mapty/blob/master/mapty%20__%20Map%20your%20workouts.png)


- Solution URL: [Github-link](https://github.com/Mikiyas6/Mapty)
- Live Site URL: [Page-link](https://mikiyas6.github.io/Mapty/)


## 🌟 Features


### 📍 Location-based Workouts
Mapty allows users to log and manage two types of workouts:
- **Running 🏃‍♂️**
- **Cycling 🚴‍♀️**


### 🗺️ Interactive Map Integration
- The app retrieves the user's location using the browser's geolocation API 🌍.
- It displays a map using the **Leaflet** library 🗺️, enabling users to:
  - **Click** on the map to add a workout location.
  - **Submit workout data**, which automatically retrieves:
    - **Weather Information** 🌦️ using external APIs.
    - **Location Details** 🏞️.
    - **Workout Calculations**:
      - **Pace 🏃‍♂️** for running workouts.
      - **Speed 🚴‍♀️** for cycling workouts.


### 🖥️ User Interface Functionalities
Mapty comes packed with features that give users control over their workout data:
- **Edit** existing workouts 📝.
- **Delete** individual workouts 🗑️.
- **Clear** all workouts with one click 🔥.
- **Sort** workouts by different criteria 🔄.
- **Navigate** directly to a workout on the map by clicking the workout in the sidebar ⬅️🗺️.
- View a complete **overview** of all logged workouts 📊.


## 🛠️ Bugs / Improvement Suggestions


- The app relies on external APIs, some of which have limits on the number of calls you can make without an API key 🛑. To overcome this, you need to **register for an API key** 🔑.
- **Potential Improvements** to make the app even better:
  - Connect the app to a **database** for persistent storage of workouts 📂.
  - Use a more robust **library for unique ID generation** to handle workouts efficiently 📛.
  - Add features such as:
    - **Drawing routes** on the map 🖊️.
    - **Mapping routes** from point **A to B** 🛤️.


## 👩‍💻 Object-Oriented Structure


Mapty uses OOP principles for code organization:


- **Workout Class**: The parent class that handles shared properties for all workouts.
- **Running Class 🏃‍♂️**: A child class that extends the Workout class, handling properties and methods specific to running.
- **Cycling Class 🚴‍♀️**: A child class extending the Workout class for cycling-specific data.
- **App Class 🖥️**: Manages the entire application, creating instances of running and cycling workouts, and coordinating data display and interactions in the user interface.


## 📂 Data Handling


- Workout data is **persisted** in the browser's **local storage** 💾.
- The **Leaflet** library is used to render maps and map interactions 📍.
- Data for workouts includes **distance**, **duration**, **pace**, and **speed** calculations based on user input and geolocation 📈.


## 🔗 External Libraries and APIs


- **Leaflet**: Used for rendering the interactive map 🗺️.
- **Geocode.xyz API**: Retrieves location coordinates 🌍.
- **OpenWeatherMap API**: Fetches weather data based on the user's location 🌦️.


## 🛠️ Installation Guide


1. Make sure you have **Node.js** installed 🟢.
2. Run `npm init` to initialize the project ⚙️.
3. Start building and enjoy exploring your workouts on the map 🚀!


---






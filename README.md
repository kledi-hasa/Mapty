# Mapty

A workout tracking application that allows you to log your running and cycling workouts on an interactive map.

## Features

- Interactive map using Leaflet.js
- Log running and cycling workouts
- Automatic geolocation to center the map on your location
- Workout data persistence using local storage
- Click on the map to add a new workout
- View workout details including distance, duration, pace/speed, and cadence/elevation
- Click on workout items in the sidebar to navigate to their location on the map

## How to Use

1. Open `index.html` in a web browser
2. Allow location access when prompted
3. Click anywhere on the map to add a new workout
4. Fill in the workout details:
   - Select workout type (Running or Cycling)
   - Enter distance (km)
   - Enter duration (minutes)
   - For running: enter cadence (steps per minute)
   - For cycling: enter elevation gain (meters)
5. Click OK to save the workout
6. Your workouts are automatically saved to local storage

- Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
- Leaflet.js (map library)
- OpenStreetMap (map tiles)
# Real-Time Location Tracking Web Application

This project is a simple web application that tracks the real-time location of a user, displays it on a Google Map, and optionally sends the location data to a server for further processing. It utilizes the Geolocation API to obtain the user's location and the Google Maps JavaScript API to visualize the location on a map.

## Features

- **Geolocation**: Requests the user's location using the browser's Geolocation API.
- **Google Maps Integration**: Displays the user's location on a Google Map with a marker.
- **Server Communication**: Sends the user's latitude and longitude to a specified server endpoint via a POST request.
- **Error Handling**: Provides feedback to the user in case of permission denial or other location errors.

## Prerequisites

To use this code, you need:
- A Google Maps API key. You can obtain one by following [Google's instructions](https://developers.google.com/maps/gmp-get-started).
- A web server to host the HTML file, or you can use platforms like GitHub Pages, Netlify, or Glitch.

## Getting Started

### 1. Clone the Repository

If you're using GitHub, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository-name.git

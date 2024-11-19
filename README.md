# PhotoWeb Zoom 

A web-based application that enables you to access your device's camera, apply an adjustable zoom effect, and capture high-quality zoomed-in photos. 

## Features
- Accesses the back camera for capturing videos and photos.
- Provides a zoom range from 1x to 1000x.
- Displays the zoomed video feed in real time.
- Allows capturing the zoomed video view as a photo.
- Saves captured photos as PNG files.

## Installation
1. Clone or download this repository.
2. Save the provided HTML file to your local machine.

## Usage
1. Open the HTML file in a browser (preferably Google Chrome or any modern browser that supports camera access).
2. Grant camera access when prompted.
3. Use the zoom slider to adjust the zoom level in real time.
4. Click the **Capture Photo** button to save the current view as a PNG file.

## Code Overview

### HTML
Defines the structure of the application, including:
- Video feed to show the camera input.
- A canvas element for displaying the zoomed video.
- Controls for adjusting zoom and capturing photos.

### CSS
Styles the interface with:
- A dark background for a sleek look.
- Styled video, canvas, and buttons.

### JavaScript
Implements the functionality:
- Accesses the user's camera using the `getUserMedia` API.
- Renders the zoomed video feed in a `canvas` element.
- Allows capturing and downloading photos.

## File Details
```plaintext
index.html - The main file for the Crazy Super Zoom Camera app.

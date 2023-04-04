# ASCII Video

This is a simple project that converts a live video feed into ASCII art in real-time. It uses the p5.js library to capture video from the user's webcam and convert each pixel into a corresponding ASCII character, based on its brightness.

## Demo

You can view a live demo of this project [here](https://ascii-video-starlove.vercel.app/)

## Getting Started

To run this project, simply clone or download the repository and open the `index.html` file in a web browser. Make sure to allow access to your webcam when prompted.

## How it Works

The `density` variable defines a string of ASCII characters, ordered by brightness from darkest to lightest. The program reads each pixel from the video feed, calculates its brightness, and assigns an ASCII character based on that brightness.

The resulting ASCII art is displayed on the webpage in a `<div>` element with the `asciiDiv` id.

## Known Issues

This project is very simple and has limited functionality. Some potential issues to be aware of include:

-   The size of the video feed is fixed at 70x55 pixels.
-   The frame rate is not optimized and may be slow on some machines.

## Authors

This project was created by Anubhav Negi. Special thanks to the coding train.

## License

This project is licensed under the MIT License. 
## Modular Audio Visualizer Circle

Mark Renzi
https://a4-mark-renzi.glitch.me

- The application was designed to learn more about audio visualization from raw frequency data using WebAudio and Canvas.
- The biggest challenges I faced were designing an algorithm that smoothly drew a path between points using quadraticCurveTo() so that I could avoid dynamically defining control points of bezier curves. I originally designed the visualizer drawing rectangles in a circle, which was nice to rotate the matrix, but using a path, I needed to convert polar coordinates to cartesian coordinates, and this took hours to get working perfectly, especially when I wanted to smooth the gaps between the points. Eventually the final challenge was some learning required to use a fade-in transition through css on my HUD, or settings menu.
- I wanted the main screen to be as simple as possible. It says click to start, and then explains that you can click or tap anywhere else to show/hide settings. The settings are names somewhat descriptively but the most interesting part of this app is testing what everything does. I recommend testing all of the themes before even touching the colors or adjustment sliders.

- There are so many fun combinations, but the stylized theme with the white background has to be my favorite:
  ![Stylized theme with white background](https://cdn.discordapp.com/attachments/121797037942374400/1299855959144796211/image.png)

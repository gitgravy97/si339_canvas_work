# si339_canvas_work

Requirements

1) Create a canvas element with a border. The canvas should be about 80% the width and 80% height of the screen. If the window is dynamically resized, you do not need to resize the canvas, but if I use Inspect element to switch to different device size it should.

2) Create a "pen" that moves with the mouse by drawing arcs. The default color should be red. If you move the mouse quickly the line will be choppy.

3) Alternate the pen colors by hitting the pressing the "b" for blue, the "g" for green, the "r" for red, and the "y" for yellow.

4) Use the up (larger) and down (smaller) arrow keys to change the radius of the pensize.  Make sure that the pen can never be set to 0 or less.

5) Clear the canvas by using the space bar.

6) React to touch events the same way you react to the mouse movements.

7) On a mobile device changing the orientation should clear and resize the canvas. This may be tricky so do what you need to do to make it work. (It may be more dramatic than "clearing" the canvas.

8) Add a color picker that allows the user to choose a different color. This won't work in Safari (on mobile), thats okay.
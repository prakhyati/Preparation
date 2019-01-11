# D3js - Data Driven document

### Why D3?
* Data Driven Documents
  * Flexibility 
    * make unique viz
    * lets you load your own data from any source , 
    doesn't just come with a set of predefined templates for making different common graphs like many other libraries
    * D3 gives you tools to make these charts yourself 
  * Elegance
    * build beautiful viz with ease
    * D3 handles huge volumes of data efficiently
    * easily add smooth transitions for updating elements(D3 comes with a sophisticated transition suite, which seamlessly allows us to switch up the positions of shape of the screen)
    * work with clean,well-designed code
  * Community
    * find pre-written code to do anything you want
    * everything is open source 
    * easy to collaborate with others
    
### Creating a Python3 webserver 
  * A webserver is a program that uses HTTP to serve the files that form webpages to users , in response to their requests which are forwarded by their computer HTTP clients.
  * Download python3
  * Go to the terminal and type
    * python3 -m http.server
fig1
    * The server is running on port 8000
    * we can open our local host on the browser
fig2

### SVGs - Scalable Vector Graphics
  * draw shapes with computer code
  * Rectangles,circles,ellipses,lines,texts and paths
  * Markup code similar to HTML
  * Small file size , dont lose any quality if resized
  * a jpeg of google logo takes about 23,000 bytes whereas for SVG it takes 310 bytes
  * We can inlude SVGs directly in an HTML file eg fig3
 fig3
      or we can ad them with Javascript
  * ##### <svg width="400" height="60"></svg>
    * creates a SVG canvas with the given with and height
  * For a rectangle we need to suppy an x and y position , which corresponds to the top left corner of the shape
    * ##### <svg width="400" height="60">
       ##### <!-- "x" and "y" coordinates give a shape its position (top left hand corner) -->
       ##### <rect x="0" y="0" width="50" height="50" fill="green"></rect></svg>
  
  
  

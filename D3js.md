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
    
### 
    
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
  * We can inlude SVGs directly in an HTML file
fig3
      or we can ad them with Javascript
  * creates a SVG canvas with the given with and height
  ```
 <svg width="400" height="60"></svg> 
 ```
  * For a rectangle we need to suppy an x and y position , which corresponds to the top left corner of the shape
    ```
    <svg width="400" height="60">
                <rect x="0" y="0" width="50" height="50" fill="red" stroke="black" stroke-width="2px"></rect>
        </svg>
    ```
  fig4  
   * if the co-ordinates of our rectangle lies outside our svg canvas we will not be able to see anything on the screen
   * for a circle
   ```
   <!doctype html>
<html>
        <head></head>
        <body>
                <svg width="400" height="200">
                        <circle cx="100" cy="50" r="25" fill="indigo" stroke="black" stroke-width="5px">
                        </circle>
                </svg>
        </body>
        </html>
  ```
  fig5 
   * for an ellipse
    ```
  <!doctype html>
  <html>
 <head>
 </head>
 <body>
 <svg width="400" height="200">
 <ellipse cx="40" cy="40" rx="15" ry="25" fill="grey">
 </ellipse>
 </svg>
 </body>
 </html>
  ```
fig6
  * for a line
 ```
  <!doctype html>
  <html>
 <head>
 </head>
 <body>
 <svg width="400" height="200">
 <line x1="185" y1="5" x2="230" y2="40" stroke="blue" stroke-width="5"></line>
 </svg>
 </body>
 </html>
  ```
fig7
 
  * for text
   ```
   <text x="260" y="25" font-size="20px" fill="orange">Hello World</text>
   ```
fig8
   * for path
   ```
   <svg width="190" height="160" xmlns="http://www.w3.org/2000/svg">
            <path d="M10 80 C 40 10, 65 10, 95 80 S 150 150, 180 80" stroke="black" fill="transparent"/>
   ```
fig9
   
   * 
    

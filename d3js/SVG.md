### SVGs - Scalable Vector Graphics
  *Scalable Vector Graphics (SVG) is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation.
  * draw shapes with computer code
  * Rectangles,circles,ellipses,lines,texts and paths
  * Markup code similar to HTML
  * Small file size , dont lose any quality if resized
  * a jpeg of google logo takes about 23,000 bytes whereas for SVG it takes 310 bytes
  * We can inlude SVGs directly in an HTML file
![fig3](https://user-images.githubusercontent.com/43897511/51080570-fd7fc400-16a3-11e9-908c-426097ec6dc1.PNG)

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
  ![fig4](https://user-images.githubusercontent.com/43897511/51080575-0ec8d080-16a4-11e9-8b52-10a9068243e0.PNG)
  
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
  ![fig5](https://user-images.githubusercontent.com/43897511/51080577-1b4d2900-16a4-11e9-81d1-3ae06c8a7792.PNG) 
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
![fig6](https://user-images.githubusercontent.com/43897511/51080578-256f2780-16a4-11e9-8148-c74d09741bee.PNG)

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
![fig7](https://user-images.githubusercontent.com/43897511/51080581-328c1680-16a4-11e9-82a4-96ae37b76e6a.PNG)
 
  * for text
   ```
   <text x="260" y="25" font-size="20px" fill="orange">Hello World</text>
   ```
![fig8](https://user-images.githubusercontent.com/43897511/51080584-3ddf4200-16a4-11e9-9124-5abcbf5491cf.PNG)

   * for path
   ```
   <svg width="190" height="160" xmlns="http://www.w3.org/2000/svg">
            <path d="M10 80 C 40 10, 65 10, 95 80 S 150 150, 180 80" stroke="black" fill="transparent"/>
   ```
![fig9](https://user-images.githubusercontent.com/43897511/51080586-49326d80-16a4-11e9-85f2-5870311e97f8.PNG)

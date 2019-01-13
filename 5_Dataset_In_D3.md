
### D3 with array 
  * 
  ```
  var dataset = [ 5, 10, 15, 20, 25 ];
  ```
### D3 with csv
  ```
  d3.csv("food.csv", function(data) {
  console.log(data);
  });
  ```
  * console.log() method writes a message to the console.
  * d3.csv() is an asynchronous method, meaning that the rest of your code is executed even while JavaScript is simultaneously waiting for the file to finish downloading into the browser. The callback function is executed whether or not the datafile was loaded successfully. To avoid confusion on this we can include an optional error parameter in the callback fucntion definition. If there is a problem loading the file, then error will be set to the error message returned by the webserver, and data will be undefined.If the file loads successfully and there is no error, then error will be null, and the data array will be populated as expected.Note that error must be the first parameter, and data the second.
  ```
    var dataset;
    d3.csv("food.csv", function(error, data) {
    if (error) { //If error is not null, something went wrong.
    console.log(error); //Log the error.
    } else { //If no error, the file loaded correctly. Yay!
    console.log(data); //Log the data.
    //Include other code to execute after successful file load here
    dataset = data;
    generateVis();
    hideLoadingMsg();
    }
    });
```
### D3 with tsv
```
  d3.tsv("food.csv", function(data) {
  console.log(data);
  });
  ```
### D3 with json
```
  d3.json("food.csv", function(data) {
  console.log(data);
  });
  ```
  


  
   
    
    

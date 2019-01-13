### Binding data
  * We use D3’s ```selection.data()``` method to bind data to DOM elements.
  * Data -> csv,array,tsv,json
  ```
  var dataset = [ 5, 10, 15, 20, 25 ];//simple array dataset
  d3.select("body")//finds the body in the DOM and hands reference to the next step in the chain
    .selectAll("p")//selects all the paragraphs in the DOM. Because none exist yet, this returns an empty
    .data(dataset)//Counts and parses our data values. There are five values in our array called data set, so everything past this point is executed five times, once for each value.
    .enter()//To create new, data-bound elements, you must use enter(). This method looks at the current DOM selection, and then at the data being handed to it. If there are more data values than corresponding DOM elements, then enter() creates a new placeholder element on which you can work your magic. It then hands off a reference to this new placeholder to the next step in the chain.
    .append("p") // Takes the empty placeholder selection created by enter() and appends a p element into the DOM. Hooray! Then it hands off a reference to the element it just created to the next step in the chain.
    .text("New paragraph!");//Takes the reference to the newly created p and inserts a text value.
    
   ```
  * 

### Chaining methods
    * By “chaining” methods together with periods, you can perform several actions
in a single line of code. It can be fast and easy, but it’s important to understand how it
works, to save yourself hours of debugging headaches later.
    * 
    ```
    d3.select("body").append("p").text("New paragraph!");
    ```
    * d3 references the d23 object , so that we can access its methods.
    * .select("body")
      * gives the select() methods a CSS selector as i/p and it will return a reference to
the first element in the DOM that matches. (Use selectAll() when you need more
than one element.)
    * .append("p")
      * append() creates whatever new DOM element you specify and appends it to the
end (but just inside) of whatever selection it’s acting on. In our case, we want to
create a new p within the body
  * .text("New paragraph")
    * text() takes a string and inserts it between the opening and closing tags of the
current selection. Because the previous method passed down a reference to our new
p, this code just inserts the new text between <p> and </p>.
  * ;
    indicates the end of this line of code.
  * The output type of one method has to match the input type expected by the next method in the chain.

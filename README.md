# notes
Exception Handling in the Rest API.
a) Create the custome Exception class that extends  the runtime exception ( just over ride 
the String constructor and call super).
b) Write a controller advice class
  1) In the controller advice class , annotate the method with @ExceptionHandler(Name of the exception class)
  2) the method will return ResponseEntity object. ResponseEntity dot status dot body ( custome java pojo).

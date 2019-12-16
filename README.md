# notes
Exception Handling in the Rest API.
a) Create the custome Exception class that extends  the runtime exception ( just over ride 
the String constructor and call super).
b) Write a controller advice class
  1) In the controller advice class , annotate the method with @ExceptionHandler(Name of the exception class)
  2) the method will return ResponseEntity object. ResponseEntity dot status dot body ( custome java pojo).


Hibernate notes:-
a) The best way to model a one-to-many relationship is to use just @ManyToOne annotation on the child entity.(for U ni directional association).
b) For the bi-directoional assoicaiton , you can add @OneToMany association on the parent class and @ManyToOne annotation on the child side of the relation.The bidirectional mapping has its pros and cons.





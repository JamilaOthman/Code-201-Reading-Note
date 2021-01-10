# Tables
#### When representing information in a table, you need to think
in terms of a grid made up of rows and columns (a bit like a
spreadsheet). In this chapter you will learn how to:
* Use the four key elements for creating tables
* Represent complex data using tables
* Add captions to tables
* The <table> element is used to add tables to a web
page.
* A table is drawn out row by row. Each row is created
with the <tr> element.
* Inside each row there are a number of cells
represented by the <td> element (or <th> if it is a
header).
* You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
* For long tables you can split the table into a <thead>,
<tbody>, and <tfoot>.


# Functions, Methods, and Objects
* Functions allow you to group a set of related
statements together that represent a single task.
* Functions can take parameters (informatiorJ required
to do their job) and may return a value.
* An object is a series of variables and functions that
represent something from the world around you.
* In an object, variables are known as properties of the
object; functions are known as methods of the object.
* Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
* JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
* Arrays and objects can be used to create complex data
sets and both can contain the other.
# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
### Define a constructor and initialize properties
To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an EpicFailVideo object.

##### This is object-oriented programming in JavaScript at its most fundamental level.
##### The new keyword instantiates (i.e. creates) an object.
##### The constructor function initializes properties inside that object using the this variable.
##### The object is stored in a variable for later use.


* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.
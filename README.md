# classes
a simple repo about classes in es6

A class is basically a function but instead of using the famous 'function' keyword to initialize it,one uses the class keyword

The main difference between function declarations and class declarations is that function declarations are hoisted and class declarations are not.One will need to declare a class and access it to avoid throwing an error.

A constructor is used to hold properties and everytime one needs to initialize a class,a constructor method is called 

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Class</h2>

<p>A simple class</p>

<p id="class"></p>

<script>
class Name {
	constructor (name) {
    	this.personname=name;
    }
}
myname = new Name ("dan");

document.getElementById("demo").innerHTML = myname.personname;
</script>

</body>
</html>

ES6 classes make our code safer by guaranteeing that an initialization function will be called, and they make it easier to define a fixed set of functions that operate on that data and maintain valid state.

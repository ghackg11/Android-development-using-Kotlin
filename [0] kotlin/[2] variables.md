Variables in kotlin can be initialised and/or declared in two ways, using ```val``` or ```var```. 

val - immutable  
var - mutable

one can also give the variable a datatype explicitly or let it determine at compile time. 

```
var x = "hello"
var x: String = "hello
```
We prefer val over val wherever possible, as it prevents errors, and code is easier to parallelise with immutable variables

**Equality checks in variables**

== compares values
=== compares reference

when checking reference, it is checked the two sides pointing to same object and when comparing values, only values of the objects on two sides are compared. 

Note: 
```
fun main(){
    val x1 = "hello"
    var x2 = "hell"+"o"
    println(x1==x2)
    println(x1===x2)
}
```
The output will be:
```
true
true
```

as both the strings are stored in string pool in same location as they have same value, one value is stored only once in the string pool.
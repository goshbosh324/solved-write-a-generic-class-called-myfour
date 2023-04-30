Download Link: https://assignmentchef.com/product/solved-write-a-generic-class-called-myfour
<br>
Write a generic class called “MyFour”. It should use a type parameterof “T”. It should have four fields, item1, item2, item3, item4, all oftype T. Its constructor receives values for setting all four items. Itshould have a method “allEqual” that returns true if all four items areequal according to their “equals” method. It should have a method called“shiftLeft” that shifts all items up one position, and puts the firstitem’s value into the last item.

For example, if list has 1, 2, 3, 4, then after shiftLeft, it is 2, 3, 4, 1.

It should have a “toString” method that returns a String of the itemsin this format: (item1, item2, item3, item4).

Finally, add a “main” method. First it should create a MyFour objectof type String, passing it four identical strings. Print the object, thencall and print the results of “allEqual”. Next, create an object of fourdifferent Integers. Again print the object and print the results of“allEqual”. After that, shift the items left using your method, andprint them again.
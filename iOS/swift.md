open XCode Playground to practice Swift language
to output anything to the console use **print()** statement
common data types in Swift - *string*, *int*, *double*, *bool* and *array*
variable declaration- **var name:datatype = value**;  (type declaration lets compiler know how much memory to set aside for the variable) variables can't be reassigned value of a different type
type inference makes compiler automatically deduce the data type of expression, we don't need to explicitly mention it
a constant, declared using *let* keyword cannot be reassigned any value
String Interpolation- "I am \(var_age) years old"
function declaration- **func name( param:datatype ) -> datatype{ return value }**
functions can pass arguments using variable names, labels or just values
**Int.random(in: start...end)** method is used to generate a random number
**...** is known as a Closed Range Operator ie first and last units are included, eg. 1985...1997
Switch statements can have multiple values in a case separated by comma
Use **where** keyword to check condition against given variable in a switch statement
FOR-IN loop iterates a variable over a range/string/array
use *stride()* function in a for-in loop to change how it iterates
use underscore: __ in a for-in loop if variable is not required
arrays only store data of the same type
array initialization- var array_name = [type]() or var array_name:[type] = [val1, val2, val3]
*array_name.count* gives us the length of an array
to add a single item to an array use **.append()** method, to add multiple items do arr_name += [val1, val2..]
use *insert(val, at:index)* or *remove(at:index)* to add/delete an item at a particular index of an array
a **set** is similar to an array except they're unordered and only contain unique elements
sets can be initialised as- var set_name = Set<type>(), or var set_name: Set = [val1, val2..]
use *insert(item)* to add element to a set, *.count*, *.isEmpty* methods to check number of items in a set and *.remove(value)* or *removeAll* to delete an item or everything from the set
*.contains* checks if a given value is present in a set or not
*set1.intersection(set2)* creates a new set using common values between both, while *.union* combines both sets (or more) into one set with unique elements
*.symmetricDifference* method can be used to find elements exclusive to both sets
*.subtracting* method take values only present in set 1 and removes values common in both sets
Dictionary is a collection of unordered data represented by key-value pairs where the keys are unique and pairs are of same datatype
to add a new key-value pair type *dictionary_name[key] = value*
to change any value- *dictionary_name[key] = new_value* or using .updateValue method
to remove a key-value pair, set it to *nil* or use *.removeValue* method, to empty the dictionary use *.removeAll* method
*.isEmpty* and *.count* methods work on all- arrays, sets, dictionaries
there are two ways of getting an **optional** value from a dictionary- 
*if let var_name = dict_name[key] { // runs if optional value is not nil }* or
*var var_name = dict_name[key]**!*** if we're sure the value exists
    scope of if-let variable is only inside its block
to loop through a dictionary we use a **Tuple**-  *for (keyHolder, valueHolder) in dict_name { // body }*
a Tuple can be assigned to a variable where its individual values can be accessed using dot notation
use *.keys* and *.values* methods to get a list of key/values of dictionary
Function definition:  **func functionName() -> returnType { }**

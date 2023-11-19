## Hello World
- open XCode Playground to practice Swift language
- to output anything to the console use **print()** statement
- common data types in Swift - *string*, *int*, *double*, *bool* and *array*

## Variables
- variable declaration → `var name:datatype = value`  (type declaration lets compiler know how much memory to set aside for the variable) variables can't be reassigned value of a different type
- type inference makes compiler automatically deduce the data type of expression, we don't need to explicitly mention it
- a constant, declared using **let** keyword cannot be reassigned any value
- String Interpolation → `"I am \(var_age) years old"`

## Conditionals & Logic
- `Int.random(in: start...end)` method is used to generate a random number
> `...` is known as a Closed Range Operator ie first and last units are included, eg. 1985...1997
- Switch statements can have multiple values in a case separated by comma
- use **where** keyword to check condition against given variable in a switch statement

## Loops
- FOR-IN loop iterates a variable over a range/string/array
- use **stride()** function in a for-in loop to change how it iterates
- use underscore `__` in a for-in loop if variable is not required

## Arrays
- arrays only store data of the same type
- array initialization → `var array_name = [type]()` or `var array_name:[type] = [val1, val2, val3]`
- **array_name.count** gives us the length of an array
- to add a single item to an array use **.append()** method, to add multiple items do **arr_name += [val1, val2..]**
- use *insert(val, at:index)* or *remove(at:index)* to add/delete an item at a particular index of an array

## Sets
- a **set** is similar to an array except they're unordered and only contain unique elements
- sets can be initialised as → `var set_name = Set<type>()` or `var set_name: Set = [val1, val2..]`
- use **insert(item)** to add element to a set, *.count*, *.isEmpty* methods to check number of items in a set and *.remove(value)* or *removeAll* to delete an item or everything from the set
- *.contains* checks if a given value is present in a set or not
- *set1.intersection(set2)* creates a new set using common values between both, while *.union* combines both sets (or more) into one set with unique elements
- *.symmetricDifference* method can be used to find elements exclusive to both sets
- *.subtracting* method take values only present in set 1 and removes values common in both sets

## Dictionary
- Dictionary is a collection of unordered data represented by key-value pairs where the keys are unique and pairs are of same datatype
- to add a new key-value pair type `dictionary_name[key] = value`
- to change any value → `dictionary_name[key] = new_value` or using *.updateValue* method
- to remove a key-value pair, set it to *nil* or use *.removeValue* method, to empty the dictionary use *.removeAll* method
- *.isEmpty* and *.count* methods work on all- arrays, sets, dictionaries
- there are two ways of getting an **optional** value from a dictionary →
  - `if let var_name = dict_name[key] { // runs if optional value is not nil }` or
  - `var var_name = dict_name[key]**!**` // if we're sure the value exists
> scope of if-let variable is only inside its block
- to loop through a dictionary we use a **Tuple** → `for (keyHolder, valueHolder) in dict_name { // body }`
- a Tuple can be assigned to a variable where its individual values can be accessed using dot notation
- use *.keys* and *.values* methods to get a list of keys/values of dictionary

## Functions
- function declaration → `func name( param:datatype ) -> datatype{ return value }`
- functions can pass arguments using variable names, labels or just values
- functions can have **argument labels** which can be used when calling the function, if argument label is replaced with an underscore only argument value needs to be provided
- a function can return multiple values via an array (for same value types) or tuple (for multiple value types) and accessed using dot notation
- using **implicit return** we can omit the return keyword if the function has only one expression
- functions can have **default parameters** so it won't be mandatory to pass arguments when calling it
- functions can also accept a **variadic parameter** which can be interpreted as an array in the function block, eg. `func func_name (param_name: param_type...) {}`
- an **inout** parameter has the power to change the value of the original arguments. Add an '&' symbol before the argument value when calling the function

~## Structures~
- Structures are blueprints which contain properties and methods → *struct **N**ame { }*
- we can create instances of structures and assign them to variables → `var var_name = struct_name()`
- we can access/assign property values of these instances using dot notation
- Methods are functions, specific to an instance or type
- **init()** method is used to customise an instance of a struct, it doesn't need a func keyword and uses *self* (similar to 'this') keyword to refer itself

~## Classes~

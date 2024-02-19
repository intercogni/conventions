# Naming
This document outlines all the naming conventions to be followed.

## Sets
Sets are defined as an entity that is capable to store information and or process.

Here, a term called `set level` is used to differentiate the types of sets. 

A set with a higher `set level` means that it is a set that consists of **strictly multiple** different types of sets with a lower `set level` than itself.
> Notice that in this case, an array of a set with a given `set level` of `n` has a `set level` of `n`.

> If a set contains multiple sets of different `set levels`, the `set level` of that set is one above the highest `set level` that it contains.

### Set Level 0a: Primitive Data Types

>Use `snake_case` to define `level 0a sets`. 

Sets with a `set level` of `0a` contains a data type that cannot be broken down into user-defined components and or methods. 

>notice that in this case, even though methods exist for primitive data types in certain programming languages such as `python` or `js`, they are not user defined. As such, this rule still follows.

In most cases, this includes `primitive data types`, which can only be broken down into bits (or in the case of strings, into bytes of characters).

>`level 0a sets` are defined by their nature to be `unclassable`, this means that the information inside `level 0a sets` cannot be assigned a custom identifier or name by the programmer.

Even though the call to the set may be defined via a function, as long as it resulted with the set being assigned a `level 0a set`, follow the convention.

```python
my_python_var = 3
```
```js
const my_js_str = useRef('Intercogni')
```
```cpp
std::vector<std::string> my_cpp_vec = {"hello", "world"};
```

### Set Level 0b: Functions
> use `camelCase` to define `level 0b sets`.

Sets with a `set level` of `0b` contains a process/execution that cannot be broken down into user-defined components and or methods.

>notice that in this case, even though methods exist for non-class functions in certain programming languages such as `python` or `js`, they are not user defined. As such, this rule still follows.

Sets with a `set level` of `0b` includes non-class functions.
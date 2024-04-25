2023.05.09

### Declare variable
1. variableType variableName{ value }
	if value is not compateble with type, it throws a compiler error.
	if we don't set a value, the variable is set to "0".
2. variableType variableName( value )
	if variableType is int and valueType is double, it cuts of the decimal digids.
	if value is not compateble with type, it throws a runtime error.
3. variableType variableName = value


### Basic
#### 1. static_cast\<variableType\>(value)
	can turn a char into a value (based on the [[askii table]] ) and vice versa
### Pointers
- variableType * variableName {&variable};
- or variableType * variableName { nullptr };
-                                                { new variableType {value}}
variableName is a [[Memory adress]] 
\*variableName is a Value 

to remove a pointer from memory;
	delete variableName;
	variableName = nullptr;

DON'T DO!!!
variableType * variableName { };
variableType * variableName;
### Error prevention
try {
	/\*code\*/
}
catch (std::exeption& ex){
	std::cout << ex.what() << std::endl;
}

_or_

Normaly the following code would go out of bounds, because the computer would run out of memory. But with the  "std::nothrow" we can prevent this.

int* name = new(std::nothrow) int\[100000000000\]
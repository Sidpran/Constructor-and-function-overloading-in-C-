##Constructor-and-function-overloading-in-C-

##AIM
Illustrate constructor overloading by providing multiple ways to initialize an object: default initialization, parameter-based initialization, and copy initialization.

Software used: MinGW compiler, Visual Studio Code, online C++ compiler.

## Program Constructor overloading
Explanation and theory: The class fetch defines three constructors that differ by their parameter lists. The default constructor initializes a and b to preset values, the parameterized constructor assigns caller-provided values, and the copy constructor clones the fields from an existing object. The display() method prints the current state, and main creates objects using all three forms to demonstrate how the compiler selects the appropriate constructor based on the arguments supplied.

Algorithm:
- Start.
- Define class fetch with public members a and b.
- Implement a default constructor that sets a = 10 and b = 20.
- Implement a parameterized constructor that assigns a = m and b = n.
- Implement a copy constructor that copies a and b from another fetch object.
- Implement display() to print a and b.
- In main: 
  - Create f1 via default construction.
  - Create f2 via parameterized construction.
  - Create f3 via copy construction from f1.
  - Call display() on f1, f2, and f3 to show their values.
- End.

## Conclusion
This example demonstrates that multiple constructors can coexist within a single class as long as they differ by parameter lists. The appropriate constructor is invoked automatically based on how the object is created, providing flexibility to initialize objects with defaults, caller-specified values, or by copying an existing instance.

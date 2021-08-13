## How to Write Your First Program in C++

Many applications are running for specific tasks on computer every day. You might be curious about how to write such a program. One of popular programming lanugages is C++. Programs written in C++ language is generally faster and smaller than programs in the other languages.

To start writing a program in C++, you need two things.
- A text editor, like Notepad++, to write C++ source code
- A compiler, like Clang, GCC, VC to translate the C++ code into a machine language that the computer can understand.

<img src="Compiler.jpg" alt="Compiling Process" style="float: left; height=30; width=80;" />



### First Run

Write the following code and run compiler.
```C++
#include <iostream>

void main() {
  std::cout << "Hello world!";
}
```
And then, run the compiled program. Then, the output should look like this.
<img src="HelloWorld.PNG" alt="Hello World" style="float: left; height=20; width=80;" />

Yay! You have written and run your first program in C++.

### A Program Breakdown
1. To display the output, you can take advantage of the existing libraries. `iostream` is the library that supports input and output using console.
```C++
#include <iostream>
```
2. The main program file must include a function called `main()`. This is where execution of the program begins. From here, you should be calling functions, instantiating classes, etc. Other files of your application as well as libraries can be included into this file.
```C++
void main() {
}
```
3. You can add your business logic to the body of `main()` function. Learn the syntax, Object-Oriented programming concept, data structure, algorithm designs such as linked lists, priority queues, etc. In the example, "Hello world!" is displayed using `iostream` library. 
```C++
  std::cout << "Hello world!";
```

### In Closing
C++ is not an easy language to program in, but doing so teaches you the fundamentals that extend to all programming languages.

### References
1. [Writing Standard Code](https://www.wikihow.com/Write-Standard-Code-in-C%2B%2B)
2. [C++ Getting Started](https://www.w3schools.com/cpp/cpp_getstarted.asp)
3. [Program Structure](https://www.cplusplus.com/doc/tutorial/program_structure/)

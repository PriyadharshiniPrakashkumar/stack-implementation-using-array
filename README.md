# Stack Operations Program

## Overview

This program demonstrates the implementation of a basic stack data structure in C++ using a predefined maximum size. The stack operations supported are:

1. **Push** - Add an element to the top of the stack.
2. **Pop** - Remove an element from the top of the stack.
3. **Display** - Display all elements in the stack.
4. **Exit** - Exit the program.

The program uses a menu-driven interface to allow users to interact with the stack.

---

## Features

1. **Dynamic Interaction**: Users can interactively perform stack operations using a menu-driven interface.
2. **Error Handling**: The program handles stack overflow and underflow conditions gracefully by displaying appropriate messages.
3. **Compact Design**: The implementation uses a struct to encapsulate stack operations and state.

---

## Files

- **main.cpp**: Contains the source code for the stack implementation.

---

## Usage Instructions

1. Compile the program using a C++ compiler:

   ```bash
   g++ -o stack_program main.cpp
   ```

2. Run the executable:

   ```bash
   ./stack_program
   ```

3. Use the menu to perform operations:

   - **1**: Push an element onto the stack.
   - **2**: Pop an element from the stack.
   - **3**: Display all elements of the stack.
   - **4**: Exit the program.

---

## Example Execution

### Input:

```
Stack Operations Menu:
1. Push
2. Pop
3. Display
4. Exit
Enter your choice: 1
Enter the value to push: 10

Stack Operations Menu:
1. Push
2. Pop
3. Display
4. Exit
Enter your choice: 3
```

### Output:

```
Pushed 10 onto the stack.
Stack elements: 10
```

---

## Limitations

1. **Fixed Size**: The stack has a fixed maximum size defined by `MAX_SIZE`. This can be changed by modifying the `#define MAX_SIZE` line in the code.
2. **Integer Data Only**: The stack is designed to store integers. To support other data types, modifications are needed.

---

## Enhancements

1. Implement dynamic memory allocation for stack size.
2. Support for generic data types using templates.
3. Add a feature to view the top element without popping it.

---



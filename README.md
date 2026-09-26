# Object-Oriented Programming with C++ (ADPC303)

Practical code repository for **Object-Oriented Programming with C++**, structured unit-wise with compilable C++ implementations, scenario-based programs, and key OOP concept demonstrations.

---

## Student Details

| Attribute | Details |
|:---|:---|
| **Student Name** | Owais Akil Deshmukh |
| **PRN** | AD2611 |
| **Class & Division** | S.Y. B.Tech (AI & DS) — Div SY-F |
| **Course** | Object-Oriented Programming with C++ (ADPC303) |
| **Semester** | Semester III |
| **Language Standard** | C++17 or later |

---

## Repository Structure

```text
CPP-unit-2-program/
├── README.md
├── unit1/
│   ├── Program_01/main.cpp   # Basic Data Types
│   ├── Program_02/main.cpp   # If-Else Selection
│   ├── Program_03/main.cpp   # Loop and Array
│   ├── Program_04/main.cpp   # Functions & Prototyping
│   ├── Program_05/main.cpp   # Class and Object
│   ├── Program_06/main.cpp   # Constructor and Destructor
│   ├── Program_07/main.cpp   # Static Member
│   └── Program_08/main.cpp   # Inline and Friend Function
├── unit2/
│   ├── Program_01/main.cpp   # Basic Single Inheritance
│   ├── Program_02/main.cpp   # Protected Member Access
│   ├── Program_03/main.cpp   # Public vs Private Inheritance
│   ├── Program_04/main.cpp   # Multilevel Inheritance
│   ├── Program_05/main.cpp   # Hierarchical Inheritance
│   ├── Program_06/main.cpp   # Multiple Inheritance
│   ├── Program_07/main.cpp   # Resolving Multiple-Inheritance Ambiguity
│   ├── Program_08/main.cpp   # Constructor and Destructor Order
│   ├── Program_09/main.cpp   # Parameterized Base Constructor
│   ├── Program_10/main.cpp   # Function Overriding
│   ├── Program_11/main.cpp   # Abstract Class
│   ├── Program_12/main.cpp   # Virtual Base Class (Diamond Inheritance)
│   ├── Program_13/main.cpp   # Friend Class
│   ├── Program_14/main.cpp   # Nested Class
│   ├── Program_15/main.cpp   # Mini-Project: Vehicle Rental System
│   └── Program_16/main.cpp   # Mini-Project: Employee Payroll System
└── unit3/
    ├── Program_01/main.cpp   # Function Overloading
    ├── Program_02/main.cpp   # Area Calculator
    ├── Program_03/main.cpp   # Unary Minus Operator Overloading
    ├── Program_04/main.cpp   # Prefix and Postfix Increment Overloading
    ├── Program_05/main.cpp   # Complex Number Addition (+)
    ├── Program_06/main.cpp   # Distance Comparison (>)
    ├── Program_07/main.cpp   # Friend / Non-Member Operator Overloading
    ├── Program_08/main.cpp   # Base Pointer without Virtual Function
    ├── Program_09/main.cpp   # Base Pointer with Virtual Function
    ├── Program_10/main.cpp   # Base Reference with Virtual Function
    ├── Program_11/main.cpp   # Abstract Class and Pure Virtual Function
    ├── Program_12/main.cpp   # Collection of Polymorphic Shape Pointers
    ├── Program_13/main.cpp   # Virtual Destructor
    ├── Program_14/main.cpp   # Object Slicing Demonstration
    ├── Program_15/main.cpp   # Payment Processing System
    └── Program_16/main.cpp   # Employee Payroll Mini-Project
```

---

## How to Compile & Run

### Linux / macOS
```bash
g++ -std=c++17 main.cpp -o program
./program
```

### Windows (using MinGW)
```cmd
g++ -std=c++17 main.cpp -o program.exe
program.exe
```

---

## Unit I: Fundamentals & Object-Oriented Basics

### List of Programs

| # | Title | Folder | Main Concept | Description |
|:---:|:---|:---:|:---|:---|
| 1 | Basic Data Types | [`unit1/Program_01`](./unit1/Program_01) | Fundamental data types & I/O | Demonstrates basic data types (`int`, `char`, `float`) to store roll number, grade, and fee amount using `cout`. |
| 2 | If-Else Selection | [`unit1/Program_02`](./unit1/Program_02) | Conditional branching | Evaluates student pass/fail condition using `if-else` selection control structure based on marks threshold. |
| 3 | Loop and Array | [`unit1/Program_03`](./unit1/Program_03) | Arrays & iterative loops | Stores test scores in an integer array and iterates using a `for` loop to print each student's score. |
| 4 | Functions | [`unit1/Program_04`](./unit1/Program_04) | Modular programming & prototyping | Implements a modular `add()` function with forward declaration (prototype), arguments, and return value. |
| 5 | Class and Object | [`unit1/Program_05`](./unit1/Program_05) | Encapsulation & object creation | Defines a `Student` class blueprint with member variables and a member function `show()`, instantiated in `main()`. |
| 6 | Constructor and Destructor | [`unit1/Program_06`](./unit1/Program_06) | Object lifecycle management | Demonstrates automatic object initialization upon instantiation and automatic cleanup upon scope exit using constructor and destructor. |
| 7 | Static Member | [`unit1/Program_07`](./unit1/Program_07) | Class-level shared data | Uses a `static int count` shared across all `Student` instances to track the total number of objects created. |
| 8 | Inline and Friend Function | [`unit1/Program_08`](./unit1/Program_08) | Inline optimization & friend access | Accesses private data using an efficient `inline` getter method and grants external access via a `friend` function. |

---

## Unit II: Inheritance

### List of Programs

| # | Title | Folder | Main Concept | Description |
|:---:|:---|:---:|:---|:---|
| 1 | Basic Single Inheritance | [`unit2/Program_01`](./unit2/Program_01) | Base and derived classes | Demonstrates single inheritance where derived `Student` inherits accessible members from base `Person` class ("is-a" relationship). |
| 2 | Protected Member Access | [`unit2/Program_02`](./unit2/Program_02) | `protected` access specifier | Demonstrates accessing protected base class members inside derived `Developer` class while preserving encapsulation from outside code. |
| 3 | Public vs Private Inheritance | [`unit2/Program_03`](./unit2/Program_03) | Inheritance access modes | Demonstrates accessibility differences showing public base members remain public in `PublicDerived` but become private in `PrivateDerived`. |
| 4 | Multilevel Inheritance | [`unit2/Program_04`](./unit2/Program_04) | Three-level hierarchy | Implements a three-tier inheritance chain (`Person` &rarr; `Employee` &rarr; `Manager`) passing and displaying data across levels. |
| 5 | Hierarchical Inheritance | [`unit2/Program_05`](./unit2/Program_05) | One base, multiple derived classes | Derives multiple specialized classes (`Car` and `Bike`) from a common base class `Vehicle`. |
| 6 | Multiple Inheritance | [`unit2/Program_06`](./unit2/Program_06) | Two base classes | Implements `Student` inheriting from both `Academic` and `Sports` base classes to compute combined total marks. |
| 7 | Resolving Multiple-Inheritance Ambiguity | [`unit2/Program_07`](./unit2/Program_07) | Scope-resolution operator | Resolves function naming collisions in multiple inheritance using the scope-resolution operator (`Base::function`). |
| 8 | Constructor and Destructor Order | [`unit2/Program_08`](./unit2/Program_08) | Object lifecycle | Traces constructor and destructor call order: base &rarr; derived during creation, and derived &rarr; base during destruction. |
| 9 | Parameterized Base Constructor | [`unit2/Program_09`](./unit2/Program_09) | Initializer list | Passes arguments from derived `Student` constructor to parameterized base `Person` constructor using member initializer list. |
| 10 | Function Overriding | [`unit2/Program_10`](./unit2/Program_10) | `virtual` and `override` | Overrides the base `move()` virtual function in `Car` and `Boat` derived classes with the `override` keyword. |
| 11 | Abstract Class | [`unit2/Program_11`](./unit2/Program_11) | Pure virtual function | Defines an abstract base class `Shape` with pure virtual function `area() = 0`, implemented by `Rectangle` and `Circle`. |
| 12 | Virtual Base Class | [`unit2/Program_12`](./unit2/Program_12) | Diamond inheritance | Solves duplicate-base ambiguity in diamond inheritance (`Person` inherited via `Student` and `Employee`) using virtual inheritance. |
| 13 | Friend Class | [`unit2/Program_13`](./unit2/Program_13) | Special access permission | Grants `Auditor` friend class complete access to inspect private balance data of the `Account` class. |
| 14 | Nested Class | [`unit2/Program_14`](./unit2/Program_14) | Class inside another class | Defines and instantiates an inner `Department` class nested within the outer `University` class scope. |
| 15 | Vehicle Rental System (Mini-Project) | [`unit2/Program_15`](./unit2/Program_15) | Integrated inheritance | Implements a vehicle rental system computing daily rental costs for cars and bikes using polymorphic base methods. |
| 16 | Employee Payroll System (Mini-Project) | [`unit2/Program_16`](./unit2/Program_16) | Abstract base & overriding | Develops an employee payroll application calculating salaries for `PermanentEmployee` and `ContractEmployee` through abstract base pointers. |

---

## Unit III: Polymorphism

### List of Programs

| # | Title | Folder | Main Concept | Description |
|:---:|:---|:---:|:---|:---|
| 1 | Function Overloading | [`unit3/Program_01`](./unit3/Program_01) | Compile-time polymorphism | Three `add()` overloads demonstrate how the compiler statically resolves function calls based on parameter types and counts. |
| 2 | Area Calculator | [`unit3/Program_02`](./unit3/Program_02) | Overloading with varied parameters | Three `calculateArea()` overloads compute areas for square, rectangle, and circle based on arguments provided. |
| 3 | Unary Minus Operator | [`unit3/Program_03`](./unit3/Program_03) | Unary operator overloading | The `Number` class overloads unary `-` so that `-number` returns a new object with the negated value. |
| 4 | Prefix & Postfix Increment | [`unit3/Program_04`](./unit3/Program_04) | Unary operator overloading | The `Counter` class implements both `++counter` (prefix) and `counter++` (postfix, distinguished by dummy `int`). |
| 5 | Complex Number Addition | [`unit3/Program_05`](./unit3/Program_05) | Binary `+` operator overloading | Overloads binary `+` as a member function to add real and imaginary components of two complex numbers directly. |
| 6 | Distance Comparison | [`unit3/Program_06`](./unit3/Program_06) | Relational operator overloading | The `Distance` class overloads `>` to enable natural relational comparison between two distance objects. |
| 7 | Friend / Non-Member Operator | [`unit3/Program_07`](./unit3/Program_07) | Operator overloading using friend function | Overloads binary `+` as a friend function to allow integer as the left operand (`10 + complexNumber`). |
| 8 | Base Pointer without Virtual Function | [`unit3/Program_08`](./unit3/Program_08) | Static binding demonstration | Demonstrates compile-time early binding where base pointer invokes base version despite pointing to derived object. |
| 9 | Base Pointer with Virtual Function | [`unit3/Program_09`](./unit3/Program_09) | Run-time polymorphism | Implements run-time dynamic binding via virtual functions using base pointer `Animal*` pointing to `Dog` and `Cat`. |
| 10 | Base Reference with Virtual Function | [`unit3/Program_10`](./unit3/Program_10) | Dynamic binding through references | Demonstrates dynamic dispatch by passing objects by base reference `const Shape&` to avoid copying and object slicing. |
| 11 | Abstract Class & Pure Virtual Function | [`unit3/Program_11`](./unit3/Program_11) | Pure virtual function | Defines an abstract `Shape` base class with pure virtual `area() = 0` which prevents instantiation and enforces override. |
| 12 | Collection of Polymorphic Shape Pointers | [`unit3/Program_12`](./unit3/Program_12) | Polymorphic processing | Stores heterogeneous derived shapes in `std::vector<std::unique_ptr<Shape>>` and computes area dynamically in a loop. |
| 13 | Virtual Destructor | [`unit3/Program_13`](./unit3/Program_13) | Safe deletion through base pointer | Ensures safe object cleanup by declaring a virtual destructor in base class, ensuring derived destructor executes upon `delete`. |
| 14 | Object Slicing Demonstration | [`unit3/Program_14`](./unit3/Program_14) | Why references/pointers are needed | Compares pass-by-value vs pass-by-reference to demonstrate how passing by value slices derived class attributes. |
| 15 | Payment Processing System | [`unit3/Program_15`](./unit3/Program_15) | Abstract interface & real-world example | Implements a real-world polymorphic payment processor supporting `CardPayment`, `UpiPayment`, and `NetBankingPayment`. |
| 16 | Employee Payroll Mini-Project | [`unit3/Program_16`](./unit3/Program_16) | Integrated polymorphism application | Builds a complete salary calculation system using abstract `Employee` base class and polymorphic pay slip generator. |
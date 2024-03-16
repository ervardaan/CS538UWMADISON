# PROGRAMMING LANGUAGES HISTORY AND DEVELOPMENT-BASIC STRUCTURE AND DEVELOPMENT OF PLs

## Scheme

- A modern variant of Lisp.
- A Functional Language: Functions are
“first class” data values.
- Dynamically Typed: A variable’s type
may change during execution; no
type declarations are needed.
- All memory allocation and
deallocation is automatic.
- Primary data structures, lists and
numbers, are unlimited in size & may
grow without bound.
- Continuations provide a novel way to
suspend and “re-execute”
computations

## ML (“Meta Language”)

- Strong, compile-time type checking.
- Types are determined by inference
rather than declaration.
- Polymorphic (one function
declaration can be used with many
different types).
- Pattern-directed programming (you
define patterns that are automatically
matched during a call).
- Typed exceptions are provided.
- Abstract data types, with
constructors, are included

## Prolog (Programming in Logic)

- Programs are Facts and Rules.
- Programmers are concerned with
definition, not execution.
Execution order is automatically
determined.
## Pizza

- Extends a popular Object-oriented
language, Java, to include
- Parametric polymorphism (similar to
C++’s templates)
- First-class functional objects
- Algebraic data types, including
patterns.

## Python

- A simple, efficient scripting language
that quickly build new programs out
of existing applications and libraries.
- Cleanly includes objects.
Scales nicely into larger applications.

### 1)programs were written in absolute machine code—a sequence of bits that encode machine instructions

### 2) Symbolic Assemblers

- Allow use of symbols for operation
codes and labels.

### 3) Fortran (Formula Translator)-1950

### 4) Cobol (Common Business Oriented Language)-1960

### 5) Algol 60 (Algorithmic Language)-1960

### 6) Lisp (List Processing Language)-1960

### 7) Simula 67 (Simulation Algol)-1967

### 8) C-1970 and C++ - 1980 mid

### 9) Java-1990 late

## programming paradigms

- Procedural Languages
    - Most of the widely-known and
widely-used programming languages
(C, Fortran, Pascal, Ada, etc.) are
procedural in nature.
  - Programs execute statement by
statement, reading and modifying a
shared memory.
  - This programming style closely
models conventional sequential
processors linked to a RAM

- Functional Languages
      - Lisp, Scheme and ML are functional
in nature.
    - Programs are expressions to be
evaluated.
    - Language design aims to minimize
side-effects, including assignment.
    - Alternative evaluation mechanisms
are possible, including
Lazy (Demand Driven) AND 
Eager (Data Driven or Speculative)

- Object-Oriented Languages
      - C++, Java, Smalltalk, Pizza and
Python are object-oriented.
    - Data and functions are encapsulated
into Objects.
    - Objects are active, have persistent
state, and uniform interfaces
(messages or methods).
    - Notions of inheritance and common
interfaces are central.
    - All objects that provide the same
interface can be treated uniformly. In
Java you can print any object that
provides the toString method. You
can iterate through the elements of
any Java object that implements the
Enumeration interface

- Logic Programming Languages
      - Prolog notes that most programming
languages address both the logic of a
program (what is to be done) and the
control flow of a program (how to do
what you want).
    - A logic programming language, like
Prolog, lets programmers focus on a
program’s logic without concern for
control issue.
    - These languages have no real control
structures, and little notion of “flow
of control.”
    - What results are programs that are
unusually succinct and focused

- Block Structured Languages
      - Include Algol 60, Pascal, C and Java.
      - Identifiers may have a non-global scope.
Declarations may be local to a class,
subprogram or block.
      - Scopes may nest, with declarations
propagating to inner (contained) scopes.
      - The lexically nearest declaration of an
identifier is bound to uses of that
identifier

- Dynamic Scoping
      - An alternative to static scoping is
dynamic scoping, which was used in
early Lisp dialects (but not in Scheme,
which is statically scoped).
    - Under dynamic scoping, identifiers
are bound to the dynamically closest
declaration of the identifier. Thus if
an identifier is not locally declared,
the call chain (sequence of callers) is
examined to find a matching
declaration

- Virtual Functions
    - A function declared within a class, C,
may be redeclared within a class
derived from C. Moreover, for
uniformity of redeclaration, it is
important that all calls, including
those in methods within C, use the
new declaration.

- SCOPE VS LIFETIME
- STRUCTS VS BLOCKS
- CLASSES
      - TYPE EQUVALENCE IN CLASSES
      - SUBTYPES
- PARAMETRIC POLYMORPHISM
      - We can create distinct subclasses
based on the values passed to
constructors. But sometimes we want
to create subclasses based on distinct
types, and types can’t be passed as
parameters. (Types are not values, but
rather a property of values.)
    - We see this problem in Java, which
tries to create general purpose data
structures by basing them on the
class Object. Since any object can be
assigned to Object (all classes must
be a subclass of Object), this works—
at least partially
    - Using this mechanism, we
can use type parameters to build a
“custom version” of a class from a
general purpose class.
C++ allows this using its template
mechanism. Pizza, an extension of
Java, also allows type parameters.
In both languages, type parameters
are enclosed in “angle brackets” (e.g.,
LinkedList<T> passes T, a type, to
the LinkedList class)
- Overloading and Ad-hoc
Polymorphism



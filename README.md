# Apress Source Code

This repository accompanies [*Beginning C++23*](https://link.springer.com/book/10.1007/978-1-4842-9343-0) by Ivor Horton and Peter Van Weert (Apress, 2023).

<img src="BeginningCpp23.jpg" width=250 alt="Cover image"/>

Download the files as a zip using the green button, or clone the repository to your machine using [Git](https://docs.github.com/en/get-started/quickstart). 

## Compiling

[Compiling.md](Compiling.md) contains a guide on how to compile source code for the book.
Our [workarounds](./Workarounds) section may assist you in working around any features your compiler is lacking.

> [!NOTE]
* Required compiler version: `g++ 15.1.0`.
* These are the compilation steps required to compile 1 `.cpp` source file; I might include a `Note` about using `CMake` later.
* Compiling the 1st program: `Ex1_01.cpp`:
* Build `std module interface`:
* `$ g++ -std=c++23 -fmodules -fsearch-include-path bits/std.cc -c -o std.o`
* Compile `main.cpp`:
* `$ g++ -std=c++23 -fmodules main.cpp -o main`
* Run executable:
* `$ ./main`
* Output:
* `The answer to life, the universe, and everything is 42.`

## Contributions

See the file [Contributing.md](Contributing.md) for more information on how you can contribute to this repository.


## Errata

See [Errata.md](Errata.md) for a list of known mistakes in the book.
Any additional errata may be submitted either through the [Apress arrata submission form](https://www.apress.com/gp/services/errata),
or as an Issues or Pull request on this Github repository.


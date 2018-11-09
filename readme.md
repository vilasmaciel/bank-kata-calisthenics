# Bank Kata

Your bank is tired of its mainframe COBOL accounting software and they hired both of you for a greenfield project in your favorite programming language!

Your task is to show them that your TDD-full and your new-age programming language can cope with good ole’ COBOL!

## Requirements

Write a class `Account` that offers the following methods:

* `void deposit(int)`
* `void withdraw(int)`
* `void printStatements()`

## The Rules

* One level of indentation per method
* Don’t use the ELSE keyword
* Wrap all primitives and Strings
* First class collections
* One dot per line (Follow de [Demeter Law)](https://en.wikipedia.org/wiki/Law_of_Demeter)
* Don’t abbreviate
* Keep all entities small (50 lines)
* No classes with more than two instance variables
* No getters/setters/properties

#### For more information:  [Object Calisthenics PDF](http://www.cs.helsinki.fi/u/luontola/tdd-2009/ext/ObjectCalisthenics.pdf)

## Example

An example statement would be:

```bash
Date        Amount  Balance
24.12.2015   +500      500
23.8.2016    -100      400
```

All credits to [Sandro Mancuso](https://github.com/sandromancuso/Bank-kata)

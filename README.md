# Clojure Brainfuck Interpreter
A Brainfuck interpreter in Clojure

See https://en.wikipedia.org/wiki/Brainfuck

Brainfuck is an esoteric programming language created in 1993 by Urban Müller, and is notable for its extreme minimalism.

The language consists of only eight simple commands and an instruction pointer. While it is fully Turing complete, it is not intended for practical use, but to challenge and amuse programmers. Brainfuck simply requires one to break commands into microscopic steps.

The language's name is a reference to the slang term brainfuck, which refers to things so complicated or unusual that they exceed the limits of one's understanding. 

Read https://en.wikipedia.org/wiki/Brainfuck#Language_design for details of how Brainfuck operates

## Running
Once your program is implemented, you can run it by executing `lein run [-- source ...]` from the current directory.

For example
```
$ lein run
```
without any sources provided will just run some example programs defined in -main

```
$ lein run -- resources/beer.bf
```
will run the 99 bottles of beer program found in resources/beer.bf

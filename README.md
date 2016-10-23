My Befunge-93 programs
======================

This is an unsorted collection of some befunge-93 programs I have written.

Some files contain complete programs and some contain only snippets or modules.

Notable programs include:
 - sudoku.b93
 - continued_squareroot_fraction.b93
 - gnome_sort.b93
 - Miller-Rabin primality test.b93
 - Sieve-Of-Eratosthenes-with-collector (v2).b93

Notes
-----

 - For some of the longer programs (err ... like ... all of them) use [BefunExec](https://github.com/Mikescher/BefunExec) or a similar fast interpreter. *(Your interpreter should support int64 numbers for some programs)*
 - I generally like to write Befunge-93 syntax. Unfortunately the '93 variant is not turing complete due to its restriction of a 80x25 size. I simply chose to ignore that restriction in the programs where I hit the limit (but I still try to compress my programs as much as possible). You could argue that - because of that - some programs are technically Befunge-98 (with a severe limited instruction set).

Overview
--------

######Almosted-Sorted-Distinct
Replaces all repeated values in an array with zero.
Works best on (almost) sorted lists (otherwise this is O(n^2))

######calcBase4Random
Get a random number between 0 and 4^n

######ConcatenateNumbers
Textually concatenate two numbers (eg: `648 o 120  = 648120`)

######continued_squareroot_fraction
Calculate the [continued fraction of a square root](https://en.wikipedia.org/wiki/Continued_fraction#Generalized_continued_fraction_for_square_roots)

######DecodeBase9
Calculates a number where its digits (int base-9) lie reversed on the stack

######DecodeBase9-2
Calculates a number where its digits (int base-9) lie in normal order on the stack

######Exponentiation
The Pow() function

######FacDigitSum
Calculates the sum of the factorials of a digit

######GenerateRandom
Get a random number between 0 and 4^n

######GenerateRandom_compressed
Get a random number between 0 and 4^n

######GetCombinatoricHash
Calculates a combinatoric hash value (the digit order is ignored).

######gnome_sort
Implementation of [gnome sort](https://de.wikipedia.org/wiki/Gnomesort). Gnome sort is not fast but simple to implement.

######HelloWorld
Print `hello world`

######HelloWorld_obfuscated
Print `hello world`

######Improbable
Runs for a random - but long - time

######integer-squareroot
Calculates the [integer-squareroot](https://en.wikipedia.org/wiki/Integer_square_root) of a number

######integer-squareroot-2
Calculates the [integer-squareroot](https://en.wikipedia.org/wiki/Integer_square_root) of a number

######is-squarenumber
Tests if an integer is a square number (really fast by deploying a number of numerical "tricks")

######Miller-Rabin primality test
An implementation of the [Miller-Rabin primality test](https://en.wikipedia.org/wiki/Miller-Rabin-Test) for numbers `0 < n < 1,373,653`

######Miller-Rabin primality test (big)
An implementation of the [Miller-Rabin primality test](https://en.wikipedia.org/wiki/Miller-Rabin-Test) for numbers `0 < n < 3,825,123,056,546,413,051`

######Primetest
A pretty basic primality test

######RandomChess
A big cube of `?` instructions

######RandomChess-2
A big cube of `?` instructions

######Sieve-Of-Eratosthenes
A implementation of the [sieve of eratosthenes](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)

######Sieve-Of-Eratosthenes-with-collector
A implementation of the [sieve of eratosthenes](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes) where we collect the found primes in a continuous memory region

######Sieve-Of-Eratosthenes-with-collector (v2)
A implementation of the [sieve of eratosthenes](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes) where we collect the found primes in a continuous memory region

######stack-array-count
Calculate the count of stack values (Null-terminated)

######stack-array-sum
Generate sum of stack values (Null-terminated)

######StackReverse
Reverse the values on the stack

######sudoku
A Sudoku solver (see my [blogpost about this program](https://www.mikescher.com/blog/9/A_complete_sudoku_solver_in_Befunge93))

######Windmill
A test program for [BefunExec](https://github.com/Mikescher/BefunExec).
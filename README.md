# C#: Sieve

Write a program that uses the Sieve of Eratosthenes to find all the primes from 2 up to a given number.

The Sieve of Eratosthenes is a simple, ancient algorithm for finding all
prime numbers up to any given limit. It does so by iteratively marking as
composite (i.e. not prime) the multiples of each prime,
starting with the multiples of 2.

Create your range, starting at two and continuing up to and including the given limit. (i.e. [2, limit])

The algorithm consists of repeating the following over and over:

- take the next available unmarked number in your list (it is prime)
- mark all the multiples of that number (they are not prime)

Repeat until you have processed each number in your range.

When the algorithm terminates, all the numbers in the list that have not
been marked are prime.

The wikipedia article has a useful graphic that explains the algorithm:
https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes

Notice that this is a very specific algorithm, and the tests don't check
that you've implemented the algorithm, only that you've come up with the
correct list of primes.

Follow these instructions on how to [get your C# development environment set up][csharp-installation].

The exercises use NUnit. Follow [this guide][nunit-guide] to get started.

[csharp-installation]: https://github.com/exercism/xcsharp/blob/master/docs/INSTALLATION.md
[nunit-guide]: https://github.com/exercism/xcsharp/blob/master/docs/TESTS.md

## Source

Sieve of Eratosthenes at Wikipedia [http://en.wikipedia.org/wiki/Sieve_of_Eratosthenes](http://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)

This exercise is from the [C#][csharp] track on [Exercism][exercism]

[exercism]: http://exercism.io
[csharp]: http://exercism.io/languages/csharp




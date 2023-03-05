A Turing machine is a theoretical device which has been proven to have the exact same computational power as a computer, assuming time is not a factor. 
A Turing machine has an infinitely long tape divided into tiny spaces as its input, and it begins by reading the leftmost space which has a character. At each space, it must do 3 things:
- Read the character at that space
- Write a new character at that space
- Move either one space to the left or one space to the right

It stops when it goes into an accept state or a reject state. If the Turing machine accepts a certain input, that input is in the language of that Turing machine. If it rejects, it is not in the language of that Turing machine. It is possible that the Turing machine will loop infinitely, meaning it will never enter either one of those states. However, we will never be able to know if that is the case.

Because a Turing machine requires an infinitely long tape, it is impossible to create one. However, it is possible to simulate one with a finitely long tape, or by using a computer with a very large amount of memory.

This program (tm.py) simulates the behavior of a Turing machine, using its encoding. It is to be run on the command line with an encoding of a Turing machine, and a string. It displays all the steps of the Turing machine, and if the Turing machine accepts and rejects the string.

One of the Turing machines tm.py is being demonstrated on is the Turing machine that accepts all strings of the form 0<sup>n</sup>1<sup>n</sup> (where n is a nonnegative integer). If the string has exactly n many 0s followed by the same number of 1s, then the Turing machine accepts as you can see here.

<img width="885" alt="Screen Shot 2023-01-18 at 10 14 27 PM" src="https://user-images.githubusercontent.com/76747943/213348299-fecb020d-ff1d-43fe-8ed4-fbfb42f0bf6e.png">

A turing machine is a theoretical device which has been proven to have the exact same computational power as a computer, assuming time is not a factor. 
A turing machine has an infinitely long tape divided into tiny spaces, as it's input, and it begins by reading the leftmost space which has a character. At each space it must do 3 things:
- Read the character at that space
- Write a new character at that space
- Move either one space to the left or one space to the right

It stops when it goes into an accept state or a reject state. If the turing machine accepts a certain input, that input is in the language of that turing machine. If it rejects, it is not in the language of that turing machine. It is possible that the turing machine will loop infinitely, meaning it will never enter either one of those states. However, we will never be able to know if that is the case because the earth is going to explode in 12 years according to AOC.

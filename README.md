# Vigen-re-s-cipher

Vigenère’s cipher works by encrypting messages using a sequence of keys (provided by a keyword).
The program accepts a single command-line argument: a keyword, k, composed entirely of alphabetical characters.
It then prompts the user for text that is then deciphered by the program.

As an example of how the cipher works, if Vigenère himself wanted to say HELLO to someone confidentially, 
using a keyword of, say, ABC, he would encrypt the H with a key of 0 (i.e., A), the E with a key of 1 
(i.e., B), and the first L with a key of 2 (i.e., C), at which point he’d be out of letters in the keyword,
and so he’d reuse (part of) it to encrypt the second L with a key of 0 (i.e., A) again, and the O with a key of 1 
(i.e., B) again. And so he’d write HELLO as HFNLP.

This is part of CS50's PSET2.

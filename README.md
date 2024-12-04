# This program is responsible for performing the shift cipher or Caesar cipher.
In cryptography, a Caesar cipher, also known as Caesar's cipher, the shift cipher, Caesar's code, 
or Caesar shift is one of the simplest and most widely known encryption techniques. 
It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet.
For example, with a left shift of 3, D would be replaced by A, and E would become B.
The method is named after Julius Caesar, who used it in private correspondence.

##The transformation can be represented by aligning two alphabets; 
The cipher alphabet is the plain alphabet rotated left or right in several positions.
For instance, here is a Caesar cipher using a left rotation of three places, equivalent to a right 
shift of 23 (the shift parameter is used as the key):

Plain   	A	B	C	D	E	F	G	H	I	J	K	L	M	N	O	P	Q	R	S	T	U	V	W	X	Y	Z<br>
Cipher	X	Y	Z	A	B	C	D	E	F	G	H	I	J	K	L	M	N	O	P	Q	R	S	T	U	V	W<br>

When encrypting, a person looks up each letter of the message in the "plain" line
and writes down the corresponding letter in the "cipher" line.

Plaintext:  THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG<br>
Ciphertext: QEB NRFZH YOLTK CLU GRJMP LSBO QEB IXWV ALD,<br>

##Deciphering is done in reverse, with a right shift of 3.

The encryption can also be represented using modular arithmetic by first transforming the letters into numbers, according to the scheme, A → 0, B → 1, ..., Z → 25.[2] Encryption of a letter x by a shift n can be described mathematically as,[3]

## E(x)=(x+n)\mod 26

Decryption is performed similarly,
## D(x)=(x-n)\mod 26
(Here, "mod" refers to the modulo operation. The value x is in the range 0 to 25, but if x + n or x − n are not in this range then 26 should be added or subtracted.)

The replacement remains the same throughout the message, so the cipher is classed as a type of monoalphabetic substitution, as opposed to polyalphabetic substitution.


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

Plain	A	B	C	D	E	F	G	H	I	J	K	L	M	N	O	P	Q	R	S	T	U	V	W	X	Y	Z<br>
Cipher	X	Y	Z	A	B	C	D	E	F	G	H	I	J	K	L	M	N	O	P	Q	R	S	T	U	V	W<br>

When encrypting, a person looks up each letter of the message in the "plain" line
and writes down the corresponding letter in the "cipher" line.

Plaintext:  THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG<br>
Ciphertext: QEB NRFZH YOLTK CLU GRJMP LSBO QEB IXWV ALD

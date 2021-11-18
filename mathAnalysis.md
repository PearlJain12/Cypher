# Mathematical Analysis of Four Square:

The four square cipher falls under a category of Ciphers known as Polygraphic Substitution Ciphers. These contribute more encryption than Monographic Substitution Ciphers 
because they use pairs of letters to encrypt. The Digraph aspect makes it less susceptible to frequency analysis attacks as there are 676 possible digraphs.

![alt text](https://crypto.interactive-maths.com/uploads/1/1/3/4/11345755/4245790_orig.jpg "Four Square")

Digraph Substitution => replacing a pair of letters with a single symbol.

Frequency Analysis Attacks => the process of analyzing the frequency at which letter show up in an encrypted message order to decrypt it.

This works because certain letters are used more than others, so when you have identified one letter, you can figure out the key. For example, 'e' is used 4x more than 'm' in general.

During the encryption process, two keys are used.

Like most pre-modern era ciphers, it isn't difficult to decrypt the four square cipher. When you have both the plaint text and the encrypted version, finding the key is simple. When only the cypher text is known, though,
you have to use brute force cryptoanalysis to figure out the frequencies of certain pairs. While four square is less susceptible to frquency analysis attacks, they are the 
best way to decrypt these ciphers. There is a low level of mathematics involved and all you need to do is analyze graphs. 

![alt text](https://crypto.interactive-maths.com/uploads/1/1/3/4/11345755/5749995_orig.jpg "Frequency")


[Historical](Historical.md)

[Mechanics](Mechanics.md)

[Computer Code](compCode.md)

[Final Analysis](https://github.com/PearlJain12/Cypher/blob/main/Final-Analysis.md)

[Main Page](README.md)



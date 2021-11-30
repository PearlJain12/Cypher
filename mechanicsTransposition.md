# Mechanics

In order to encrypt with the transposition cipher, you need plain text (e.g. "We love the transposition cipher"). You will also need a key. This key will 
create a table used for encryption. Our key will be '7 x 5'. This means that there will be 7 rows and 5 columns columns in our table.

Our encryption process would look like this:
***
1 2 3 4 5 

W e - l o

v e - t h

e - t r a

n s p o s

i t i o n

\- c i p h

e r
***

Then, you create the encrypted message by creating ords going down the columns.

"Wveni-eee-stcr--tpii-ltroop-ohasnh-"

To decrypt, you can create a matrix. Count the number of characters in the message: 35. When you factor this, you get a 5 x 7 matrix. Notice that this is opposite the original key. 

***
w v e n i - e

e e - s t c r 

\- - t p i i .

l t r o o p - 

o h a s n h -
***
Once again, going down the columns, you get "We love the transposition cipher"
Since the process of encryption and decryption is the same, this cipher is symmetrical.

[Historical](HistoricalTransposition.md)

[Mathematical Analysis](mathAnalysisTransposition.md)

[Computer Code](compCodeTransposition.md)

[Final Analysis](finalAnalysisTransposition.md)

[Main](README.md)


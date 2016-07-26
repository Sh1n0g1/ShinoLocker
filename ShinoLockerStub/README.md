#ShinoLockerStub

<pre>
Usage: ShinoLockerStub \<E|D\> \<KEY\> \<IV\> \<FILEPATH\>
<E|D>                D to decrypt, E to encrypt.
<KEY>                AES key (Base64)
<IV>                 AES IV  (Base64)
<FILEPATH>           File to encrypt/decrypt

All parameters are mandatory and the order is stricted.

Example:
ShinoLockerStub E VEFLRVNISVRFU0hJR0FXQQ== UkFUQUtFU0hJVEVTSElHQQ== C:\file.txt


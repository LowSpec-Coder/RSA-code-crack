# RSA-code-crack
Made this for fun,  crack the rsa given the cipher(c), the encryption key(e, N) where e = 65,537. In RSA c = M^e (mod N)

Steps to crack RSA 
1.First factorize N into p and q (here). This will give you p and q (the two prime numbers).
2.Next we determine PHI=(p−1)(q−1).
3.Next we derive d (the decryption key value) from e and PHI.
4.Then decipher with Msg=Cd(modN)

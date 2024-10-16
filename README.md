# Mandatory Crypto

## What you're asked to do

1. Decrypting a ciphertext knowing the key
Under the folder *decrypting_otp* you will find a cipher-image and a key. Using the *images_xor.py* script, decrypt the cipher-image and recover the corresponding plain-image.

2. Breaking OTP when the key has been reused
Under the folder *breaking_otp* you will find two cipher-images. We don’t know anything about the corresponding plaintexts, only that they are images and that the same key has been used for both encryptions.

    - a. Can you get any information about the two plaintexts? Beware that we don’t aim at entirely recovering them (which is possible but a bit more complicated (*)). We just want to find out how they look like.
    
    they are the key to each other, very holesome :D

    - b. Find out and explain, in a more formal way (maybe using some mathematical expressions), why it’s a bad idea to reuse the key in OTP. You will need to use the XOR properties seen in class.
    
    The whole idea with OTP is that its ony used one time and fits the specific length of that message. And if one message is cracked, the next cant be cracked with the same key.

3. OTP alternatives
OTP, by definition, works XORing the plaintext with the key to encrypt, and XORing the ciphertext with the same key to decrypt. Modify the *images_xor.py* script to use the binary operators AND, and then also OR, instead of XOR. What do you observe in both cases and why?

with AND and OR it only reveals the differences, XOR. AND only inputs a bit if both inputs are 1, and OR only does it if one of the inputs is a 1. 

 


(*) You’re of course welcome to try, as a bonus exercise.






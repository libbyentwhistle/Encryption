# Encryption and Decryption
A walkthrough of encryption work in python by using a simple (reverse encryption), caesar cipher and a combination of the two. There is also decryption included, the reverse process of encryption. 

## Encryption

### Simple Encryption

The simple encryption file is based off an example from https://www.codementor.io/python/tutorial/python-encryption-message-in-python-via-reverse-cipher.
The simple encryption can be accessed here: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13oFog866ZGBxyNTXaFpecZ9_Zb8l7SM-#scrollTo=0WCS2h9w_kgD)


The first block of code is a very simple one, the second block of code allows the viewer to add their own message and see it be encrypted. If you rerun the code you will be able to encrypt your own message!

The simple encryption is called a **reverse cipher**, as the output is the input reversed. For example: 


Input: Blue


Output: eulB

### Caesar Cipher

The second file, the **Caesar Cipher** is based off of this example from: https://medium.com/@Operaho/make-a-caesars-cipher-with-python-8958ffa1e90d. 
The Caesar cipher can be accessed here: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I8anDUiN3je9II2CsXWHUthVsJnnitg6) . 
If you rerun the code you will be able to encrypt your own message!

A caesar cipher shifts all letters in the message by a key. For example to encrypt the word "green" with a key of 5 would become: 
      lwjjs

### Combined Cipher

The third file, the **Combined Cipher** is a combination of the Caesar cipher and the reverse cipher. 
The combined cipher can be accessed here: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xoO40lPgfDB__hJgXP90MPL8tzNNp1Ai#scrollTo=PuGoVo11sEZC) .
If you rerun the code you will be able to encrypt your own message!

The Combined Cipher works by first doing a Caesar cipher on the message, and then doing a reverse cipher on the message after it has been encrypted by the Caesar cipher. 

For example if red was to be encrypted with a key of 24 the final answer would be: **bcp**


## Decryption

### Simple Decryption

The code to access the simple decryption can be accessed here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1m9rdPY4bl3o0ychEP6zrM2YwM3FnbFCD#scrollTo=k84zWtXL7yF_) .
If you rerun the code, you will be able to decrypt your own encrypted message!

As you can see, the code is almost identical to the simple encryption. 


### Decryption of a Caesar Cipher

#### Key Known

The code to access the code to decrypt when the key is used can be accessed here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JXgOgtA6Y1E6PewjxAqtYQI737az9Smx) .

As you can see the code to decrypt is very similar to the code to encrypt using a Caesar cipher, however instead of moving forwards through the alphabet by the key, we move backwards through the alphabet by the key in order to determine the origanl message.

#### Key Unknown

The code can be accessed here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EE3NqMSDbY-iwKPCjSPWQ0Wtj14Jrhfp#scrollTo=m4gxT7rncElU) .

This code uses brute force to determine what the original message was before it was encrypted. This means it will use every key possible and prints out every possible answer. Only one solution is in readable English, and thus must be the original message. 

### Combined Decryption

The combined decryption can be accessed here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iV47gYw9CqNIAtnTkxvwAjAvKsLN-F_9) .

This combines the reverse cipher and the Caeser cipher. When the combined cipher was coded the Caeser cipher was done before reversing the cipher, so when we decipher it the steps are done in reverse, first the encrypted message is reversed and then brute forced in order to reveal the original message. 


# Encryption
A workthrough of encryption work in python by using a simple (reverse encryption), caesar cipher and a combination of the two. 

## Simple Encryption

The simple encryption file is based off an example from https://www.codementor.io/python/tutorial/python-encryption-message-in-python-via-reverse-cipher.
The simple encryption can be accessed here: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13oFog866ZGBxyNTXaFpecZ9_Zb8l7SM-#scrollTo=0WCS2h9w_kgD)


The first block of code is a very simple one, the second block of code allows the viewer to add their own message and see it be encrypted. If you rerun the code you will be able to encrypt your own message!

The simple encryption is called a **reverse cipher**, as the output is the input reversed. For example: 


Input: Blue


Output: eulB

## Caesar Cipher

The second file, the **Caesar Cipher** is based off of this example from: https://medium.com/@Operaho/make-a-caesars-cipher-with-python-8958ffa1e90d. 
The Caesar cipher can be accessed here: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I8anDUiN3je9II2CsXWHUthVsJnnitg6) . 
If you rerun the code you will be able to encrypt your own message!

A caesar cipher shifts all letters in the message by a key. For example to encrypt the word "green" with a key of 5 would become: 
      lwjjs

## Combined Cipher

The third file, the **Combined Cipher** is a combination of the Caesar cipher and the reverse cipher. 
The combined cipher can be accessed here: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xoO40lPgfDB__hJgXP90MPL8tzNNp1Ai#scrollTo=PuGoVo11sEZC) .
If you rerun the code you will be able to encrypt your own message!

The Combined Cipher works by first doing a Caesar cipher on the message, and then doing a reverse cipher on the message after it has been encrypted by the Caesar cipger. 

For example if red was to be encrypted with a key of 24 the final answer would be: **bcp**

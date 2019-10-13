#  Crypto Warmup 1

Points:75

## Question:

```
Crpyto can often be done by hand, here's a message you got from a friend, llkjmlmpadkkc with the key of thisisalilkey. Can you use this table to solve it?
```


## Hint:

```
-Submit your answer in our competition's flag format. For example, if you answer was 'hello', you would submit 'picoCTF{HELLO}' as the flag.
-Please use all caps for the message.
```


# Solution:

1. This is a question related to vigenere cipher.
2. Remember the table given is to encrypt a message into a vigenere cipher and we have to decrypt the message for this particular      question.
3. So we have to use the table in reverse manner.Pick up a key and find the cipher text alphabates in that row or column. For ex. key(1)=t,CipherText(1)=l. So find the alphabet 'l' in the row or column of alphabet 't. Here we will get PlainText(1)=S. Proceed in the similar way and decrypt the entire Cipher.
4. If you are lazy to read the point 3, I have one tool here... have fun ;) :https://github.com/Amangondaliya555/PyVigenere

## Flag:

```
picoCTF{SECRETMESSAGE}
```

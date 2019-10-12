#Crypto Warmup 1

Points: 75
Category

##Cryptography
Question

    Crpyto can often be done by hand, here's a message you got from a friend, llkjmlmpadkkc with the key of thisisalilkey. Can you use this table to solve it?.

Hint

    Submit your answer in our competition's flag format. For example, if you answer was 'hello', you would submit 'picoCTF{HELLO}' as the flag.

    Please use all caps for the message.

Solution

This uses a Vigenère Cipher. Online tool: https://planetcalc.com/2468/

    Set Transformation to Decrypt
    Set Key to thisisalilkey
    Set Text to llkjmlmpadkkc
    Click CALCULATE

Transformed text is secretmessage
Flag

picoCTF{SECRETMESSAGE}

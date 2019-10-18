#  blaise's cipher

Points:200

## Question:

```
My buddy Blaise told me he learned about this cool cipher invented by a guy also named Blaise! Can you figure out what it says? Connect with nc 2018shell.picoctf.com 46966. 
```


## Hint:

```
1.There are tools that make this easy.
2.This cipher was NOT invented by Pascal.
```


# Solution:

  1.Here we have to connect to the 2018shell.picoctf.com 46966.
  
  2.After connecting to it, we got a long senseless paragraphs.
  
  3.It is nothing but actually encrypted. By observation, we can say it is either a caesar cipher or a vigenere cipher.
  
  4.But the title of the question is blaise's cipher. Which is a name of the inventor of Vigenere cipher.So those paragraphs are  
  encrypted using vigenere cipher.
  
  5.Command line tools may have some issues due to long paragraphs and also we dont know the key. So we can use other online 
  tools. For ex: https://www.mygeocachingprofile.com/codebreaker.vigenerecipher.aspx
  
  6.Using this tool, you will get lots of solutions with different key. You will have do random search. You will find the key in 
  decrypted paragraph with key = 277.

## Flag:

```
picoCTF{v1gn3r3_c1ph3rs_ar3n7_bad_cdf08bf0}
```

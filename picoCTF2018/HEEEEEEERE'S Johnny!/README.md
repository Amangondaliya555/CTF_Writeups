# HEEEEEEERE'S Johnny!

Points:100

## Question:

```
Okay, so we found some important looking files on a linux computer. Maybe they can be used to get a password to the process. Connect with nc 2018shell.picoctf.com 40157. Files can be found here: passwd shadow. 
```


## Hint:

```
1.If at first you don't succeed, try, try again. And again. And again.
2.If you're not careful these kind of problems can really "rockyou".
```


# Solution:

  1.Rockyou in the hint is very well highlighted and it actually helps too. But we can solve even without rockyou.

  2.You must have the knowledge of how to use john the ripper tool. 
   
  3.use command as given below:
  --> unshadow passwd shadow
  --> john --show shadow
  
  4.Explaining above commands, unshadow combine two files to make it useable for the john tool. and john is a password cracker
  tool which i will suggest you to learn, it is very useful.

  5.That isnt it guys! we have to connect to the nc 2018shell.picoctf.com 40157. They will ask username and password. And from  
  the above steps we already got a username and password. Here username will be "root", and password maybe different for   
  different users.for me it was: password1 
  
  6. Use the credentials  and there you got a flag! :)

## Flag:

```
picoCTF{J0hn_1$_R1pp3d_1b25af80}
```

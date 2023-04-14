# Level 7 -> 8
Login to Natas.
Another secret key, let’s go ahead and view sourcecode.
It seems that the secret code we need is encoded. Looking though the PHP code we can see that the “secret” entered is converted from bin to hex, reversed, and then base64 encoded.
So for us to get the “secret” we have to reverse engineer this. Let’s begin by opening the console, and start up PHP with php -a. We can get the secret key from the encoded key by base64 decoding it, reversing the string, and converting the hex back to binary
```
$ php -a
Interactive mode enabled
$ echo base64_decode(strrev(hex2bin('3d3d516343746d4d6d6c315669563362')));
oubWYf2kBq
```
Entering above in query, will get the password
The password for next level is `Sda6t0vkOPkM8YeOZkAGVhFoaplvlJFd`.

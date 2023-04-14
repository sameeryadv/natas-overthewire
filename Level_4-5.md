# Level 4 -> 5
Login to NATAS.
We can see we don’t have access to the webpage because we are not logged in. Let’s fire up Burp Suite and see if we can intercept the packet for the natas5.
Now using Burp, we see that in Cookies `loggedin=0`. We will set `loggedin=1`. Now we will get password.
The password is `fOIvE0MDtPTgRhqmmvvAOt2EfXR6uQgR`.

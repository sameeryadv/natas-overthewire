# Level 6 -> 7
Login to natas. When you view page source, you will see password is in `etc/natas_webpass/natas8`.
udging by the hint, I assume this is a Directory Traversal Attack.

If we click on Home our URL should display http://natas7.natas.labs.overthewire.org/index.php?page=home. Let’s go ahead and remove home and add /etc/natas_webpass/natas8. The URL should look like so: http://natas7.natas.labs.overthewire.org/index.php?page=/etc/natas_webpass/natas8 .
The Password for next level is `a6bZCNYwdKqN5cGP11ZdtPg0iImQQhAB `.

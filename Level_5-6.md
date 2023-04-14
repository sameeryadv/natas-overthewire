# Level 5 -> 6
Login to Natas.
Alright, for this level we are to enter a secret, and the query should return the password… hopefully! Let ‘s go ahead and click View sourcedode and we should get the below PHP script.
It seems that the PHP is including a link to a file stored on the webpage /includes/secret.inc. Let’s go ahead and add that to the end of our URL, like so: http://natas6.natas.labs.overthewire.org/includes/secret.inc. We should come up to a blank webpage, so let’s View Page Source.
Another PHP script, with the secret code we need. Let’s go back to the home page and enter it. If correct, we should get the password `jmxSiH3SP6Sonf8dv66ng8v1cIEdjXWr`.

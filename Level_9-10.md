# Level 9 -> 10
Login to Natas. Click on view source.
Okay, so the script seems to be the same as level 9’s, but now they are filtering the ; and & command.
Seems they still haven’t fixed the way “key” is storing input. So we can exploit this the same way we did in 9; but this time just using regular expressions.
Let’s go ahead and enter `.* /etc/natas_webpass/natas11 #` inside the query. By entering `.*`, we tell grep to search for all, while ignoring case, and match it to `etc/natas_webpass/natas11`. The `#` command, comments out dictionary.txt, preventing any errors from occurring.


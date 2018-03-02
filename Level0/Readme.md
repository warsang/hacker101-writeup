# Level 0: Breakerbank

## CSRF
After trying an amount lower than zero with any account number, we get the [sample bug report](https://levels-a.hacker101.com/static/report0.txt) so I won't write up on the CSRF.

## Authorization Bypass/Direct Object Reference

The second vulnerability I found was that we can add a from parameter to the POST request allowing an attacker to transfer arbitrarily funds from any account to any other account

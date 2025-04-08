# my notes on cybersecurity
this repo covers good-enough cybersecurity practices which i try to follow
this won't cover you if you're an active target, but i can certainly guarantee you that you aren't

## general tips:

- use a [password manager](#password-manager)
- use authenticators (i go with google authenticator because i'm sure it won't go away and i won't lose access to it)
- use google/github oauth whenever possible. if you reuse a password and it gets leaked, you'll have to change it everywhere, however if your oauth password leaks you can just change the password theme
- on ios, avoid relying on apple for auth. you'll get locked into apple if you do.
- use auto-generated passwords. if you follow this, you shouldn't be afraid of losing them
- avoid running software that has access to passwords outside of it. i'll cover that in the [software](#software) section

## password manager
preferrably back them up to google every once in a while
my choice is bitwarden
check [have i been pwned](https://haveibeenpwned.com/) once in a while

- bitwarden: opensource, able to be self-hosted, good autofill on mobile. slightly annoying to use because it locks your vault. best option if you care and if you self-host in
- google: may not be private, but very secure. best autofill on android, works on IOS too. you can't use it on non-chromium browsers on desktop unless you import your passwords. you can also just get locked out of your google account sometimes
 proton pass: way too new to be confident in it. has autofill for mobile and browser extensions

## software
this will cover running software that has access to external passwords

- giving your passwords to big big tech is usually alright, but minimize the amount of services you give them to.
- certain software with built up reputation is good too. bitwarden and keepass are checked constantly and keepass's RCEs are ridiculously minor
- running small pieces of software is good too, but make sure you understand the code and make sure there's no malicious imports. read the package's requirements.txt or packages.json. i don't recommend running software in languages you don't understand

## identity
only applies if you have multiple online identities. so, a personal account and an online account.
it is good practice for those who play competetive games or have to interact with any agressive online communities

- use separate emails and a usernames
- don't make up fake names, locations and such. just don't tell anyone about your real one

## contributing
if you feel like i'm wrong on something or want to add something, submit a pull request or an issue
just be pragmatic about it

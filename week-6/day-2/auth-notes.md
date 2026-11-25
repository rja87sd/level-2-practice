# Week 6 Day 2 — Auth notes

Write 1–2 sentences for each, in your own words. **No keys in this file**: it gets pushed.

## API key

What is it for?
- The API key is a means of authorizing a user to use the API. It basically says "this request is from me/my account."


## OAuth

What is it for? (Think: "Sign in with Google" on another website.)
- It allows one app to use another app for a user without getting their password. This is how a user can sign in with their Google account on a different website, for example.

## JWT

What is it for? (Think: the wristband you get after showing your ID at the door.)
- It is a signed token with an expiration time/date given by a server after you log in. You show it with each request so you don't have to log in every single time you send one.

## Where did my key live today?

Which file, and why doesn't it get pushed?
- It lived in config.js. It doesn't get pushed because that file is listed in .gitignore, so Git ignores it when committing changes.


## Could I put this page on GitHub Pages? Why not?

- No. We don't want to put the key on GitHub because every user could find and copy it.
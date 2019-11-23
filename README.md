# Sempo Fullstack Coding Challenge

## Introduction
Transactions on the Ethereum Blockchain are made by signing a message using a private key, which is 32-byte secret like that looks something like `0x7dcbb63dd31af85ea96d5e87541663bd3e8e8e4b2574964bfc8365f6b39e764a`. 

Unfortunately Private Keys are very difficult for humans to remember, especially for people with low levels of literacy.

Various methods have been suggested for making Private Keys into something more human friendly, including converting them into a sequence of emojis.

## The task 
Your challenge is to create a web app that supports the following:
- When a user submits their name, a 32 byte private key should be generated on a backend server
- In return, the user receives their private key in the form of a sequence of emojis. The sequence should use **no more than 29 unique emojis, and be as short as possible.**
- When the user enters the correct sequence of emojis and submits them, the server should return the correct name

## Other Requirements
- Private keys should be stored on the server in a secure manner
- Please use Python for the backend and React with JSX for the frontend - all other decisions are up to you!
- When you're finished, please share a github or other source control repository containing your work, along with instructions on how to run your code on a local machine.

## BONUS ROUND

Instead of converting Private Keys into a sequence of Emojis, convert them into human-readable sentences using a modified Markov Chain text generator.
Word suggestions might be used to help users re-enter their sentences correctly.



# Simple-XSS-Keylogger

XSS Keylogger is a simple way to record a webpage visitor’s data. It’s used to record one’s passwords, to capture private messages, and to leak personal information. In most cases, intruders steal cookie session to identify the target user. However, sometimes the cookie session isn’t enough and an intruder may need to know what keys the website’s visitor presses.
HTTP only cookie;
non-session based authentication;
a password necessary for activities with higher privileges.

This keylogger stores all keystrokes with timestamps in the array and sends them to the server controlled by a hacker via HTTP every 2 hundred milliseconds. This tutorial is a simple example of what you can record with Javascript backdoor. It’s also possible to record mouse movements and clicks and a DOM element and to view the recorded data in live mode.

Javascript code:
![image](https://user-images.githubusercontent.com/92847004/138407416-69919d0f-f7e1-492b-8f57-e5839a675e06.png)

PHP-Server code:
![image](https://user-images.githubusercontent.com/92847004/138407532-cd127d23-1d94-48c4-a0de-47b86c1c0c0a.png)

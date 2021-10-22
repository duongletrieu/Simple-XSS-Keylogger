# Simple-XSS-Keylogger

XSS Keylogger is a simple way to record a webpage visitor’s data. It’s used to record one’s passwords, to capture private messages, and to leak personal information. In most cases, intruders steal cookie session to identify the target user. However, sometimes the cookie session isn’t enough and an intruder may need to know what keys the website’s visitor presses.
HTTP only cookie;
non-session based authentication;
a password necessary for activities with higher privileges.

This keylogger stores all keystrokes with timestamps in the array and sends them to the server controlled by a hacker via HTTP every 2 hundred milliseconds. This tutorial is a simple example of what you can record with Javascript backdoor. It’s also possible to record mouse movements and clicks and a DOM element and to view the recorded data in live mode.

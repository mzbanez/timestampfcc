API Basejump: Timestamp Microservice - FreeCodeCamp Challenge
=========================

Project
------------

User Stories

I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016)
If it does, it returns both the Unix timestamp and the natural language form of that date.
If it does not contain a date or Unix timestamp, it returns null for those properties.

Sample Usage:

https://timestamp-mzbanez.glitch.me/January20

https://timestamp-mzbanez.glitch.me/1518048011

-------------------

Sample Output:

{"unix":"1484870400","natural":"January 20, 2017"}

{"unix":"1518048011","natural":"February 8, 2018"}
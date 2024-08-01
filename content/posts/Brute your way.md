---
title: "Brute your way In "
date: 2024-08-01T05:11:55+05:00
description: "Some time status 200 is not enoguh"
tags: [Brute]
categories: [Burp]
---
Initial Commit
Some times the status code is not telling the truth, espcially in graphql endpoints 
I had to search for status code inside the body response. 
![alt text](<Brute your way in.png>)
Status 200 should have been different 
![alt text](<Brute your way in-3.png>)
The actual error was password expired which was not handled gracefully in the application.
![alt text](<Brute your way in-2.png>)


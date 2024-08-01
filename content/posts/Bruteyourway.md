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
![Brute your way in](https://github.com/user-attachments/assets/451858b7-b957-4f4d-97fe-e71ad6fc688b)

Status 200 should have been different 
![Brute your way in-3](https://github.com/user-attachments/assets/dec4d6dc-3530-4488-92cd-42210b3a931c)

The actual error was password expired which was not handled gracefully in the application.

![Brute your way in-2](https://github.com/user-attachments/assets/10201a33-c855-4b37-a700-feb90e0c7221)


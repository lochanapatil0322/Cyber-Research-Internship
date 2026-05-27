# File Upload Vulnerability - Remote Code Execution via Web Shell Upload

## Lab Details
- Platform: PortSwigger Web Security Academy
- Difficulty: Apprentice
- Status: ✅ Solved

## Description
This lab has a vulnerable file upload function that performs no validation 
on uploaded files. I uploaded a PHP web shell instead of an image, which 
the server executed, allowing me to read sensitive files — this is called 
Remote Code Execution (RCE).

## Tools Used
- Burp Suite Community Edition
- PortSwigger Web Security Academy





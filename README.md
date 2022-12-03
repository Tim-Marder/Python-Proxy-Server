# Binghamton University: CS428 2022 Fall

## Project-3: Web Proxy Server

### SUMMARY

[Provide a short description of your program's functionality, no more than a couple sentences]: #
Proxy Server to demonstrate the usual behavior of a client requesting information from a web server, which is handled by a proxy server in between to make future delivery of information faster and more efficient.

### NOTES, KNOWN BUGS, AND/OR INCOMPLETE PARTS

[Add any notes you have here and/or any parts of the project you were not able to complete]: #
N/A

### REFERENCES

[List any outside resources used]: #
https://alexanderell.is/posts/simple-cache-server-in-python/
https://stackoverflow.com/questions/919897/how-to-obtain-a-thread-id-in-python

### INSTRUCTIONS

[Provide clear and complete step-by-step instructions on how to run and test your project]: #
1. Make sure that the proxyserver file is in another directory from the webserver and the home.html file in order to properly test whether or not the proxy server works.
2. Run the `webserver1.py` file in one terminal instance.
3. Run the `proxyserver1.py` or `proxyserver2.py` instance in another terminal instance.
4. On another device, put the first device's IP and the proxy server's port into the browser's URL with `/home.html` at the end.
5. If the page loads, then the proxy server works.
6. Double check in the terminal instances that the forward and response messages are printed by both the proxy and web servers.
7. When testing the cached proxy server, reload the URL multiple times and confirm that the page still loads, the proxy server is printing a "proxy-cache" message to the terminal, and the web server is no longer being used to retrieve the data.

### SUBMISSION

I have done this assignment completely on my own. I have not copied it, nor have I given my solution to anyone else. I understand that if I am involved in plagiarism or cheating I will have to sign an official form that I have cheated and that this form will be stored in my official university record. I also understand that I will receive a grade of "0" for the involved assignment and my grade will be reduced by one level (e.g., from "A" to "A-" or from "B+" to "B") for my first offense, and that I will receive a grade of "F" for the course for any additional offense of any kind.

By signing my name below and submitting the project, I confirm the above statement is true and that I have followed the course guidelines and policies.

Submission date: 11/30/2022

Team member 1 name: Tim Marder

Team member 2 name: Joshua Gordon

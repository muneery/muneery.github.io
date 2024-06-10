# waph-alkhasme
# WAPH-Web Application Programming and Hacking
 
## Instructor: Dr. Phu Phung
 
## Student
 
**Name**: Muneer Al-Khasawneh
 
**Email**: alkhasme@mail.uc.edu
 
**Short-bio**: I am a computer science student with keen interests in ethical hacking.
 
![Muneer's headshot](ubuntui01.png)
 
## Repository Information
 
Respository's URL: [https://github.com/muneery/waph-alkhasme/tree/main/labs/lab1]([https://github.com/muneery/waph-alkhasme/tree/f0c0468f583e93e79b435b13495ed9a7f0a99f7b/labs/lab0](https://github.com/muneery/waph-alkhasme/tree/main/labs/lab1))
 
This repository belongs to Muneer which is private to store source codes practiced.
 
### Lab 1 Report

For Lab 1 its primary focus was tracking and updating lab commits. We were to use Wireshark to explore HTTP protocols and observe the traffic flow as shown in my screenshots. We also use CGI, PHP, and ECHO while programming in C to improve the web interface and to understand request messages. In one of the last steps, we used curl to create POST requests and to also analyze. This lab enhanced monitoring and networking within the web of Wireshark.
 
### Part 1: The Web and HTTP Protocol

### Task 1 & 2: Familiarity and Understanding of the Wireshark tool and HTTP protocol and using Telnet.

In Task 1, Wireshark was installed to monitor network traffic by capturing HTTP requests and responses, allowing the analysis of HTTP streams and overall traffic flow. In Task 2, telnet was used alongside Wireshark to manually interact with a web server by customizing HTTP requests. This involved sending requests to the server at port 80 as seen in my screenshots, highlighting the differences between manual telnet requests and browser-based requests. The combined use provided clear view of the communication between the client and server.

![HTTP Requests](lab2_1.png)
![Response Requests](lab2_2notm.png)
![Stream Requests](httpstream3.png)
![Telnet](lab2_4.png)
![Manual Requests & Analysis](lab2_5_80.png)



### Part 2: Basic Web Application Programming

### Task 1. CGI Web applications in C (a & b):

For task 1, I wrote and compiled a C CGI program, configured it on a web server, and accessed it via a browser. Then, I created an advanced CGI program by integrating C code with HTML, following similar steps, and deployed it on the web server.

![CGI 1](lab2_cgi6.png)
![CGI 2](lab2_cgiweb7.png)
![W3schools Code and Server](lab2_cgiedit8.png)



### Task 2. A Simple PHP Web Application with user input. (a & b):

For task 2, I developed a simple PHP web application with two components a "helloworld.php" displaying my name and an "echo.php" that echoes user input. Both Pages were configured and accessed via localhost on the web server. I demonstrated basic PHP functions and highlighted potential security risks like injection with the "echo.php" due to the lack of input validation. Proper input sanitization is crucial to mitigate these vulnerabilities. Below are my screenshots.

![Helloworld PHP](lab2_php9.png)
![ECHO PHP](echolab210.png)



### Task 3. Understanding HTTP GET and POST requests. (a, b, & c):

a. Using Wireshark, I analyzed HTTP GET requests for "echo.php" after submitting my name with "data=".In my screenshots, you will see the traffic and headers managing these requests.

b. I employed curl to execute an HTTP POST request with my name to "echo.php". Screenshots from curl showcase the request execution and the corresponding HTTP stream captured by Wireshark, detailing the data transmission.

c. HTTP GET requests are visible in the address bar and retrieve data from the server, while POST requests are not visible and are used for uploading larger data. Both types include crucial headers and support various data formats like JSON and HTML, as evidence in the provided screenshots. These comparisons highlight the distinct roles and characteristics of GET and POST methods in web communication.

![POST Curl](lab2_11.png)
![HTTP Curl](lab2_12.png)





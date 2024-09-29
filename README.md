# Port-Scanner-Python
 Port scanning is a script or program created to search for an open host. It can find which ports are open on a network device, a server, a router, or an ordinary desktop. Learn how to develop a port scanner with Python very simply. 
This article will teach you how to use the socket module in Python to create your port scanner. The central premise of this straightforward port scanner is to use a list of ports to attempt to connect to a given host (website, server, or any other device connected to the Internet or network). The port is open if you have successfully established a connection.

For example, when you loaded this page, you connected to this website on port 80. In a similar vein, this script will attempt to connect to a host on several different ports. Don't use this tool on a host you aren't authorized to test; these tools are helpful for penetration testers and hackers!


**Table of contents:**

•	Simple Port Scanner

•	Conclusion

•	Disclaimer



**Simple Port Scanner**

Let's begin by creating a basic port scanner and importing the socket module. If the socket module is installed on your computer and is part of the Python standard library, you don't need to install anything.

Here's a simple Python port scanner using the socket library. This script scans a range of ports on a specified host to check if they are open or closed.

![Port Scanner 01](https://github.com/user-attachments/assets/fee81037-70a5-4193-bd4d-26561a00f913)
![Poer Scanner Python 02](https://github.com/user-attachments/assets/623d0d5d-168b-4937-85b9-0f04ffabc7c2)



**Conclusion.**

Port scanning works well most of the time. A certified penetration tester can use this tool to check which ports are open, identify possible security devices like firewalls, assess network security, and evaluate device strength.

Hackers who want to find weak spots on the target machine often use it as a reconnaissance tool.
Nmap, a popular choice among penetration testers, offers advanced features beyond port scanning. It provides sophisticated methods to identify running operating systems and services, making it a comprehensive tool for network assessment.


**Note:**

•	Scanning ports on a remote server without permission may be illegal or against the terms of service of the network provider. 

•	The socket library is used here to attempt connections to each port. If a connection is successful, the port is considered open.



**Disclaimer:**

**Always ensure you have permission to scan the target host.**

**If it is abused, I won't be held accountable.**


Please note that this script's purpose is to help people learn Python and test it on their own devices. 



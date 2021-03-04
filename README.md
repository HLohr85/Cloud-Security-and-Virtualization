# ELK-Stack-Project

Domain: Network Security
Question 1:  Faulty Firewall
Suppose you have a firewall that's supposed to block SSH connections, but instead lets them through. How would you debug it?
Make sure each section of your response answers the questions laid out below.
​


Restate the Problem


Provide a Concrete Example Scenario

In Project 1, did you allow SSH traffic to all of the VMs on your network?
Which VMs did accept SSH connections?
What happens if you try to connect to a VM that does not accept SSH connections? Why?



Explain the Solution Requirements

If one of your Project 1 VMs accepted SSH connections, what would you assume the source of the error is?
Which general configurations would you double-check?
What actions would you take to test that your new configurations are effective?



Explain the Solution Details

Which specific panes in the Azure UI would you look at to investigate the problem?
Which specific configurations and controls would you check?
What would you look for, specifically?
How would you attempt to connect to your VMs to test that your fix is effective?



Identify Advantages/Disadvantages of the Solution


Does your solution guarantee that the Project 1 network is now "immune" to all unauthorized access?


What monitoring controls might you add to ensure that you identify any suspicious authentication attempts?​




Question 2: Unsecured Web Server
Suppose you find a server running HTTP on port 80, despite compliance guidelines requiring encryption in motion. What do you do?
​​


Restate the Problem


Provide a Concrete Example Scenario


In Project 1, did you have servers running HTTP on port 80?  If so, why was it permissible to do so?


In a real deployment, which specific machine would you configure differently? How, and why?




Explain the Solution Requirements

Why is running HTTP on port 80 a potential problem?
How would you reconfigure a server to serve HTTP traffic safely?
How does this solution fix the problem?



Explain the Solution Details

Which tools and technologies would you use to implement this solution in Project 1?
How, specifically, would you use these tools to harden your deployment?



Identify Advantages and Disadvantages of the Solution

Will your solution break clients that used to communicate with the server over port 80?
Do you have to do any work to keep this solution running longterm? Or can you simply "set it and forget it?”

# Theory Quetions 

## A) Docker Fundamentals 

**What is a Doker container, and how is it different from a virtual machine (VM) ?**

A: Container are packages of software that contian all of the necessary elements to run in any enviroment. In this way, containers virtualize the operating system and run anywhere. Virtual machines access the hardware of physcial machine through a hypervisor. The hypervisor create an abstraction layer allowing the VM to access CPU, memory and storage. Containers, on the other hand, represent a package that includes an executable with the dependencies it needs to run.


***
***What is the purpose of Dockerfile? Explain the significance of directives like FORM, COPY, RUN and CMD.***

A: Docker can build the images automatically by reading the instructions from a Dockerfile. A Docker file is a text document that contains all the commands a user could call
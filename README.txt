README:

This project was created for an assignment from the RES course at HEIG-VD engineering school, in Yverdon, Switzerland. The aim was to create a simple SMTP client that could send predefined emails randomly between a given list of email adresses. 

How to use it:

clone the repo and either:
- run the .jar program under out/artifacts, it takes 3 arguments: the number of groups you want to create, the smtp server and the port used.
- build and run it directly from your favorite IDE, you can do as much improvements as you like.

you should edit the emails.txt and texts.txt to set respectively the emails you want to make participate and the body of emails. Emails should be displayed 1 per line, texts should be separated by a line with only one dot. You can specify a subject by writing in the beginning: « subject: » + anything. For now, make sure to let one empty line after the subject.
 

If you don’t want to try it on a real SMTP server, you can use a mock server. It is a tool designed to behave as a server « talking » different protocols (here we used MockMock, a SMTP server with an HTTP interface) for testing purposes, so you can test the program without sending request to a real server.
To use MockMock, just download the .jar @ https://github.com/tweakers-dev/MockMock and follow the instructions to launch it. You will be able to send him emails which will be displayed on a webpage interface.

Enjoy! =)
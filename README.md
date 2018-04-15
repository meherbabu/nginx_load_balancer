This project setsup a load balancer using nginx. It uses the basic load balancer setup using round robin algorithm.

Application2 and Application3 are 2 REST APIs developed in spring boot projects. Application2 runs on 8081 and Application3 runs on 8082.

To start nginx load balancer:
      Go to nginx-1.12.2 and run the nginx.exe file.
      
Run the application using http://localhost:80. Run the application continuously. 
You can observe server1 and server2 as outputs alternatively.

server1 is returned as the Rest response from Application1
server2 is returned as the Rest response from  Application2

# Loadbalancing-over-aws-cloud-through-ansible

OBJECTIVE :
Main objective for doing this task is to use the concept of dynamic inventory so that we dont have to make manual inventory every time which will save our time .

Hello Guys welcome you all in this project I have integrated to tools ansible + aws cloud 
In this project I have done os provisioning through ansible over aws cloud means I have lauch 3 instances which will work as backend web server and 1 instance which will work as front end load balancer and in this project i have use the concept of dynamic inventory So for launching webserver instance over aws cloud file name is webserver_aws and for launching loadbalancer instance file name is loadbalancer_aws and after launching instances I have use the concept of roles for configuring haproxy and httpd in respective instances.

Haproxy is been configured in loadbalancer instance and httpd is been configured in webserver instance .

Tools used :
1) ANSIBLE
2) AWS CLOUD
 
--> This project solves the problem of making inventory manually

--> Through this project I learnt how to use blockinfile module of ansible and how to integrate ansible through aws cloud 


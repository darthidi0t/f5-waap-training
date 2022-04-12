F5 Distributed Cloud WAF 101
===================

`Last updated: 2022-01-19 2:00 AM ET`

F5’s  Distributed Cloud SaaS Web Application Firewall (WAF) can help you mitigate application threats 
with an updated WAF engine that inherits the shared  capabilities of F5 BIG-IP Advanced WAF, 
and NGINX App Protect. During this hands-on lab you will learn about the following: 

- F5’s Distributed Cloud Platform for providing edge WAF and DDoS protection  
- Updates to F5 Distributed Cloud’s WAF engine that is powered by F5’s WAF engine  
- Hands-on lab of deploying Distributed Cloud’s WAF   
- Protecting existing Public IP resource via F5’s hosted Distributed Cloud WAF    
- Deploying Distributed Cloud WAF into a cloud provider network (AWS) to protect internal Private IP resources via F5’s Volterra WAF  


Lab Environment
~~~~~~~~~~~~~~~

During this lab you will be using the shared Distributed Cloud Platform `f5-sales-public` tenant (the first lab exercise will 
cover how to access this environment).

The lab will also be using a AWS account where we have deployed the following resources.

- NGINX webserver that is exposed to the Public internet ("Public Endpoint")
- F5 Distributed Cloud Mesh node that can be used to connect to AWS VPC (network)
- NGINX webserver that only has a private IP address 

During the lab exercises we will explore different methods of protecting and exposing applications/webserver
that are included in the lab

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   lab1/index
   lab2/index
   lab3/index
   lab4/index
   lab5/index

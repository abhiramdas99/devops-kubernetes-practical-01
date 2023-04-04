# devops-kubernetes-practical-01
make the clustering of 3 nodes and create ngnix deployment of of 3 replica
--------------------------------------------------------------------------
Basic 
1) Own Security group, that allow all traffic from any destinatin to Ec2 machine 
2) Create 3 instance ( t2. mediaum / ubuntu latest ami) with common keypair
3) Attach instances with security group , that create in step 1
4) Rename all the machine as master, slave1 &  slave2 

Setup of master machine -
1) Access the master machine by putty or any other tools 
2) Take the administrative previlege  by  command : sudo su 
3) create a file install.sh and paste the  command from the below link and save it 
   Link - 



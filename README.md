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
3) change the host name by  command : hostnamectl set-hostname master   # for master its master , for slave 1 its savel1 like this . 
4) create a file install.sh and paste the  command from the link and save it 
   Link - <a target="_blank" href="https://raw.githubusercontent.com/abhiramdas99/devops-kubernetes-practical-01/main/master-node/install.sh">link </a>  
5) execute the file  the command is : bash install.sh 
6) do the same activities (1-4) all the 3 nodes 

7) do the cluster setup the command is : kubeadm init # this command will through the token  for all save1 and salve2
8) 



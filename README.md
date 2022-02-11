# Creating-an-Application-Load-Balancer-and-Auto-Scaling-Group-in-AWS
Creating an Application Load Balancer and Auto Scaling Group in AWS

#Install the stress

sudo su
yum -y update
amazon-linux-extras install epel -y

yum install stress -y

stress --cpu 8 --timeout 300s

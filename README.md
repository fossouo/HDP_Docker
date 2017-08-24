# HDP_Docker
This document will help you settings up HDP Cluster on a single machine using Docker

1. Prerequisites 

Live Operating System RedHat (7 or > 6.5)

2. Prepare my Docker Host 

Go to : http://continuum.io/downloads
Download according to your Python version 

$ bash Anaconda-latest-Linux-x86_64.sh
$ <Anaconda Path>/bin/pip install ansible==2.1.3.0
$ sudo yum install git -y 
(If not working then run : yum install epel-release -y before)
$ git clone https://github.com/objectrocket/ansible-hadoop.git

Referal : https://community.hortonworks.com/articles/87001/using-ansible-to-deply-hdp-on-aws.html

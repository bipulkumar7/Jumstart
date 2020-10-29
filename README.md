
Prequisite:
===========
	1. On aws account setup policy & rules for a user to do full permission  on ec2 instances
	2. Terraform installed locally.
	3. Create a Dash script locally to install Docker & Nginx i.e script.sh

After executing terraform following names are created:
=====================================================
VPC Name: Jumpstart Test
EC2 Instance: node0

Test:
======
1. Login to ssh and type docker on console
2. Use public DNS link in browser to test Nginx working or not.

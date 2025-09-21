1. Create a new Security Group, DO NOT USE DEFAULT
2. Create EC2 (EC2/Server/Instance/VM all mean the same thing)
	a. Create name and tag
	b. name the key pair name the same as the created name. Keep type as PEM (Key pair connects a user's computer to the AWS EC2 via secure shell)
	c. under network setting go to firewall and select existing security group
	d. under advance details go to user data. Add code
	e. Before launching instance double check your work
3. once instance was created copy public DNS, make it into a useable link, and paste the link
	a. Make sure to type HTTP://
4.In order to terminate instance
	a. click instance
	b. Select the instance that you wish to terminate
	c. click instance state
	d. click Terminate instance
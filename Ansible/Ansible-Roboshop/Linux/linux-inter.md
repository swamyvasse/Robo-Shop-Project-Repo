windows vs linux 
---------------------------------
less cost 
more performance
more stability 
free OS
security

Linux server ---> everything is text

flavour distributions
---------------------------

kernel + shell + utilities = Distributions

Ubuntu ----> community OS
centOs
Fedore
RHEL ----> Enterprise OS = you will get support
Suse
Arch linux


public key/private key mechanism

ssh --> secure shell protocol

protocol port-no IP-Address username password/privatekey

HTTP 80
MYSQL 3306
DNS 53
SMTP 25
tomact 8080


how to create public/private key-pair
-------------------------------------

ssh-keygen -f <file name>

how to connect linux server
---------------------------------

ssh -i devops.pem (path for publicpublic/private key-pair) username@Public-key

ssh -i devops.pem ec2-user@52.23.200.107

$ --> indicates normal user 
# --> indicates root user

# hyperledger

Commands that I used (mostly came from HyperLedger Lab Discussion postd on Canvas)

1) Created EC2 instance
2) connect to ec2 instance from ubuntu terminal
3) installed prereqs with given commands posted on Hyperledger lab discussion

---------launching network
 enter first-network directory
Generate the required certificates and articates for your first network

$ ./byfn.sh -m generate
To see the generate certificates use the following command:
$ cd crypto-config
$ ls
Create your first network using the following command
$ ./byfn.sh -m up
Check the generates images and running containers using the following command:
$ docker images
$ docker ps
To bring down the created network executed the following command
$ ./byfn.sh -m down
You can check the created images have been removed using the following:
$ docker images


![ubuntu hyperledge img1](https://user-images.githubusercontent.com/42783815/45504980-56246c00-b759-11e8-9bf1-b7b46aa1e6ee.PNG)
![ubuntu hyperledge img2](https://user-images.githubusercontent.com/42783815/45504988-59b7f300-b759-11e8-9eba-2da9b536e41d.PNG)
![ubuntu hyperledge img3](https://user-images.githubusercontent.com/42783815/45504990-5c1a4d00-b759-11e8-9e3c-c91bdcb0e7ad.PNG)

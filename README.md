# Simple-lamp


### php
* version 7.1
* apache included

### MySQL
* version 5.6

### phpMyAdmin
* version 4.5.3.1

## QuickStart
`$ git clone https://github.com/ShotaroHirota/lamp71-XD.git`

`$ cd lamp71-XD`  

`$ vim docker-compose.yml #replace the comment-out with IP`  

`$ docker-compose up -d`

`$ curl localhost #hello world from simple-lamp`  
# Setup  
for PhpStorm user
* Settings>Language&Framework>PHP>Debug>DGBp proxy  
IDEkey => ""  
Host => "{The IP of the machine running your IDE.}"  
Port => "9000"

 `$ docker-compose up -d` \# -d(daemon) is optional  

# Refference
* PhpStorm XDebug setting  
  https://gist.github.com/chadrien/c90927ec2d160ffea9c4


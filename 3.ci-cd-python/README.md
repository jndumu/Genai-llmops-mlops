sudo yum update -y
```
sudo yum -y install docker
```
#sudo amazon-linux-extras install docker
sudo service docker start
sudo systemctl start docker
sudo service docker status
sudo groupadd docker
sudo usermod -a -G docker ec2-user
newgrp docker
docker version

``` aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 533267397903.dkr.ecr.us-east-1.amazonaws.com
```





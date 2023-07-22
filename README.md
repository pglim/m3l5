# hello-node
aws ecr get-login-password --region ap-southeast-1 | docker login --username AWS --password-stdin 255945442255.dkr.ecr.ap-southeast-1.amazonaws.com

docker build -t asgn-3.5-pglim360 .

docker tag asgn-3.5-pglim360:latest 255945442255.dkr.ecr.ap-southeast-1.amazonaws.com/asgn-3.5-pglim360:latest

 docker push 255945442255.dkr.ecr.ap-southeast-1.amazonaws.com/asgn-3.5-pglim360:latest
 
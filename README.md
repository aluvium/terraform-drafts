# terraform drafts
### Idea
With purpose to create drafts for deploying automated environments IaaC mainly for AWS cloud and  Docker, using Terraform.
- - -
### Content
##### Docker :  
1. [__terraform-docker-nginx__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-docker-nginx) - Delpoying a container using the docker enviroment. Pulling img from docker hub.
2. [__terraform-docker-nginx-proxy__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-docker-nginx-proxy) - Two containter one with an app second as a proxy. Pulling from a docker hub.
3. [__terraform-docker-custom__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-docker-custom) - Applaying docker container using for e.g. docker inspect output as container resource.

##### AWS : 
1. [__terraform-ec2_local__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-aws-ec2_local) - Bare EC2 instance using local credentials.
2. [__terraform-ec2_cloud__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-aws-ec2_cloud) - Bare EC2 instance using credentials from cloud.
3. [__terraform-aws-vpc__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-aws-vpc) - VPC, EC2 instances - both took from terraform-aws-modules. Creds from cloud.
4. [__terraform-aws-static-web-s3__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-aws-static-web-s3) - VPC, EC2 instances - both took from terraform-aws-modules. Bucket S3 - own module. Creds from cloud.
5. [__terraform-aws-vpc-elb-sg-vars__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-aws-vpc-elb-sg-vars) - VPC, app_security_group, lb_security_group, elb_http, -  took from terraform-aws-modules. Own module ec2_instances. Resources - random_string. Local creeds.
6. [__terraform-aws-vpc-lb-ec2-db__](https://github.com/aluvium/terraform-drafts/tree/master/terraform-aws-vpc-lb-ec2-db) - VPC, app_security_group, lb_security_group, elb_http, aws_db_subnet_group, aws_db_instance -  took from terraform-aws-modules.Own module ec2_instances. Resources - random_string. Local creeds.🪓 Optimalized, automated variables.
- - - 
### Usage 
    git clone https://github.com/aluvium/terraform-drafts.git
    terraform init && terraform apply
### Contributions
https://learn.hashicorp.com

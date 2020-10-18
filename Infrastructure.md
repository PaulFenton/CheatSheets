### Docker

docker build -t <image-name> .\
docker images\
docker run -p 8080:8080 `<image-name>`\
docker containers ls\
docker kill `<container-id>`
  
#### Centos
RUN yum update -y
RUN yum install -y <package-name>

#### Debian
RUN apt-get update -y
RUN apt-get install -y <package-name>


### Terraform

terraform init\
terraform apply -auto-approve\
terraform destroy -force

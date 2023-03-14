provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "emre-olgun/docker-instance/aws"
    key_name = "key"
}
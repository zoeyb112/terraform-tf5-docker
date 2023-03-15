provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "<github-username>/docker-instance/aws"
    key_name = "clarusway"
}
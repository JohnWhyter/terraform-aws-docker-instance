```hcl

provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "JohnWhyter/docker-instance/aws"
    key_name = "key"
}
```
# Create main.tf and provide following:

```hcl
module "vpc" {
  source  = "aidynilyas/vpc/aws"
  version = "0.1.1"
  
  vpc_cidr = "10.0.0.0/16"
  subnet1_cidr = "10.0.1.0/24"
  subnet2_cidr = "10.0.2.0/24"
  environment = "dev"
}
```
# terraform-module-instance

```hcl

module "instance" {
  source  = "Bakyt65/instance/module"
  version = "2.0.0"
  instance_type = "t2.micro" # Replace with your value
  instance_name = "makusya" # Replace with your value
}

#!/bin/bash

sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2
sudo systemctl enable apache2

```

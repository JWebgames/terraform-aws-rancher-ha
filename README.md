# Terraform AWS ASG for RancherOS

![Hosted on AWS](https://img.shields.io/badge/Hosting-AWS-brightgreen.svg)
![Infrastructure as Code via Terraform](https://img.shields.io/badge/Infrasture%20as%20Code-Terraform-brightgreen.svg)

Based on work done by Chris Urwin and Ahmad Emneina located on [GitHub](https://github.com/chrisurwin/terraform-aws-rancher-ha) and Michael Laccetti located on [GitHub](https://github.com/mlaccetti/terraform-aws-rancher-ha)

This script will setup HA on AWS with SSL terminating on an ELB with an appropriately configured variable file.  It will also configure Route 53 to give the ELB a nicely resolvable URL.

This was developed so that it should be simple for someone to stand up a Rancher HA server and test its functionality.

It will create the appropriate security groups, ELB, RDS and EC2 instances.

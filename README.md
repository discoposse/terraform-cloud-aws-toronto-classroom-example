# terraform-cloud-aws-toronto-classroom-example

Shows how we can use and AMI with a web server that will spin up a web app with the following:

* ingress/egress rules in Security Group
* ALB (Application Load Balancer)
* target group with our EC2 instance added
* ACM certificate for TLS and dns
* Route53 for FQDN configuration to align with TLS certificate

# EC2
## Launch an EC2 Instance From Scratch(04/09/2025)
Launched an EC2(`t2.micro`) without key-pair(it is a bad practice for security reason). Make sure to attach Security Group that allows inbound/outbound traffic for ssh and http(s)

## Create AMI from EC2(04/09/2025)

## Launch an EC2 Instance From AMI(04/09/2025)
The boot time was a lot faster. It is because the instance does not need to boot up from the beginning

## Delete EC2 Instances and AMI(04/09/2025)
Make sure to delete them to prevent billing. Make sure to delete `EBS Snapshot` as well since it must be deleted separately

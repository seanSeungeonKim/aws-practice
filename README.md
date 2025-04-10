# EC2

## 04/09/2025
### Launch an EC2 Instance From Scratch
Launched an EC2(`t2.micro`) without key-pair(it is a bad practice for security reason). Make sure to attach Security Group that allows inbound/outbound traffic for ssh and http(s)

### Create AMI from EC2

### Launch an EC2 Instance From AMI
The boot time was a lot faster. It is because the instance does not need to boot up from the beginning

### Delete EC2 Instances and AMI
Make sure to delete them to prevent billing. Make sure to delete `EBS Snapshot` as well since it must be deleted separately

## 04/10/2025
### ENI and Elastic IP
Created an Elastic IP and associated it with EC2 instance.

Finding: Public IP address in EC2 instance did NOT change even after it is stopped


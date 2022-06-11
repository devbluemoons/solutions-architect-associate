# solutions-architect-associate
AWS Certified Solutions Architect – Associate  
  
## common
- [x] Region
  - [x] AZ
- [x] REST API
- [x] HTTP / HTTPS 
- [x] AWS CLI
```ShellSession
# install
pip install awscli --upgrade --user

aws --version
```
  
## Storage
- Object Storage
  - S3 (simple storage service)
    - [ ] bucket
    - [ ] load balancers
    - [ ] web servers
    - [ ] web hosting
    - [ ] indexing
    - [ ] storage
    - [ ] read after write consistent
    - [ ] partitioning
    - [ ] encryption
      - [ ] SSE-SE
      - [ ] SSE-C
      - [ ] SSE-KMS
    - [ ] access control
      - [ ] IAM policy
      - [ ] bucket policy
      - [ ] ACL policy
    - [ ] storage class
      - [ ] standard
      - [ ] standard IA
      - [ ] RRS
      - [ ] One Zone IA
      - [ ] glacier
        - [ ] vault
        - [ ] standard
        - [ ] expedited
        - [ ] bulk
    - [ ] object versioning
    - [ ] object lifecycle
    - [ ] copy cross region
    - [ ] select
- Block storage
  - EBS (elastic block store)
    - [ ] EC2 instance store
    - [ ] SSD
    - [ ] IOPS SSD
    - [ ] HDD
- File storage
  - EFS (elastic file system)
- on-premise storage
  - [ ] SGW (storage gateway)
    - [ ] file gateway
    - [ ] volume gateway
    - [ ] tape gateway
- import / export tool
  - [ ] snowball
  - [ ] snowball edge
  - [ ] snowball mobile

## Network
- VPC (virtual private cloud)
  - [ ] CIDR
  - [x] subnet
  - [x] AZ (availability zone)
  - [ ] gateway
    - [ ] internet gateway
  - [ ] router
    - [ ] routing
    - [ ] routing table
  - [ ] virtual firewall 
    - [ ] security group
      - [ ] stateful
      - [ ] stateless
    - [ ] network ACL 
  - [ ] network class
    - [ ] A class
    - [ ] B class
    - [ ] C class
  - [ ] DHCP (dynamic host configuration protocol)
  - [x] IP address (destination / host)
    - [x] public IP
    - [x] private IP
  - [ ] IP masquerade
  - [ ] global accelerator
  - [ ] NAT (network address translation)
    - [ ] NAT device
    - [ ] NAT gateway (for IPv4)
    - [ ] egress-only gateway (for IPv6)
  - [ ] traffic
    - [ ] in-bound
    - [ ] out-bound
    - [ ] port
  - [ ] endpoint
    - [ ] interface endpoint
    - [ ] gateway endpoint
  - [ ] peering
  - [ ] transit gateway
  - [ ] ENI (elastic network interface)
  - [ ] EIP (elastic IP)
  - [ ] NACL (network access control list)
  - [ ] VPG (virtual private gateway)
  - [ ] Flow Log
- VPN
- Direct Connect

## Computing
- EC2 (elastic compute cloud)
  - [x] SSH
  - [ ] AMI (amazon machine image)
    - [ ] OS
    - [ ] software
  - [ ] instance
    - [ ] CPU
    - [ ] memory
    - [ ] storage
      - [ ] EBS (elastic block store)
        - [ ] snapshot
      - [ ] EFS (elastic file system)
    - [ ] network
      - [ ] subnet
      - [ ] ip address
  - [ ] security group
  - [ ] key pair
    - [ ] public key
    - [ ] private key
  - [ ] ELB (elastic load balancing)
    - [ ] ALB (application load balancer)
    - [ ] NLB (network load balancer)
    - [ ] OLB (classic load balancer)
  - [ ] Auto Scaling

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

# version check
aws --version
```

## Computing
- EC2 (elastic compute cloud)
  - [ ] AMI (amazon machine image)
    - [ ] quick start AMI
    - [ ] market place AMI
    - [ ] community AMI
    - [ ] private AMI
  - [ ] instance type
    - [ ] general purpose
    - [ ] compute optimized
    - [ ] memory optimized
    - [ ] accelerated computing
    - [ ] storage optimized
  - [ ] VPC (virtual private cloud)
  - [ ] tenancy
    - [ ] shared tenancy
    - [ ] dedicated instance
    - [ ] dedicated host
  - [ ] placement groups
    - [ ] cluster
    - [ ] spread
    - [ ] partition
  - [ ] instance purchasing options
    - [ ] on-demand
    - [ ] reserved
    - [ ] spot
  - [ ] lifecycle
  - [ ] resource tag
  - [ ] storage volume
    - [ ] EBS (elastic block store)
      - [ ] general purpose SSD
      - [ ] provisioned IOPS SSD
      - [ ] throughput optimized HDD
      - [ ] cold HDD
    - [ ] instance store volume
  - [ ] security
    - [ ] security group
    - [ ] NACL (network access control list)
  - [ ] IAM role
  - [ ] NAT (network address transition) device
    - [ ] NAT instance
    - [ ] NAT gateway
  - [ ] key pair
  - [ ] auto scaling
    - [ ] launch configurations
    - [ ] launch template
    - [ ] auto scaling group
      - [ ] minimum
      - [ ] maximum
      - [ ] desired capacity
      - [ ] ALB (application load balancer)
      - [ ] health check
      - [ ] options
        - [ ] manual scaling
        - [ ] dynamic scaling policies
        - [ ] simple scaling policies
        - [ ] step scaling policies
        - [ ] target tracking policies
        - [ ] schedulted actions
  - [ ] system manager
    - [ ] actions
      - [ ] automation
      - [ ] command
      - [ ] policy
    - [ ] insights

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
      - [ ] intelligent tiering
      - [ ] infrequent access
      - [ ] RRS (reduced redundancy storage)
      - [ ] One Zone IA
      - [ ] glacier
        - [ ] vault
        - [ ] standard
        - [ ] expedited
        - [ ] bulk
      - [ ] glacier deep archive
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

## Database
- RDS (relational database service)
  - [ ] instance
    - [ ] VPC (virtual private cloud)
    - [ ] not allow ssh
    - [ ] not allow direct connection from EC2
    - [ ] type
      - [ ] standard
  - [ ] engine
    - [ ] Amazon Aurora
    - [ ] PostgreSQL
    - [ ] MySQL
    - [ ] MariaDB
    - [ ] Oracle Database
    - [ ] Microsoft SQL Server
- Redshift
- DynamoDB

## Identity and Access Management

## Monitoring
- [ ] CloudTrail
- [ ] CloudWatch
- [ ] Config

## DNS / Network Routing
- [ ] DNS (domain name system)
- [ ] Route 53
- [ ] CloudFront

## Automating
- [ ] SQS
- [ ] Kinesis
  - [ ] Video Streams
  - [ ] Data Streams
  - [ ] Data Firehose

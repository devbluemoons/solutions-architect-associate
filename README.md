# solutions-architect-associate
AWS Certified Solutions Architect – Associate  
  
## common
- [ ] Region
  - [ ] AZ
- [x] REST API
- [ ] HTTP / HTTPS 
- [ ] AWS CLI
```sh
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
- VPC
  - [ ] CIDR
  - [ ] subnet
  - [ ] availability zone
  - [ ] gateway
    - [ ] internet gateway
  - [ ] router
    - [ ] routing
    - [ ] routing table
  - [ ] virtual firewall 
    - [ ] security group
    - [ ] network ACL 
  - [ ] network class
    - [ ] A class
    - [ ] B class
    - [ ] C class
  - [ ] DHCP
  - [ ] IP address (destination / host)
    - [ ] public IP
    - [ ] private IP
  - [ ] IP masquerade
  - [ ] NAT
    - [ ] NAT gateway
  - [ ] traffic
    - [ ] in-bound
    - [ ] out-bound
    - [ ] port
  - [ ] endpoint
    - [ ] interface endpoint
    - [ ] gateway endpoint
  - [ ] peering
  - [ ] transit gateway
- VPN
- Direct Connect

## Computing
- [ ] EC2

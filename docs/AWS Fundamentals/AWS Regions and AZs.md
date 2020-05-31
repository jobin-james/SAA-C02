## AWS Regions and AZs

## AWS Regions
- AWS has regions all around the world, And each region is named. eg: `us-east-1.`
- Each AWS Region consists of multiple, isolated, and physically separate AZ's within a geographic area
- Most of the aws services are region-scoped. Eg: AMI ids are region -scoped, means AMI ids are different in different aws regions.
- AWS now spans 76 Availability Zones within 24 geographic regions around the world, and has announced plans for nine more Availability Zones and three more AWS Regions in Indonesia, Japan, and Spain.

[AWS Global infrastructure Documentation](https://aws.amazon.com/about-aws/global-infrastructure/)

![map](https://d1.awsstatic.com/about-aws/Global%20Infrastructure/Global-Infrastructure-Map_Networks_1.01c9ef0f300ef42e91e7faa3eacbfceb52c87191.png)

## AWS Availability Zones

* Each region has many availability zones. Normally 3, but always a minimum of 2 and max of 6.
    1. `us-east-1a`
    2. `us-east-1b`
    3.` us-east-1c `
* An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region.
* AZs are together connected with high bandwidth ultra-low latency networking.
* AZ’s give customers the ability to operate production applications and databases that are more highly available, fault tolerant, and scalable than would be possible from a single data center.
* All traffic between AZ’s is encrypted.
# aws-vpc-aem

A basic AWS Cloud Formation Script that can be used to build out a VPC for hosting Adobe AEM.

The VPC separates out the different AEM instances using dedicated subnets, with an Elastic Load balancer to distribute traffic across separate availability zones within a single region. 

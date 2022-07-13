Ec2 Basic - The cloudformation template creates an Ec2 instance in the subnet, AZ of your choice and with Key, Sec group, Name, Type that you choose in parameters.
Ec2WithSG - The template creates Ec2 instance and security group in the subnet, AZ of your choice and with Key, Name, Type that you choose in parameters
Ec2withRootVolume - The template creates Ec2 instance and security group in the subnet, AZ of your choice and with Key, Name, Type that you choose in parameters. If you choose
                    production a custom root volume is created and if Dev is chosen the default root volume of AMI is created.
Ec2WithEbsVolumes - The template creates Ec2 instance and security group in the subnet, AZ of your choice and with Key, Name, Type that you choose in parameters
	              If you choose Ddrive and Edrive a custom D and E drive are created and attached to the instance and if you choose nothing they are not created.

Ec2StopSNS - Create an eventbridge rule and SNS topic with access policy to send notification when Ec2 stops.
VpcEndpoints_SSM - Creates 3 VPC endpoint services for your private ev2 instances to connect to SSM agent and come under fleet manager.

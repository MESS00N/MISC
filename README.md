# MISC

aws ec2 describe-subnets --subnet-ids $(aws eks describe-cluster --name <cluster-name> --query "cluster.resourcesVpcConfig.subnetIds" --output text) --query "Subnets[*].AvailabilityZone" --output text


Invalid choice: 'text)', maybe you meant:

  * text

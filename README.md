# MISC

aws ec2 describe-subnets --subnet-ids $(aws eks describe-cluster --name <cluster-name> --query "cluster.resourcesVpcConfig.subnetIds" --output text) --query "Subnets[*].AvailabilityZone" --output text


usage: aws [options] <command> <subcommand> [<subcommand> ...] [parameters]
To see help text, you can run:

  aws help
  aws <command> help
  aws <command> <subcommand> help

aws: error: argument --output: Invalid choice, valid choices are:

json                                     | text
table                                    | yaml
yaml-stream


Invalid choice: 'json)', maybe you meant:

  * json



What experience does the SRE candidate have with automation and toil reduction?  Please provide examples.
What experience does the SRE candidate have with resilient infrastructure and/or application design?
Provide examples of the SRE candidate’s development experience.

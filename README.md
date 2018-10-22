# Sparta AWS Instances

1) When logged in, click the services in the AWS navbar and click the EC2 link.
2) Press the launch instance button.
3) Select desired Amazon Machine Image (AMI), ensuring that it is a free tier.
4) Select the free tier instance Type and click the Next button.
5) Click the next button.
6) Click the next button again.
7) Add tage to your instance (e.g Key=name, value=David), when done click next.
8) Select the existing group radio button, and select the launch-wizard-1 security group and click review and launch
9) Click the launch button
10) Click the running instances link
11) select your desired running instance and copy the public DNS(IPv4).
12) Ask your supervisor for the Amazon Private Key
13) in the running instances page, click the connect button and follow the steps shown, changing the final command to the file location of the Amazon private key file
14) you are now in the instance SSH terminal

# DeathWishCoffee2
# Building an EC2 Instance in AWS
## Prerequisites

- An AWS account
- Basic understanding of the [AWS console](https://aws.amazon.com/console/)
- Visual Studio Code [VSC](https://code.visualstudio.com/) (Windows)

- ## Step 1: Choose an Amazon Machine Image (AMI)

1. Open the [AWS Management Console](https://aws.amazon.com/console/) and navigate to the EC2 service.
2. Click on **Launch Instance**.
3. Select an AMI from the list based on your requirements. For this guide, we'll use the [Amazon Linux 2 AMI](https://aws.amazon.com/amazon-linux-2/).

## Step 2: Configure the Instance
Configure the following settings for your EC2 instance:

- ***Instance Type:*** Determine the CPU, memory, and storage resources for your workload.
- **Network Settings:** Specify the subnet and security group for your instance.
- **Key Pair:** Create or use an existing key pair for SSH authentication.
- **To connect using SSH:**
```bash
ssh -i <key_pair>.pem <user>@<public_ip>
```
## Useful Documents:

- [AWS EC2 User Guide](https://docs.aws.amazon.com/ec2/)
- [AWS EC2 Launch Instance Wizard](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/launching-instance.html)
- [AWS Documentation](https://docs.aws.amazon.com/)

- ![image](https://github.com/ArchAndrew/Test/assets/125866011/2ec72ce4-3644-4587-a4f5-d3b3fcd11582)

![ghtest1png](https://github.com/ArchAndrew/Test/assets/125866011/b3bcd586-98ae-4785-bdb2-84dd2513a54e)

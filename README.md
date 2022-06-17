# Project 2: Deploy a high-availability web app using CloudFormation

### Dependencies

##### 1. AWS account

You would require to have an AWS account to be able to build cloud infrastructure
##### 2. VS code editor or editor of your choice

An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download)

### How to run the cloudformation scripts

You can run the scripts in two easy steps:

```bash
# For linux users, give the scripts appropriate permissions
chmod +x ./create.sh
chmod +x ./update.sh
# Ensure that the AWS CLI is configured before running the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh network-infra network-infra.yml network-params.json
# Create servers
# Change the AMI ID in the server-infra.yml
# Check the region in the update.sh file
./create.sh servers server-infra.yml server-params.json
```

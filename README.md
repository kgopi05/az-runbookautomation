# az-runbookautomation
Setup for Azure Runbook Automation for VM

# Overview  

This Azure Terraform repository will provision below resources

1. VPN & Subnet
2. VM and Disks
3. NSG
4. VM Extensions

## How to Provision the Azure services using this Repo
1. Connect to Azure using your preferred method (az login CLI )
2. Connect to Subscription (az account set -s <Subscriptionid>)
3. Run the pre-request.sh script
4. Copy the access_key of the Storage account and update in the environment/state.tf file
5. Navigate the environment directory (dev) and execute the terraform plan.

## Additional info :

1. This repository having Runbook automation codes and disk encryption scripts (testing phase)

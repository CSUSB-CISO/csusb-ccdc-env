## FIXME

# -- Instruction -- 

**Pre-requisite**
Install Terraform 
> https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

1. Clone repository
`git clone https://github.com/CSUSB-CISO/csusb-ccdc-env.git`
2. Set variables
```
export TF_VAR_VIRTUAL_ENVIRONMENT_ENDPOINT="https://YOUR_ENDPOINT:8006"
export TF_VAR_PROXMOX_VE_API_TOKEN='YOUR_API_TOKEN'
```
3. Change into desired environment and create environment
```
cd terraform/moon.mine
terraform apply --auto-approve
```

**Note**: You might need to adjust the VMID numbers respective to your environment


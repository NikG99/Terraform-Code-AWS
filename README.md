Deployment Steps
Save the Terraform code in a file (e.g., wsus_registry_update.tf).
Initialize Terraform:
bash
Copy code
terraform init
Validate the configuration:
bash
Copy code
terraform validate
Apply the configuration:
bash
Copy code
terraform apply
Confirm the changes when prompted.
Post-Deployment
Use the AWS Management Console or AWS CLI to verify the success of the SSM command.
Ensure the EnableCertPaddingCheck registry key is correctly updated on the EC2 instance.

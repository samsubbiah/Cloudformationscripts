# Cloudformationscripts

stack_using_ssm_parameter_store.yaml - Create a single EC2 Instance whose Instance Type and AMI id comes from SSM Parameter store. Advantage is , we can change the parameter and update Cloudformation stack . Assume An organization has 10 different stacks all uses same Linux Image . If the image changes , updating the parameter store and updating stack will pick up the new AMI. No need to change the 10 cloud formation stacks.

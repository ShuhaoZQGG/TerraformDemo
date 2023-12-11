# Setting Input Variables
# In Order of precedence (Lowest => Highest)

- Manual entry during plan/apply
- Default value in declaration bloc
- TF_VAR_<name> environment variables
- terraform.tfvars file
- *.auto.tfvars file
- Command line -var or -var-file
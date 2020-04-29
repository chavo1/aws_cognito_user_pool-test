# Cognito User Pool example

- This is based on following example:

https://github.com/terraform-providers/terraform-provider-aws/tree/master/examples/cognito-user-pool

- The example creates a Cognito User Pool, IAM roles and lambdas.

### Running the example

```
git clone https://github.com/chavo1/aws_cognito_user_pool-test.git
cd aws_cognito_user_pool-test
terraform init
terraform plan
terraform apply
```
### Don't forget to destroy
```
terraform destroy 
```
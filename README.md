### Terraform State Bootstrapping

Remote state resources (S3 bucket and DynamoDB lock table)
are provisioned via a one-time bootstrap Terraform stack.
These resources are shared, long-lived, and managed separately
from application infrastructure.
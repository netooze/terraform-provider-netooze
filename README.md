Terraform Provider Netooze
Run the following command to build the provider

go build -o terraform-provider-netooze
Test sample configuration
First, build and install the provider.

make install
Then, run the following command to initialize the workspace and apply the sample configuration.

cd example
terraform init && terraform apply

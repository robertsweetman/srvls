# srvls

This is a scaffolding example project to show the following:
 - deploying terraform to AWS via Github Actions
 - deploying lambda functions using Terraform
 - creating lambda functions in Rust


## Deployment

Running from local machine at the moment, create two environment variables:

`$env:AWS_ACCESS_KEY_ID=`
`$env:AWS_SECRET_ACCESS_KEY=`

Then run the usual `terraform init\plan\apply` and go from there.

## ToDo

1. Github action to run terraform apply
2. Set-Output warning in existing plan needs to be killed by supplying this to 'apply' properly
3. Create a very basic set of terraform resources to deploy something
4. Create a very basic 'hello world' lambda function in Rust & deploy it -> Website? Url?
5. Look into how to create tests for this
6. Write up troubleshooting steps, debug goes where?
7. Monitoring
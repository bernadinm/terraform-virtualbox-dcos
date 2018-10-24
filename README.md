# terraform-virtualbox-dcos [WIP]
_Used to install DC/OS locally us_

## Prerequisites
- Go
- Terraform

## Installation

```
go get github.com/terra-farm/terraform-provider-virtualbox
go build github.com/terra-farm/terraform-provider-virtualbox
cp $GOPATH/src/github.com/terra-farm/terraform-provider-virtualbox/terraform-provider-virtualbox .
```

## Deploy

```
terraform init
terraform apply
```

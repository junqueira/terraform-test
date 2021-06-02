# terraform-example

[![Build Status](https://travis-ci.org/junqueira/terraform-test.svg?branch=master)](https://travis-ci.org/junqueira/terraform-test)

-> test sample exemples
    https://github.com/terraform-providers/terraform-provider-aws/tree/master/examples/lambda


## Standard

```
└── terraform-lambda
    ├── hello_lambda.py
    ├── iam.tf
    ├── lambda.tf
    ├── outputs.tf
    └── vars.tf
```

## With Module

```
└── terraform-lambda-as-module
    ├── main.tf
    ├── modules
    │   └── lambda
    │       ├── function
    │       │   ├── hello_lambda.py
    │       └── lambda.tf
    ├── provider.tf
    └── vars.tf
```

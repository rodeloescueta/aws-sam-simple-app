# A simple backend with a RESTful API endpoint using Amazon API Gateway

> #### You must have aws cli installed and configured

* Create s3 bucket `aws s3 mb s3://<your-bucket-name>`
* Packaged _template.yml_ file `aws cloudformation package --template-file template.yml --s3-bucket <your-bucket-name> --output-template-file packaged-template.yaml`  __it will create _packaged-template.yaml_ file__
* Deploy to AWS cloudformation `aws cloudformation deploy --template-file packaged-template.yaml --stack-name <your-cfm-name> --capabilities CAPABILITY_IAM`

It should show something like this.

```
Waiting for changeset to be created..
Waiting for stack create/update to complete
Successfully created/updated stack - delo-sam-basic-project
```




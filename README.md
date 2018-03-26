Run templates from the command line

```
aws cloudformation create-stack --template-body file://templates/template_name.cft --stack-name single-instance --parameters ParameterKey=KeyName,ParameterValue=tutorial ParameterKey=InstanceType,ParameterValue=t2.micro
```

Run templates from the command line

```
aws cloudformation create-stack --template-body file://templates/single-instance.yml --stack-name single-instance --parameters ParameterKey=KeyName,ParameterValue=tutorial ParameterKey=InstanceType,ParameterValue=t2.micro
```

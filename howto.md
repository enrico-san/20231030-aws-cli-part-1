### install aws cli
```bash
pip3 install awscli --upgrade --user

aws configure  # insert access key and secret, region = eu-west-1 and type = json
```

### describe resources
```bash
aws ec2 describe-instances
aws memorydb describe-clusters --output table
```
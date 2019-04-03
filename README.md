# aws-ssm-patch-list-export
AWS SSM service gives provision to run a patch baseline on the EC2 instances, but doesnt give provision to export the list of patches. This blog will guide you how to get the patch exported.


```
aws ec2 describe-instances --filter "Name=tag-key,Values=patch"
```

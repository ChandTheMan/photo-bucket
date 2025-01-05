# photo-bucket
A static site to see some photos?

Some cmds:

aws cloudformation validate-template --template-body file://s3-test.yaml
aws cloudformation create-stack --stack-name my-s3-bucket-stack --template-body file://s3-test.yaml --capabilities CAPABILITY_NAMED_IAM
aws cloudformation delete-stack --stack-name my-s3-bucket-stack

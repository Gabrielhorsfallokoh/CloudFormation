# To create a stack
aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network-infra.yaml --parameters file://dev-parameter.json

# To delete a stack
aws cloudformation delete-stack \
    --stack-name dev-network-infra-pf
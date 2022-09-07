pipeline
{
stages {
stage ("submit Stack")
{
steps {
sh “aws cloudformation create-stack \
    --stack-name s3bucket \
    --template-body file:///simplests3cft.json \
    --region ‘us-east-1' \
    "
    }
}
}

pipeline
{
stages {
stage ("submit Stack")
    {
steps {
    sh “aws cloudformation create-stack --stack-name myteststack --template-body file:///lambda.yaml --region ‘us-east-1'"
        }
    }
}
}

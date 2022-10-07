pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name sample --template-body file://lambda.yaml --region 'us-east-1'"
              }
             }
            }
            }

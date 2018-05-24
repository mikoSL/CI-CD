# AWS DevOps Essentials : An introductory workshop on CI/CD practices
* From https://github.com/awslabs/aws-devops-essential

* AWS CodeCommit (store code in private git repo)
* AWS CodeBuild (fully managed build service)
* AWS CodePipeline (fully managed continuous delivery service)
* AWS CodeDeploy (automated application deployment service)
* Jenkins (open source automated build server)
* AWS Cloud9 (cloud-based integrated integrated development environment IDE)

## Lab1 Build project on the cloud
* Setup AWS Cloud9 IDE.
* Create a AWS CodeCommit Repository.
* Clone the Repo to Cloud9.
* Commit changes to Remote Repo in CodeCommit.
* Prepare Build Service (create project in CodeBuild).
* Build the code on cloud (using CodeBuild).

## Lab2 Automate deployment for testing
* Prepare environment for testing (create VPC, IGW, route tables, ACL, EC2 instances)
* Create CodeDeploy application and deployment group.
* Prepare application for deployment (appspec.yml & update buildspec.yml).
* Deploy an application revision.

## Lab3 Setup CI/CD using AWS CodePipeline
* Create a pipeline.
* Create CodeDeploy deployment group for production.
* Edit a pipeline (add stages).
* Add manual approval action.
* Approve or reject an approval action in CodePipeline.

## Lab4 Using Lambda as test stage in CodePipeline
* Create a sample Lambda function.
* Add the Lambda function to a pipeline in CodePipeline.
* Test the pipeline with the Lambda function.

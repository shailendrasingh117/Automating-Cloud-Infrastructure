# Automating-Cloud-Infrastructure
This project demonstrates how to automate the deployment of AWS resources using AWS CloudFormation and GitHub. The project includes a CloudFormation template and a deployment pipeline that automatically deploys the template when changes are pushed to the GitHub repository.
# Prerequisites
Before you can deploy this project, you need to have the following prerequisites:

1. An AWS account with the necessary permissions to create AWS resources
2. The AWS CLI installed on your local machine
3. A GitHub account with a repository to store the CloudFormation template and deployment pipeline code
4. The AWS CodePipeline GitHub App installed on your GitHub account
# Deployment Steps
1. To deploy this project, follow these steps:

2. Clone this repository to your local machine:<br>
 $ git clone https://github.com/<your-github-username>/cloudformation-automation.git

3. Modify the CloudFormation template ('template.yaml') to suit your needs.<br> 
This template creates an Amazon S3 bucket and an Amazon DynamoDB table.

4. Commit and push your changes to the GitHub repository:<br>
$ git add template.yaml<br>
$ git commit -m "Update CloudFormation template"<br>
$ git push<br>
5. Wait for the AWS CodePipeline deployment to complete. This will automatically create the CloudFormation stack based on the updated template.

6. Verify that the resources were created as expected by checking the AWS Management Console or using the AWS CLI.
# Conclusion
This project demonstrates how to automate the deployment of AWS resources using AWS CloudFormation and GitHub. 
By following the steps above, you can easily modify and deploy your own CloudFormation templates using GitHub and AWS CodePipeline.

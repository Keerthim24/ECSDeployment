Created a Repository in Github and created a sourcecode for AWS Code Pipeline
Created a stack in AWS Cloud Formation and uploaded the template(sourcefile)
Specified the task details,configured stack options and acknowledged.
codepipeline is created in AWS and github source is given
Released the changes every times when the code is changed in git repo
Crosschecked the git tokens changes and checked whether the connectivity from git repo to AWS is working or not
4 stages are created through github repo sourcefile with manual approvals
Task:2 In Terraform Cloud account workspaces are created,environment and Terraform variables are defined
Working directory is defined
Two other workspaces for staging and production is created.
Git Workflow:Necessary keys AWS Access Key Id, AWS Secret Access Key, AWS Region,Terraform API key tokens are added to GitHub repo
Infrastructure is deployed 
Building and deploying the API by configuring AWS Credentials.Build, tag, and push the image to Amazon ECR
Implement a quick dummy feature in a feature branch (e.g. feature/dummy).
Do a pull request in dev.
Merge dev to staging and eventually master

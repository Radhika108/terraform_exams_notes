10 Min - Revision notes for Terraform Associate Exam.
Terraform visitor badge-2

This repo is a collection of study note prepard to use it for revission before the exam.



Study materials	Links
	LINK
A Free Course Developed by Andrew Brown from ExamPro
	LINK
	LINK
Click on each topic below to expand the content
What is IAC ? Understanding Infrastructure As Code.
IAC
What Is IAC? Understanding Infrastructure As Code
Deploy your infrastucture resources with code.
It enables DevOps, version control, better collabration
Declarative - code in a readable format not worring about api
speed, cost , reduced risk
below code is an example for IAC, thi is a code to get current VPCs from AWS environment

example

Terraform
Terrform is declarative
Codify your Software defined networking
all cloud IAC solution (AWS,GCP,Azure) , cloud agnostic
check out all providers for terraform, LINK
Terraform Work Flow, IaC with Terraform.
Terraform Work Flow
Write -> Plan -> Deploy

Write the code, plan and review the code & once you are happy Apply to deploy the resources.

terraform init
it initialize the directory
which means it will add modules and plugins.
setup up backend
Terraform plan , terraform apply & terrraform destroy.
PLAN
terraform plan

it allow the users to review the code
helps to understand what are you deploying
your Auth keys are used only if needed
APPLY
terrform apply

deploy the code , create resources in your cloud
updates the statefile, terraform.tfstate
tfstate can store in local and remote
DESTROY
terraform destroy

destroy all your resources from cloud acording to the config file, that you created using code.
Provider Block, resource Block and data block.
Terraform installation and Providers.
Terraform State.
Terraform variables & outputs.
Terraform Provisioners.
Terraform state file.
Terraform local and remote state files.
Terraform Modules.
Terraform input and output modules.
Build in functions.
Type constraints.
Dynamic Blocks.
Terraform fmt, taint, import.
Terraform Workspace.
Debugging.
terraform fmt, terraform taint, terraform import.
Terraform Cloud and Enterprise.
Sentinal
Policy as code
Has its own laungage
Version control
Testing and Automation
ex :- enforce CIS Security standards
Vault
Secrets Management Software
Pass temparory creds
terrform Registry
Modules are stored in registry
Publically accessable
Anyone can contribute to Registry
Cloud Workspaces
workspaces hold in cloud rather than in local
records activity
Can trigger via github actions
OSS and Terraform Cloud workspace
OSS
Create statefile locally
Variables are stored in.tfvars file
creds are stord locally
Cloud
Version control
communicated via API/CLi
State files stored in Cloud
variables are stored in cloud work space
creds are stord in cloud
Benifits of Terraform Cloud
remote execution
workspace on org model
version control
manage remotely
Private registry avilable to host privately
cost estimation
policy as code with sentinal
More Useful links
Terraform Best Practices - Link
250 Practice Questions For Terraform Associate Certification - Link

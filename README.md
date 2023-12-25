# django-fargate
To deploy it, follow these steps:
1- Create a service on AWS ECR. make sure the service uses the task mentioned in the DjangoFargateTask-AWS.CLI.json.
2- Use the servicename created in the aws.yml ECS_SERVICE.
3- Update the image tag in the DjangoFargateTask-AWS.CLI.json
4- update the imagetag in the aws.yml
5- commit and push the code to github.

*note that the cpuArchitecture for the image that is built in github is X86_64 while the image build on the Mac chip M3 is ARM.
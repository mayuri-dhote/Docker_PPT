# Docker_PPT

Create a Jenkins pipeline to deploy application present at: https://github.com/knoldus/node-hello
Required command to run the application and the ports being used are present in the Github repository.
The application should be containerized and should be running on docker.
The image has to be pushed on DockerHub and should be pulled for running.
The ports of the application should be open for communication and accept connection on the host machine.
Use any type of Jenkins project.
Implement use of Global Tools Configuration to use NodeJS effectively
Requirements:
Jenkins should be set up on a Cloud Virtual Machine and not from the local system
Any commits to the ‘main’ branch should trigger the job on Jenkins and start the build process
Use Github webhooks to trigger builds
The first part of the Jenkins job should be creating the package
The second part of the Jenkins job will be to send the package to another VM and run it there
The validations can be performed by hitting endpoints: <VM_IP>:3000 or <VM_IP>:3001



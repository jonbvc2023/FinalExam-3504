# FinalExam-3504 - https://github.com/jonbvc2023/FinalExam-3504

Design and Develop a Simple Website:
• Reuse the source code from the project

2. Set Up GitHub Repository:
• Create a new public GitHub repository to host your website's source code
name it as an upgrade/final exam or any name of your choice
  create your github repository
    https://github.com/jonbvc2023/FinalExam-3504
   
4. Version Control with Git:
• Ini,alize the Git repository in your project directory.
  clone your github git clone https://github.com/your-username/repository-name.git
  Navigate to the local repository on your machine - cd repository-name
  Run the following command to initialize a Git repository in your project directory - git init
  Use the git add command to stage the changes for the next commit. You can stage specific files or use a wildcard (.) to stage all changes - git add .
  Commit the changes with a meaningful commit message - git commit -m "Your descriptive commit message here"
  Finally, push your changes to the GitHub repository - git push origin branch-name




6. Set Up AWS Account and EC2 Instance:
• Create an AWS account if you don't have one.
   launch an instance
   make sure you create a new keypair using .ppk
   allow or enable SSH, HTTP, HTTPS
   

5. Install Necessary So`ware on EC2 Instance:
• SSH into the EC2 instance and install required so`ware, such as Apache web
server and Git.
  sudo yum updatE
  sudo yum update    # For Amazon Linux or CentOS
  sudo yum install httpd    # For Amazon Linux or CentOS
  sudo yum install git

7. Implement CI/CD with GitHub Ac,ons:
   create a simple workflow to trigger the CIéCD process
   
• Configure the workflow to run whenever changes are pushed to the main
branch.
• The CI/CD process should automa,cally deploy the latest changes to the EC2
instance.

9. Dockerize the Website:
  Create a new directory for your project
  Create a file named app.js with the following content
  Create a package.json file with the following content
  Install dependencies
  Create a file named Dockerfile (without any file extension) in the project root
  Open a terminal, navigate to the project directory, and run the following command to build the Docker image
  Replace your-website-image-name with a suitable name for your Docker image - docker build -t your-website-image-name .
  Once the image is built, run a container using the following command - docker run -p 3000:3000 -d your-website-image-name

11. Deploy the Website using Docker:
• Install Docker on the EC2 instance.
• Transfer the Docker image from your local machine to the EC2 instance.
• Run the Docker container to deploy the website.

13. Tes,ng:
• Perform manual tes,ng of the website to ensure that all pages and features
are working correctly.
• Test the website's func,onality within the Docker container.
14. Documenta,on:
• Create a README.md file in your GitHub repository with instruc,ons on how
to set up the project, deploy the website using CI/CD, Terraform, and Docker.


• Document the CI/CD workflow and explain how it ensures automa,c
deployment.
• Include any challenges faced during the process and how you overcame
them.


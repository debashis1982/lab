* Install Jenkins - https://docs.aws.amazon.com/aws-technical-content/latest/jenkins-on-aws/installation.html
* start jenkins - sudo service jenkins start
* Install git - sudo yum install git -y
* install maven - sudo yum install maven -y
* Prepare jenkinsfile
* Create webhook - http://<jenkins_instance>/github-webhook
* Install docker - sudo amazon-linux-extras install docker
* Give jenkins permission to docker by adding jenkins to docker group- sudo usermod -aG docker jenkins
* Restart jenkins - sudo service jenkins start
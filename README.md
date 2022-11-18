# Jenkins Pipeline

## How to Install Jenkins in AWS EC2 Ubuntu Instance

1. sudo apt update 
2. sudo apt install openjdk-8-jdk -y
3. visit:     https://pkg.jenkins.io/debian-stable/
4. sudo systemctl start jenkins
5. sudo systemctl enable jenkins
6. sudo systemctl status jenkins
7. add 8080 port to the security group
8. sudo cat /var/lib/jenkins/secrets/initialAdminPassword

# GitOps - Manifest for Complete DevOps Tutorial
for windows:
---------------
Install Jenkings from official site : https://www.jenkins.io/download/#downloading-jenkins and always take LTS version.

for linux/debian/ubuntu
-----------------------

Install jenkins
----------------
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins
For java
---------
sudo apt update
sudo apt install openjdk-11-jre
java -version
openjdk version "11.0.12" 2021-07-20
OpenJDK Runtime Environment (build 11.0.12+7-post-Debian-2)
OpenJDK 64-Bit Server VM (build 11.0.12+7-post-Debian-2, mixed mode, sharing)
Note:
------------
By default, your Jenkins runs at https://localhost:8080/. This can be changed by editing jenkins.xml , which is located in your installation directory. This file is also the place to change other boot configuration parameters, such as JVM options, HTTPS setup, etc.

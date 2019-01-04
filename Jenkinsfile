pipeline {
    agent any
    stages{
        stage("Git Clone"){
            steps{
                git 'git@github.com:farrukh90/webserver_with_jenkins.git'
            }
        }
        stage("Copy file to Web"){
            steps{
                sh "cp -f index.html  /var/www/html/index.html"
            }
        }
    }
}
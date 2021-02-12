pipeline {
    agent any
    environment {
        PATH = "/usr/local/src/apache-maven"
    }
    stages {
        stage("Code checkout"){
        }
        stage("Build code"){
            steps{
              sh "mvn clean install"
            }
        }
        stage("Deploy"){
        }
    }
}

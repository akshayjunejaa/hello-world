pipeline {
    agent any
    environment {
        PATH = "/usr/local/src/apache-maven:$PATH"
    }
    stages {
        stage("Code checkout"){
            steps{
               git credentialsId: 'git_credentials', url: 'https://github.com/ravdy/hello-world.git'
            }
        }
        stage("build code"){
            steps{
              sh "mvn clean install"
            }
                 
                }
            }
        }
    }
}

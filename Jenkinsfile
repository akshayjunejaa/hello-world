pipeline {
    agent any
    tools {
        maven '/usr/local/src/apache-maven' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}		

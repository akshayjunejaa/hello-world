pipeline {
	agent any
	tools {
		maven '/usr/local/src/apache-maven' 
	}
	stages {
		stage('example') {
			steps {
				sh 'mvn --version'
			}
		}
	}
}		

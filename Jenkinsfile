pipeline {
	agent any
	tools {
		maven '/usr/local/src/apache-maven' 
	}
	stages {
		stages ('example') {
			steps {
				sh 'mvn --version'
			}
		}
	}
}		

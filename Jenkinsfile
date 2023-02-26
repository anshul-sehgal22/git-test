pipeline {
	agent any
	options {
		timeout(time: 20, unit: 'MINUTES')
		disableConcurrentBuilds()
		retry(1)
	}
	
	environment{
		OWERN="Anshul Sehgal"
	}
	
	stages {
		checkout scm
		
		stage('Do Something') {
			steps {
				sh 'ls -ltr'
			}
		}
	}
	
}

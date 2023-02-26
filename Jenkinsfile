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
		stage('Checkout') {
			checkout scm
		}
		
		stage('Do Something') {
			sh 'ls -ltr'
		}
	}
	
}

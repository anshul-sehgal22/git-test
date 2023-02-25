pipeline {
    stages {
        stage('checkout') {
            steps {
                    checkout scm
            }
        }
        stage('Do Something') {
            steps {
                    sh 'cat test.py'
            }
        }
    }
}

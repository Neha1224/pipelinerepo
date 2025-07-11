pipeline {
    agent any { label 'Neha' }

    stages {
        stage('a') {
            steps {
                echo 'sending notification'
            }
        }
        stage('b') {
            steps {
                echo 'testing code'
            }
        }
        stage('c') {
            steps {
                echo 'checking out code'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Hello 1') {
            steps {
                 echo 'Hello, Node'
            }
        }
        stage('Hello 2') {
            steps {
                echo 'Hello, Npm'
            }
        }
        stage('Install node packages') {
            steps {
                sh 'npm install'
            }
        }
    }
}
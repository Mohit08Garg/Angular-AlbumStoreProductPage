pipeline {
    agent {
        docker { image 'node:8-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
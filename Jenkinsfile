pipeline {
    agent {
        node {
            label 'my-first-build'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
pipeline {
    agent { docker { image 'python:3.8.8-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

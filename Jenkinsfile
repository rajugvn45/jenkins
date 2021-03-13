pipeline {
    agent { docker { image 'python:3.9-slim-buster' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

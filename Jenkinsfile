/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:alpine3.16' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

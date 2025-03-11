/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.13.2-alpine3.21' } }
    environment {
        PATH = "/usr/local.bin:$PATH"
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

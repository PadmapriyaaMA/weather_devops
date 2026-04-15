pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'No build required for static HTML website'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests defined for static website'
            }
        }

        stage('Deploy Website') {
            steps {
                echo 'Starting local server...'
                bat 'python -m http.server 8000'
            }
        }
    }
}
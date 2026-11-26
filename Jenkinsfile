pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Fetching source code from GitHub'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}

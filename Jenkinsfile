pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                checkout scm
                echo 'GitHub repository checked out successfully'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing completed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment completed'
            }
        }
    }
}

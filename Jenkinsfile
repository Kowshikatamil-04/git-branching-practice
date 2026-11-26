pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                checkout scm
                echo 'Repository checkout successful'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing completed successfully'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment completed successfully'
            }
        }
    }
}

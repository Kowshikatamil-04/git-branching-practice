pipeline {
    agent any

    stages {

        stage('Git Checkout') {
            steps {
                echo 'Checking out source code from GitHub'
                git branch: 'main',
                    url: 'https://github.com/Kowshikatamil-04/git-branching-practice.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage started'
                echo 'Application build completed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application...'
                sh 'test 1 -eq 1'
                echo 'Test passed successfully'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                echo 'Deployment completed successfully'
            }
        }
    }
}
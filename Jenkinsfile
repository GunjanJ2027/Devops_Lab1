pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'echo Build step executed successfully'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests passed successfully'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                bat 'echo Deployment completed successfully'
            }
        }
    }
}

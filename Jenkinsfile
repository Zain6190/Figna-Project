pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying to staging/production...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Notify team.'
        }
        failure {
            echo 'Pipeline failed! Check logs.'
        }
    }
}

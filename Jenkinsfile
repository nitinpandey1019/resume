pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out successfully'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building Project'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running Tests'
            }
        }
    }

    post {
        success {
            echo 'Pipeline Success'
        }

        failure {
            echo 'Pipeline Failed'
        }
    }
}

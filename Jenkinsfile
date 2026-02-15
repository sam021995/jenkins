pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application...'
                sh 'echo Build step executed'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Test step executed'
            }
        }

        stage('Deploy123') {
            steps {
                echo 'Deploying application...'
                sh 'echo Deploy step executed'
            }
        }

    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}

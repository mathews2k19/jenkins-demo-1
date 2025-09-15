pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Running build step...'
                // Replace this with your build command if you have one
                bat 'echo Building on Windows...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Replace with actual test command
                bat 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Replace with actual deploy steps
                bat 'echo Deploy step...'
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

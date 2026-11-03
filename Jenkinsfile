
pipeline {
    agent any

    stages {
        stage('Welcome') {
            steps {
                echo 'Welcome to GitHub and Jenkins!'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                bat 'echo Build Successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project...'
                bat 'echo Testing Successful'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project...'
                bat 'echo Deployment Successful'
            }
        }
    }
}

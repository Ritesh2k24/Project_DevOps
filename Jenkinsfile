pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Ritesh2k24/Project_DevOps.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the application"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying to server"'
            }
        }
    }
}

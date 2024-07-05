pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/burrasatyanarayana/jenkins' // Change to your repository URL
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
                // Add build commands here, e.g., npm install for a Node.js project
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                // Add test commands here, e.g., npm test for a Node.js project
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the project..."'
                // Add deploy commands here
            }
        }
    }
}

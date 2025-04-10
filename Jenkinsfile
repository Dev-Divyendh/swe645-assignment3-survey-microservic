pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from GitHub repository
                git 'https://github.com/your-username/jenkins-dummy-cicd.git'
            }
        }

        stage('Build') {
            steps {
                // Print a message to show the build is working
                echo 'Building the project...'
                sh 'echo "Build complete!"'
            }
        }

        stage('Deploy') {
            steps {
                // Simulate a deployment message
                echo 'Deploying application...'
                sh 'echo "Deployment complete!"'
            }
        }
    }
}

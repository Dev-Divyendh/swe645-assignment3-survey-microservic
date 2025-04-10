pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git(
                    url: 'https://github.com/Dev-Divyendh/swe645-assignment3-survey-microservic.git',
                    branch: 'main', // Make sure to specify the correct branch
                    credentialsId: 'github-credentials' // Use the credentials you've set up for GitHub
                )
            }
        }
        stage('Build') {
            steps {
                echo 'Building the projects...'
                // Add your build steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add your deploy steps here
            }
        }
    }
}

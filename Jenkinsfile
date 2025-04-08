pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo '✅ Cloning the repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo '🛠️ Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying application...'
            }
        }
    }
}

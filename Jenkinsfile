pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Starting build..."
                // Allora optimization step
                allora {
                    strategy 'speed'
                    optimize true
                }
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
    }
}

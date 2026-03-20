pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Starting build..."
                // Remove or comment out this line:
                // allora {
                //     strategy 'speed'
                //     optimize true
                // }
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
    }
}

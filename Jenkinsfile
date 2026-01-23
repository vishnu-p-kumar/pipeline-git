pipeline {
    agent any // Specifies where the pipeline will run (any available agent)
    stages {
        stage('Plain') {
            steps {
                echo 'Planning...' // Example step: print a message
                // Add your build commands here, e.g., 'sh "mvn clean install"'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...' // Example step: print a message
                // Add your build commands here, e.g., 'sh "mvn clean install"'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...' // Example step: print a message
                // Add your test commands here, e.g., 'sh "mvn test"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...' // Example step: print a message
                // Add your deploy commands here, e.g., 'sh "your_deploy_script.sh"'
            }
        }
    }
}

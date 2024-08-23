pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Example: Compile your code or run a build command
                sh 'echo "Running build command..."'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Example: Run your tests
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Example: Deploy your application
                sh 'echo "Deploying application..."'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished!'
        }
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}

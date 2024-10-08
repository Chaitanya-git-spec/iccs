pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
        sh 'echo "Running build command..."'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing...'
        sh 'echo "Running tests..."'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying...'
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
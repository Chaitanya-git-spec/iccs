pipeline {
  agent any  // This runs the pipeline on any available agent

  stages {
    stage('Build') {
      steps {
        echo 'Quick Build Stage'
        sh 'sleep 5'  // Simulate build with a 5-second sleep
      }
    }

    stage('Test') {
      steps {
        echo 'Quick Test Stage'
        sh 'sleep 5'  // Simulate tests with a 5-second sleep
      }
    }

    stage('Deploy') {
      steps {
        echo 'Quick Deploy Stage'
        sh 'sleep 5'  // Simulate deployment with a 5-second sleep
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

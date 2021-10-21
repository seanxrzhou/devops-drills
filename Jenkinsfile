pipeline {
  agent any
  stages {
    stage('Pre Hello') {
      steps {
        sh 'echo "Test..."'
      }
    }

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }

  }
  environment {
    Stage = 'Dev'
  }
}

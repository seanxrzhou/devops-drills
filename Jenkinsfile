pipeline {
  agent any
  stages {
    stage('Prehello') {
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

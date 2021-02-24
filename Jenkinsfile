pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build ' echo "helloworld"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "test"'
      }
    }

  }
  environment {
    stage = 'deploy'
  }
}
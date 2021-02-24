pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'mvn clean install'
      }
    }

  }
  environment {
    stage = 'build'
  }
}
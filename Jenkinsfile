pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        bat 'mvn --version'
      }
    }
  }
  environment {
    Development = 'Dev'
  }
}
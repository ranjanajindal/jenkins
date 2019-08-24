pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'mvn --version'
      }
    }
  }
  environment {
    Developmnt = 'Dev'
  }
}
pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'mvn --version'
        mvn install package
      }
    }
  }
  environment {
    Development = 'Dev'
  }
}

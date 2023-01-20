pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        sh 'php --version'
      }
    }
    stage('test') {
      steps {
        sh 'php test.php'
      }
    }
  }
}

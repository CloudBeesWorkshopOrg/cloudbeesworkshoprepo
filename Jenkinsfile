pipeline {
  agent any
  stages {
    stage('Greet and Version') {
      parallel {
        stage('Greet') {
          steps {
            echo 'Hello'
          }
        }
        stage('') {
          steps {
            echo 'Hello'
            sh 'java --version'
          }
        }
      }
    }
  }
}
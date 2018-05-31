pipeline {
  agent { label 'jdk9' }
  stages {
    stage('GreetVersion') {
      steps {
        echo 'Hello'
        sh 'java -version'
      }
    }
  }
}

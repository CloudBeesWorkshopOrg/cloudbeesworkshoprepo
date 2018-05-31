pipeline {
  agent { label 'jdk9' }
  environment { GNAME='Alfonso' }
    stages {
    stage('GreetVersion') {
      steps {
        echo 'Hello'+env.GNAME
        sh 'java -version'
      }
    }
  }
}

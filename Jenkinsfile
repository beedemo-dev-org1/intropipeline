pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('SayHello') {
      steps {
        echo 'Hello Mani'
        sh 'java -version'
      }
    }
  }
}
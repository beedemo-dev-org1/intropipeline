pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('SayHello') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
}
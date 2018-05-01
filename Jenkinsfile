pipeline {
  agent any
  stages {
    stage('SayHello') {
      steps {
        echo 'Hello Mani'
        sh '''pipeline {
   agent any
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
            sh \'java -version\'
         }
      }
   }
}'''
        }
      }
    }
  }
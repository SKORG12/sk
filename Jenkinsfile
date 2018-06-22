pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Hello to Me') {
      steps {
        echo 'Hello Soudipta'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Soudipta'
  }
}
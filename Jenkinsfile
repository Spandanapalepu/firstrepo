pipeline {
  agent any
  stages {
    stage('checkout') {
      checkout scm
    }
    stage('print text') {
      steps {
        sh """
          echo "Hello World"
        """
      }
    }
  }

}

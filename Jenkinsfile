pipeline {
agent any
  stages {
    stage('checkout') {
      parallel (
  steps {
       sh "echo "Hello Everyone""
      }
      steps {
        sh "echo "Welcome""
      }
       )
    }
  }
}

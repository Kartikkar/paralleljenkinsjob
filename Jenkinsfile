pipeline {
agent any
  stages {
    stage('checkout') {
      parallel (
  steps {
       sh "echo "Hello Everyone""
      }
        stage('build') {
      steps {
        sh "echo "Welcome""
      }
        }
       )
    }
  }
}

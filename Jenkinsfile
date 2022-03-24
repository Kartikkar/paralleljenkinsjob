pipeline {
agent any
  stages {
    stage('checkout') {
      parallel (
  steps {
       sh "echo "Hello Everyone""
      }
        post (
      steps {
        sh "echo "Welcome""
      }
          )
        )
    }
  }
}

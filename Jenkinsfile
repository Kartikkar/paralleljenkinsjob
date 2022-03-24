pipeline {
agent any
  stages {
  parallel(
    stage('checkout') {
  steps {
       sh "echo "Hello Everyone""
      }
      steps {
        sh "echo "Welcome""
      }
    }
  )
  }
}

pipeline {
agent any
  stages {
  parallel(
    stage('checkout') {
  steps {
       sh "echo "Hello Everyone""
      }
    }
    stage('build') {
      steps {
        sh "echo "Welcome""
      }
    }
    }
  )
  }
}

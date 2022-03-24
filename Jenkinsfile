pipeline {
agent any
  stages {
    stage('parallel') {
    steps {
     parallel ( 'checkout'
               {
       sh "echo "Hello Everyone""
      }
               {
        sh "echo "Welcome""
      }
      )
    }
  }
}
}

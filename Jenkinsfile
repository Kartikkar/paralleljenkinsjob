pipeline {
agent any
  stages {
    stage('parallel') {
    steps {
     parallel ( 'checkout'
               {
       sh "echo "Hello Everyone""
      }
       'build'
               {
        sh "echo "Welcome""
      }
      )
    }
  }
}
}

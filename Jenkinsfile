pipeline {
agent any
  stages {
stage('parallel') {
  steps {
    parallel(
      a: {
       sh "echo "Hello Everyone""
      },
      b: {
        sh "echo "Welcome""
      }
    )
  }
}
}
}

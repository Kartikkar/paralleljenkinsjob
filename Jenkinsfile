pipeline {
    agent any
   stages{
   stage('test') {
      steps {
   parallel {
        stage('one') {
           steps{
            sh echo "good morning"
            }
        }
       stage('two') { 
           steps{
          sh echo "devops class" 
           }
           }
       }
    }
}
   }
}

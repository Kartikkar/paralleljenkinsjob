pipeline {
    agent any
   stages{
   stage('test') {
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

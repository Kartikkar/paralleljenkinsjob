pipeline {
    agent any
   stages{
   stage('test') {
   parallel {
        stage('one') {
           step {
            sh echo "good morning"
            }
        }
       stage('two') { 
           step {
          sh echo "devops class"
           }
           }
       }
}
   }
}

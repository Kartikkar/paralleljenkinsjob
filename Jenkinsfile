pipeline {
    agent any
   stages{
   stage('test') {
   parallel {
        stage('one') {
           steps {
            echo "good morning"
            }
        }
       stage('two') { 
           steps {
          echo "devops class"
           }
           }
       }
}
   }
}

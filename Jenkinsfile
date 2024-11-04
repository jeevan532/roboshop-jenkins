pipeline {
   agent any
   stages{
     stage('hello'){
       steps{
          echo hello world
       }
     }
   }
   post {
     always {
       echo 'send message'
     }
   }
}
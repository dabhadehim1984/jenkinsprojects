pipeline {
   agent any
   tools {
      maven 'maven'

   }
   stages {
     stage ('Fetch code') {
       steps {
         sh 'mvn clean'
       }
        

     }

     stage ('Build') {
       steps {
         sh 'mvn verify'
       }
        

     }

     stage ('Test') {
       steps {
         echo 'deploying the application'
       }
        

     }

   }
	
}

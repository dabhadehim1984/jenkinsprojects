pipeline {
   agent any
   tools {
      maven 'maven'

   }
   stages {
     stage ('Fetch code') {
       steps {
         git branch: 'master', url: 'https://github.com/dabhadehim1984/second-demo-project.git'
       }
        

     }

     stage ('Build') {
       steps {
         sh "mvn install"
       }
        

     }

     stage ('Test') {
       steps {
         sh "mvn test"
       }
        

     }

   }
	
}

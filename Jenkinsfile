pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
       stage("Testing my code"){

         steps{
           echo "Testing code againts CIS"
         }
       } 
      stage("Runnign powershell script")
      {
        steps {

          powershell '''write-host "This is from pipline as code"
          get-service'''
        }
        
      }
    }
}

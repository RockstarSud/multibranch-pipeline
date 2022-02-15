pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "install dependecies..."'  
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

     stage("Stage") { 
         steps { 
           sh 'echo "stage application..."'
         }
     }

      stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }
     }
  
   	}

   }

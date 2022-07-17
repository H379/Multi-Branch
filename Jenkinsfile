pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     
     
     tools {nodejs "nodejs"}

     stages {
      stage('Example') {
       steps {
        sh 'npm config ls'
      }
    }
  }
     
     
     
     
     
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }

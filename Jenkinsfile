pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "docker123"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}

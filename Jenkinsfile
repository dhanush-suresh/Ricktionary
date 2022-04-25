pipeline { 
 agent any 
 stages { 
  stage('Testing') { 
   steps{ 
       echo 'running Tests' 
       sh 'python lab.py' 
    } 
  }
  stage('Build') { 
   steps { 
    echo 'Building jar files...' 
    
   } 
  } 
 } 
}

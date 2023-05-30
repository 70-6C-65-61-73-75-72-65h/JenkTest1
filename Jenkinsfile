 pipeline {
  agent any
    
  tools {nodejs "NodeJs"}
    
  stages {
        
 
     
    stage('Build') {
      steps {
        sh 'npm install'
         sh 'npm run build'
      }
    }    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
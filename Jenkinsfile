 pipeline {
  agent any
    
  tools {nodejs "NodeJs"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/70-6C-65-61-73-75-72-65h/JenkTest1.git'
      }
    }
     
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
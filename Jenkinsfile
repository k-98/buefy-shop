pipeline {
  agent any
    
  tools {react "react"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/k-98/buefy-shop'
      }
    }
     
    stage('Build') {
      steps {
        sh 'yarn install'
        sh 'yarn dev'
         sh 'yarn build'
         sh 'yarn start'
      }
    }  
    
  }
}

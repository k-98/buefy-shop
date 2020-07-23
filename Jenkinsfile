pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/k-98/buefy-shop.git'
        bat 'npm install'
      }
    }
  }
}

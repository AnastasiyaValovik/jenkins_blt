pipeline {
  agent any
  
  stages {
    
      stage('Install npm packages') {
        steps{
          sh 'npm install'
        }
      }
      stage('Build') {
        steps {
          sh 'npm cypress run'
        }
      }
  }
}



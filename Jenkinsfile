pipeline {
  agent any
  
  stages {
    
      stage('Install npm packages') {
        steps{
          sh 'docker run -it -v $PWD:/e2e -w /e2e cypress/included:9.4.1'
        }
      }
  }
}



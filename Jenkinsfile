pipeline {
  agent any
  stages {
      stage('Checkout git') {
          steps {
              git branch: 'main', url: 'https://github.com/amaresh435/case_study_feb2023'
          }
      }
      
      stage ('Build & JUnit Test') {
          steps {
              sh 'BUILD Steps here00101' 
          }
          
      }
  }    
}

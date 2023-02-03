pipeline {
  agent any
  stages {
      stage('Checkout git') {
          steps {
              git 'https://github.com/amaresh435/case_study_feb2023.git'
          }
      }
      
      stage ('Build & JUnit Test') {
          steps {
              sh 'BUILD Steps here001' 
          }
          
      }
  }    
}

pipeline {
  agent any
  stages {
     stage('Git Checkout'){
            steps{
                script{   
                    git branch: 'main', url: 'https://github.com/amaresh435/case_study_feb2023.git'
                }
            }
        }  
      stage ('Build & JUnit Test') {
          steps {
              sh 'BUILD Steps here00101' 
          }
          
      }
  }    
}

pipeline {
  agent any
  stages {
    stage ('checkout'){
      steps {
        checkout scm
        }
      }
    stage ('execute'){
      steps {
        sh 'python3 analyze_excel.py'
      }
    }
   }        
}

pipeline {
  agent any
  stages {
    stage('install'){
     steps {
       sh 'sudo apt install apache2'
       
       sh 'sudo systemctl start apache2'
       
       sh 'sudo systemctl status apache2'
      }
    }
    stage('status'){
     steps {
          sh 'sudo systemctl status apache2'
      }
    }
    
    }
  }
  

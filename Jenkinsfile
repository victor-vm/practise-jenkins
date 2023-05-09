pipeline {
  agent any
  stages('Build') {
     steps {
       sh 'sudo apt install apache2'
       
       sh 'sudo systemctl start apache2'
       
       sh 'sudo systemctl status apache2'
      }
    }
  }
  

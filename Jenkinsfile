pipeline {
  agent any
  stages {
    stage('Setting the variables values') {
      steps {
        sh 'dig +short myip.opendns.com @resolver1.opendns.com'
      }
    }
  }
}
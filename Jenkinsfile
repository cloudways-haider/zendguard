pipeline {
  agent {
    node {
      label 'new'
    }

  }
  stages {
    stage('Syntax Check') {
      steps {
        sh 'ansible-playbook zend/site.yml -i zend/hosts --check'
      }
    }
  }
}
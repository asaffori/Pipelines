pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('error') {
      steps {
        bat 'echo 111'
      }
    }
  }
}
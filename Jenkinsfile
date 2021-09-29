pipeline {
  agent {
    node {
      label 'windows'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat 'npm install'
      }
    }

  }
}

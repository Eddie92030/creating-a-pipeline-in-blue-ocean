pipeline {
  agent {
    node {
      label 'windows'
    }

  }
  stages {
    stage('Build') {
      steps {
        powershell 'npm install'
      }
    }

  }
}

pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Prince-Nii/tic-tac-toe', branch: 'main')
      }
    }

    stage('Directory files') {
      steps {
        sh '''pwd
&& whoami && ls -la'''
      }
    }

  }
}
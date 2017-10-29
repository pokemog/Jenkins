pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
          powershell (returnStdout: true, script: 'Write-Output "Hello World!"')
      }
    }
    stage('Test') {
      steps {
        bat 'echo Test'
      }
    }
    stage('Deploy') {
      steps {
        bat 'echo Deploy'
      }
    }
  }
}
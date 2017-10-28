pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        pwd(tmp: true)
        validateDeclarativePipeline 'Jenkinsfile'
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
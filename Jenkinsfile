pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is the build step'
                script {
                    def msg = powershell (returnStdout: true, script: 'Write-Output "Hello World!"')
                    println msg
                }
            }
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
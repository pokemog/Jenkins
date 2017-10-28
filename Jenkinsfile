pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                define stdout = bat returnStdout: true, script: 'dir'
                println = stdout
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
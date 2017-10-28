pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps {
                def output = bat returnStdout: true, script: 'dir'
                println output
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
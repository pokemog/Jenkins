pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps {
                def output = bat returnStdout: true, script: 'dir'
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
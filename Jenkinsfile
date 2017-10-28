pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps {
                def output = 'This is my output'
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
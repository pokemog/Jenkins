pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                bat 'dir' 
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
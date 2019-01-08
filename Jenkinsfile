pipeline {
    agent any
    stages {
        stage('CleanWorkspace') {
            steps {
                cleanWs()
            }
        }
        stage('BuildWorkspace') {
            steps {
                sh 'make'
            }
         }
        stage('BuildWorkspace') {
            steps {
                sh 'make runInSequence'
            }    
        }
    }
}
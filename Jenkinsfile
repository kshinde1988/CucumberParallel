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
              gradle('clean build')
               }
            }
    }
}
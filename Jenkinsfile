pipeline{

    agent any

    stages {

        stage ('Compile Stage') {

            steps {
                
                    bat 'gradle clean build'

            }
        }
    stage ('Test Stage') {

            steps {
               
                    bat 'gradle runInParallel'


            }
        }

    }

}
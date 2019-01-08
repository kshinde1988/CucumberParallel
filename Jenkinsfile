pipeline{

    agent any

    stages {

        stage ('Compile Stage') {

            steps {
                
                    bat 'gradlew.bat clean build'

            }
        }
    stage ('Test Stage') {

            steps {
               
                    bat 'gradlew.bat runInParallel'


            }
        }

    }

}
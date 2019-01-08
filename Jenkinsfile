pipeline{

    agent any

    stages {

        stage ('Compile Stage') {

            steps {

                //withradle(gradle : 'GRADLE_HOME') {
                    bat 'gradle clean build'

                }

            }
        }
    stage ('Test Stage') {

            steps {

                 withMaven(gradle : 'GRADLE_HOME') {
                    bat 'runInParallel'

                }

            }
        }

    }

}
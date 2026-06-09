pipeline {
    agent any
    options {
        buildDiscarder(logRotator(
            artifactDaysToKeepStr: '',
            artifactNumToKeepStr: '5',
            daysToKeepStr: '',
            numToKeepStr: '5'
        ))
    }
    stages {
        stage('Hola') {
            steps {
                echo 'Hola Mundo desde Jenkins!'
            }
        }
    }
}

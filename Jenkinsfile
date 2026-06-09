pipeline {
    agent any
    options {
        buildDiscarder logRotator(artifactDaysToKeepSrt: '', artifactNumToKeeSrt: '5', daysToKeepStr: '', numToKeepStr: '5')
    }
    stages {
        stage('Hola') {
            steps {
                echo 'Hola Mundo desde Jenkins!'
            }
        }
    }
}

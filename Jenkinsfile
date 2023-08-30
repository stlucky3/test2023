pipeline {
    agent any
       stages {
        stage('Checkout From GitHub Repository') {
            steps {
                checkout scm
            }
        }
         stage('Maven Tool Build and Test Code') {
            steps {
                script {
                    sh 'mvn clean install'
                }
            }
        }
    }
}
